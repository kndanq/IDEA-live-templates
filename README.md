# Custom IntelliJ IDEA Live Templates Java
### Create template
- Double `shift` and then hit `Live Templates`
- Create Live Template

![image](https://github.com/ndanqkhoa/idea-live-templates/assets/79648632/cf921a48-67f0-43fe-a8be-def173e8125c)

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
### test.assertion.equals
```java
org.junit.jupiter.api.Assertions.assertEquals($EXPECTED$, $ACTUAL$);
```
```xml
<template name="test.assertion.equals" value="org.junit.jupiter.api.Assertions.assertEquals($EXPECTED$, $ACTUAL$);" description="Assertions" toReformat="false" toShortenFQNames="true" useStaticImport="true">
  <variable name="EXPECTED" expression="" defaultValue="" alwaysStopAt="true" />
  <variable name="ACTUAL" expression="" defaultValue="" alwaysStopAt="true" />
  <context>
    <option name="JAVA_CODE" value="true" />
  </context>
</template>
```
### test.comment.method.under
```java
/**
 * Method under test:
 * {@link }
 */
```
```xml
<template name="test.comment.method.under" value="/**&#10; * Method under test:&#10; * {@link }&#10; */&#10;" description="/** Method under test  **/" toReformat="false" toShortenFQNames="false">
  <context>
    <option name="JAVA_CODE" value="true" />
  </context>
</template>
```
### test.extend.testcontainers
```java
extends com.faber.ConfigTestContainer.AbstractContainerBaseTest
```
```xml
<template name="test.extend.testcontainers" value="extends com.faber.ConfigTestContainer.AbstractContainerBaseTest" description="extends AbstractContainerBaseTest" toReformat="false" toShortenFQNames="true" useStaticImport="true">
  <context>
    <option name="JAVA_CODE" value="true" />
  </context>
</template>
```
### test.function.gwt
```java
@org.junit.jupiter.api.Test
void given_when$EXPR$_then() {
    // Given:
    
    // When:
    
    // Then:
}
```
```xml
<template name="test.function.gwt" value="@org.junit.jupiter.api.Test&#10;void given_when$EXPR$_then() {&#10;    // Given:&#10;    &#10;    // When:&#10;    &#10;    // Then:&#10;}" description="@Test" toReformat="true" toShortenFQNames="true" useStaticImport="true">
  <variable name="EXPR" expression="" defaultValue="" alwaysStopAt="true" />
  <context>
    <option name="JAVA_CODE" value="true" />
  </context>
</template>
```
### test.function.parameterized
```java
@org.junit.jupiter.params.ParameterizedTest
@org.junit.jupiter.params.provider.MethodSource("given$name$")
void given_when_then() {
    // Given:

    // When:

    // Then:
}

static Stream<Arguments> given$name$() {
    return Stream.of(
            Arguments.of(),
            Arguments.of(),
            Arguments.of());
}
```
```xml
<template name="test.function.parameterized" value="@org.junit.jupiter.params.ParameterizedTest&#10;@org.junit.jupiter.params.provider.MethodSource(&quot;given$name$&quot;)&#10;void given_when_then() {&#10;    // Given:&#10;&#10;    // When:&#10;&#10;    // Then:&#10;}&#10;&#10;static Stream&lt;Arguments&gt; given$name$() {&#10;    return Stream.of(&#10;            Arguments.of(),&#10;            Arguments.of(),&#10;            Arguments.of());&#10;}" description="@ParameterizedTest" toReformat="false" toShortenFQNames="true" useStaticImport="true">
  <variable name="name" expression="" defaultValue="" alwaysStopAt="true" />
  <context>
    <option name="JAVA_CODE" value="true" />
  </context>
</template>
```
