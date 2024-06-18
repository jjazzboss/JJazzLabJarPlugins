# JJazzLab jar plugins

This Maven project generates from each JJazzLab plugin a jar deployable on the [Sonatype Maven Central](https://central.sonatype.com) repository. 
These jar plugins are to be used with the [JJazzLab Toolkit](https://github.com/jjazzboss/JJazzLabToolkit).

## YamJJazz plugin ([source code](https://github.com/jjazzboss/JJazzLab/tree/master/plugins/YamJJazz))

## FluidSynthEmbeddedSynth plugin ([source code](https://github.com/jjazzboss/JJazzLab/tree/master/plugins/FluidSynthEmbeddedSynth))

## How to use

For sample code how to use the JJazzLab Toolkit with these plugins, check out the [DemoApp](https://github.com/jjazzboss/JJazzLabToolkit/tree/main/DemoApp).

## Build

Note that there is usually no need to build those jar plugins yourself since they are available on [Sonatype Maven Central](https://central.sonatype.com).
 
To build yourself, you must have previously built JJazzLab locally (`mvn clean install`), so that all JJazzLab plugins modules are available in your local Maven repository (usually `$HOME/.m2`).

Fork and run `mvn clean deploy`.

Requirements
- Java JDK 17
- Apache Maven version 3.6.3 or later