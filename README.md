Developer with 1 year of professional experience

  <br>
  <br>

<h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;">Open Source</h2>
  <ul>
    <li>
      <b>Hibernate ORM</b> -
      <a href="https://github.com/hibernate/hibernate-orm/pull/13050">PR #13050</a>:
      Fixed UNION queries rejecting the same Java type reached through different attribute paths
    </li>
    <li>
      <b>pgjdbc (PostgreSQL JDBC)</b> -
      <a href="https://github.com/pgjdbc/pgjdbc/pull/4297">PR #4297</a>:
      Fixed <code>PreparedStatement.getMetaData()</code> bypassing <code>prepareThreshold</code> and leaving a named server-side statement behind
    </li>
    <li>
      <b>node-mysql2 (MySQL)</b> -
      <a href="https://github.com/sidorares/node-mysql2/pull/4425">PR #4425</a>:
      Fixed a failed <code>execute()</code> staying the connection's active command and deadlocking the following <code>ROLLBACK</code>
    </li>
    <li>
      <b>node-mysql2 (MySQL)</b> -
      <a href="https://github.com/sidorares/node-mysql2/pull/4394">PR #4394</a>:
      Fixed a user <code>typeCast</code> never running on NULL columns under the binary protocol
    </li>
    <li>
      <b>ioredis (Redis)</b> -
      <a href="https://github.com/redis/ioredis/pull/2137">PR #2137</a>:
      Fixed a zero-argument <code>SUNSUBSCRIBE</code> being dropped when a cluster client has sharded subscribers
    </li>
    <li>
      <b>node-redis (Redis)</b> -
      <a href="https://github.com/redis/node-redis/pull/3342">PR #3342</a>:
      Fixed <code>XADD</code>/<code>XTRIM</code> dropping an explicit <code>LIMIT 0</code>, which silently capped trimming instead of making it unlimited
    </li>
    <li>
      <b>node-redis (Redis)</b> -
      <a href="https://github.com/redis/node-redis/pull/3333">PR #3333</a>:
      Fixed <code>XGROUP CREATE</code>/<code>SETID</code> dropping an explicit <code>ENTRIESREAD 0</code>, so a consumer group's lag counter could not be reset
    </li>
    <li>
      <b>node-redis (Redis)</b> -
      <a href="https://github.com/redis/node-redis/pull/3328">PR #3328</a>:
      Fixed <code>MEMORY USAGE</code> dropping an explicit <code>SAMPLES 0</code>, which silently fell back to the server default of 5 samples
    </li>
    <li>
      <b>Gradle</b> -
      <a href="https://github.com/gradle/gradle/pull/38509">PR #38509</a>:
      Fixed precompiled script plugin tasks losing the build dependencies of their generated sources
    </li>
    <li>
      <b>Gradle</b> -
      <a href="https://github.com/gradle/gradle/pull/38762">PR #38762</a>:
      Fixed file collections losing their display name after a configuration cache restore, which degraded error messages
    </li>
    <li>
      <b>Gradle</b> -
      <a href="https://github.com/gradle/gradle/pull/38649">PR #38649</a> (co-author):
      Fixed non-abstract <code>Property</code> getters losing their owner after a configuration cache restore
    </li>
    <li>
      <b>Puppeteer</b> -
      <a href="https://github.com/puppeteer/puppeteer/pull/15292">PR #15292</a>:
      Made mutation-based waits (<code>waitForSelector</code> with <code>&gt;&gt;&gt;</code>, text and XPath selectors) observe changes inside open shadow roots
    </li>
    <li>
      <b>Puppeteer</b> -
      <a href="https://github.com/puppeteer/puppeteer/pull/15358">PR #15358</a>:
      Fixed <code>page.setContent()</code> going through <code>document.write</code>, which triggered Chrome's intervention and blocked cross-site parser-blocking scripts
    </li>
    <li>
      <b>Playwright Java</b> -
      <a href="https://github.com/microsoft/playwright-java/pull/1967">PR #1967</a>:
      Fixed tracing with <code>setSources(true)</code> capturing no source files for browsers attached via <code>connect()</code>, because call stacks were sent on the wrong connection
    </li>
    <li>
      <b>Playwright Java</b> -
      <a href="https://github.com/microsoft/playwright-java/pull/1948">PR #1948</a>:
      Fixed <code>Screencast.showActions()</code> rejecting every <code>AnnotatePosition</code> value because the enum was sent to the driver without its Gson serializer
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
