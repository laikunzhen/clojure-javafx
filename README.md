# Desktop Application

A calculator desktop application for OS X written with Clojure and JavaFX.

## Usage

You need Leiningen, Maven and Ant

Download and install "jfxrt.jar" into your local Maven repository.

Download the App Builder from https://java.net/projects/appbundler/downloads

## Build

```
build.sh
```

## Install the JavaFX runtime

```
mvn install:install-file  \
 -Dfile=$JFXRTPATH/jfxrt.jar \
 -DgroupId=com.oracle \
 -DartifactId=javafx-runtime \
 -Dpackaging=jar \
 -Dversion=2.2.3
```

## Credits

http://eddmann.com/posts/infix-calculator-in-clojure/

## License

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
