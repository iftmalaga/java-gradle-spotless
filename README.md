# Keep your code with Gradle [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

## :clipboard: Introduction

[Spotless](https://github.com/diffplug/spotless) Ideally, a code formatter can do more than just find formatting errors - it should fix them as well.

## :cloud: Getting Started

Follow along this notes. You will need to have at least [Java 8](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html) installed or some openJDK distribution, and [Gradle](https://gradle.org/) on the PATH. 

You can use some package management tool for windows. E.g. [Chocolatey](https://chocolatey.org/)

*	[OpenJDK8 Zulu](https://azul.com) - Java Development Kits (OpenJDK build)

```
choco install zulu8 -y
```

*	[Gradle](https://gradle.org/) - Constructor and manager dependencies

```
choco install gradle --version 5.6.4 -y
```

Clone this repository, and fire up a command-line tool.

> To know a code formatter can do more than just find formatting errors - it should fix them as well

## :computer: Steps

To execute the next command line:

```
gradle build
```

You can check unused import is removed out _Alphanumeric_ class:

```java
import java.lang.Number
```
