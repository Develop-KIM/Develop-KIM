Developer with 1 year of professional experience

  <br>
  <br>

<h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;">Open Source</h2>
  <ul>
    <li>
      <b>Hibernate ORM</b> -
      <a href="https://github.com/hibernate/hibernate-orm/pull/13050">PR #13050</a>:
      Fixed UNION queries rejecting the same Java type reached through different attribute paths (e.g. a <code>java.util.Date</code> on the entity vs. one inherited from a <code>@MappedSuperclass</code>) by returning shared per-precision <code>DateJavaType</code> instances
    </li>
    <li>
      <b>pgjdbc (PostgreSQL JDBC)</b> -
      <a href="https://github.com/pgjdbc/pgjdbc/pull/4297">PR #4297</a>:
      Fixed <code>PreparedStatement.getMetaData()</code> bypassing <code>prepareThreshold</code> — even at <code>prepareThreshold=0</code> a single call left a named <code>S_1</code> statement behind and broke connection poolers; routed describe through the same <code>isOneShotQuery</code> gate the execute paths use (a 42.7.8 regression, not a revert)
    </li>
    <li>
      <b>node-mysql2 (MySQL)</b> -
      <a href="https://github.com/sidorares/node-mysql2/pull/4425">PR #4425</a>:
      Fixed a failed <code>execute()</code> (from an undefined bind parameter) staying registered as the connection's active command, which deadlocked the following <code>ROLLBACK</code> — returned <code>null</code> from the execute path's catch so the command queue advances and the transaction can unwind
    </li>
    <li>
      <b>JetBrains Exposed (Kotlin SQL / ORM)</b> -
      <a href="https://github.com/JetBrains/Exposed/pull/2853">PR #2853</a>:
      Fixed a data race where a JDBC <code>Database</code>'s capability flags were computed through unsynchronized lazy init — switched to thread-safe lazy initialization so concurrent first access from multiple threads can't observe a torn or partially-built value
    </li>
    <li>
      <b>Axon Framework (CQRS / Event Sourcing)</b> -
      <a href="https://github.com/AxonIQ/AxonFramework/pull/4733">PR #4733</a>:
      Fixed annotated handler resolution invoking a shadowed supertype's <code>private</code> handler over the matching subtype handler when signatures matched — the comparator's final tiebreaker had ordered by declaring class name
    </li>
  </ul>
  <br>
  <br>

  <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;">Contact Me</h2>
  <a href="mailto:kimdonghwan913@gmail.com">
    <img src="https://img.shields.io/badge/kimdonghwan913@gmail.com-EA4335?style=flat&logo=Gmail&logoColor=white"/>
  </a>
  <a href="https://www.gitanimals.org/en_US?utm_medium=image&utm_source=Develop-KIM&utm_content=line">
  </a>

  <br>
  <br>

  <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;">Platforms & Languages</h2>
  <span>
    <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat&logo=Spring&logoColor=white">
    <img src="https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white">
    <img src="https://img.shields.io/badge/Nuxt-00DC82?style=flat&logo=nuxt&logoColor=white">
    <br><br>
    <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white">
    <img src="https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white">
    <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white">
    <img src="https://img.shields.io/badge/Javascript-F7DF1E?style=flat&logo=Javascript&logoColor=white">
  </span>
