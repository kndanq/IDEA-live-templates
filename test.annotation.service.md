### test.annotation.service
```java
import org.junit.jupiter.api.DisplayNameGeneration;
import org.junit.jupiter.api.DisplayNameGenerator.ReplaceUnderscores;
import org.junit.jupiter.api.extension.ExtendWith;
import org.mockito.junit.jupiter.MockitoExtension;

@ExtendWith(MockitoExtension.class)
@DisplayNameGeneration(ReplaceUnderscores.class)
```
```xml
<template name="test.annotation.service" value="import org.junit.jupiter.api.DisplayNameGeneration;&#10;import org.junit.jupiter.api.DisplayNameGenerator.ReplaceUnderscores;&#10;import org.junit.jupiter.api.extension.ExtendWith;&#10;import org.mockito.junit.jupiter.MockitoExtension;&#10;&#10;@ExtendWith(MockitoExtension.class)&#10;@DisplayNameGeneration(ReplaceUnderscores.class)" description="@ExtendWith(MockitoExtension.class)" toReformat="true" toShortenFQNames="true" useStaticImport="true">
  <context>
    <option name="JAVA_CODE" value="true" />
  </context>
</template>
```