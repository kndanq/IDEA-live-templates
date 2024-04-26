### test.annotation.repository.mongo
```java
import org.springframework.boot.test.context.SpringBootTest;
import org.junit.jupiter.api.DisplayNameGeneration;
import org.junit.jupiter.api.DisplayNameGenerator.ReplaceUnderscores;

@SpringBootTest
@DisplayNameGeneration(ReplaceUnderscores.class)
```
```xml
<template name="test.annotation.repository.mongo" value="import org.springframework.boot.test.context.SpringBootTest;&#10;import org.junit.jupiter.api.DisplayNameGeneration;&#10;import org.junit.jupiter.api.DisplayNameGenerator.ReplaceUnderscores;&#10;&#10;@SpringBootTest&#10;@DisplayNameGeneration(ReplaceUnderscores.class)" description="@SpringBootTest" toReformat="true" toShortenFQNames="true" useStaticImport="true">
  <context>
    <option name="JAVA_CODE" value="true" />
  </context>
</template>
```