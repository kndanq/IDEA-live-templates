### test.annotation.repository.sql
```java
import org.springframework.boot.test.autoconfigure.orm.jpa.DataJpaTest;
import org.junit.jupiter.api.DisplayNameGeneration;
import org.junit.jupiter.api.DisplayNameGenerator.ReplaceUnderscores;

@DataJpaTest
@DisplayNameGeneration(ReplaceUnderscores.class)
```
```xml
<template name="test.annotation.repository.sql" value="import org.springframework.boot.test.autoconfigure.orm.jpa.DataJpaTest;&#10;import org.junit.jupiter.api.DisplayNameGeneration;&#10;import org.junit.jupiter.api.DisplayNameGenerator.ReplaceUnderscores;&#10;&#10;@DataJpaTest&#10;@DisplayNameGeneration(ReplaceUnderscores.class)        " description="@DataJpaTest" toReformat="true" toShortenFQNames="true" useStaticImport="true">
  <context>
    <option name="JAVA_CODE" value="true" />
  </context>
</template>
```