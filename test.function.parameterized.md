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