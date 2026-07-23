# GraphStream -- JavaFX UI for Java 11


## This project is a fork of [GraphStream/gs-ui-javafx](https://github.com/graphstream/gs-ui-javafx), redistributed under CECILL-C license.

The GraphStream project is a java library that provides an API to model, analyze and visualize graphs and dynamic graphs.

This module contains a JavaFX implementation of the GraphStream Viewer.

Check out the the original projects website <http://www.graphstream-project.org/> for more information.

## Install UI

`gs-ui-javafx` is a plugin to the  `gs-core` main project. 

Maven users may include major releases of `gs-core` and `gs-ui-javafx` as dependencies: 

```xml
<dependencies>
    <dependency>
        <groupId>io.github.de-tu-dresden-inf-lat</groupId>
        <artifactId>gs-core</artifactId>
        <version>2.2</version>
    </dependency>

    <dependency>
        <groupId>io.github.de-tu-dresden-inf-lat</groupId>
        <artifactId>gs-ui-javafx</artifactId>
        <version>2.1</version>
    </dependency>
</dependencies>
```

## Configure UI

`gs-core` needs to be told which UI implementation to use. Simply add a system property to you project: 

```java
System.setProperty("org.graphstream.ui", "javafx");
```

Or use the command line :

```bash
java -Dorg.graphstream.ui=javafx YourClass
```

## Help

You may check the documentation on the original projects [website](http://graphstream-project.org).
## License

See the COPYING file.