# JJazzLab jar plugins

This Maven project generates, for each of the [JJazzLab plugins](https://github.com/jjazzboss/JJazzLab/tree/master/plugins), a jar deployable on the Sonatype Maven Central repository. 

These jar plugins are to be used with the [JJazzLab Toolkit](https://github.com/jjazzboss/JJazzLabToolkit).

## How to use

For sample code how to use the JJazzLab Toolkit with these plugins, check out the Toolkit's [DemoApp](https://github.com/jjazzboss/JJazzLabToolkit/tree/main/DemoApp).

## Build

Requirements: Java JDK 17, Apache Maven version 3.6.3 or later

There is usually no need to build those jar plugins yourself since they are available on [Sonatype Maven Central](https://central.sonatype.com). But if you insist:
 
- Clone and build [JJazzLab](https://github.com/jjazzboss/JJazzLab) locally (`mvn clean install`), so that all JJazzLab plugins modules are available in your local Maven repository (usually `$HOME/.m2`)
- Clone this repo 
- Run `mvn clean install`

