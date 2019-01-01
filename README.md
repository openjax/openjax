# OpenJAX Classic

**Simple, high-performance, Java API eXtensions**

OpenJAX Classic is a collection of modules that supplement Java's standard APIs.

## Simple

The supplementary APIs are designed to be simple, and as non-coupling as possible.

## High-Performance

The APIs are implemented to minimize both process and memory complexity.

## Modules

* **[autogen][autogen]**: Modules that utilize the [Code Generation][codegen] process to obtain better language cohesion, and faster runtime performance.
* **[cdm][cdm]**: _Code Design Model_ An abstraction of the Java programming language, in Java.
* **[exec][exec]**: APIs for external process execution and environment management.
* **[io][io]**: APIs that supplement the `java/io` and `java/nio` packages for I/O operations.
* **[jaxb][jaxb]**: Modules that supplement JAXB with cohesive and high-performance APIs and tools.
* **[jci][jci]**: _Java Compiler Interface_ An implementation of an in-memory-compiler.
* **[json][json]**: APIs for efficiently reading and parsing JSON documents.
* **[lang][lang]**: APIs that supplement the `java/lang` package with simple and useful extensions.
* **[logging][logging]**: APIs that provide simple _logging_ extensions to [SLF4J][slf4j].
* **[math][math]**: APIs that supplement the `java/math` package with higher-performance alternatives, and simple and useful extensions.
* **[maven][maven]**: APIs that supplement Maven's APIs with cohesive abstractions, and simple and useful extensions.
* **[measure][measure]**: A nimble datatype abstraction that expresses numerical values with units, supporting automatic unit reduction.
* **[net][net]**: APIs that supplement the `java/net` package with higher-performance alternatives, and simple and useful extensions.
* **[security][security]**: APIs that provide simple security abstractions.
* **[sql][sql]**: APIs that supplement the `java/sql` package with simple and useful extensions.
* **[test][test]**: APIs that provide simple _test_ extensions to [JUnit][junit], and Maven's [maven-surefire-plugin][maven-surefire-plugin].
* **[util][util]**: APIs that supplement the `java/util` package with higher-performance alternatives, and simple and useful extensions.
* **[xml][xml]**: Modules for efficiently reading, writing, and validating XML documents.

### License

This project is licensed under the MIT License - see the [LICENSE.txt](LICENSE.txt) file for details.

[autogen]: /../../../../openjax/classic-autogen
[cdm]: /../../../../openjax/classic-cdm
[exec]: /../../../../openjax/classic-exec
[io]: /../../../../openjax/classic-io
[jaxb]: /../../../../openjax/classic-jaxb
[jci]: /../../../../openjax/classic-jci
[json]: /../../../../openjax/classic-json
[lang]: /../../../../openjax/classic-lang
[logging]: /../../../../openjax/classic-logging
[math]: /../../../../openjax/classic-math
[measure]: /../../../../openjax/classic-measure
[maven]: /../../../../openjax/classic-maven
[net]: /../../../../openjax/classic-net
[security]: /../../../../openjax/classic-security
[sql]: /../../../../openjax/classic-sql
[test]: /../../../../openjax/classic-test
[util]: /../../../../openjax/classic-util
[xml]: /../../../../openjax/classic-xml

[codegen]: https://en.wikipedia.org/wiki/Code_generation_(compiler)
[junit]: https://junit.org
[maven-surefire-plugin]: https://maven.apache.org/surefire/maven-surefire-plugin/
[slf4j]: https://www.slf4j.org/