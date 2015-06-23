# jMCCS - OS X implementation

This Maven project implements the `Monitor`-interface and extends the `MonitorManager`-class that are required by
[jMCCS][jmccs]. It uses [JNA][jna] to interact with the supplied native-library (`libmccs`) which is based on
[DDC-CI-Tools-for-OS-X][ddcciosx].

## Usage

As this is a Maven project, you can include this project in your application simply by depending on it.
(**Note:** the package is not yet in the Maven central repository. The following snippet will not work until it is pushed.)

```xml
<dependency>
    <groupId>de.pitkley</groupId>
    <artifactId>jmccs-osx</artifactId>
    <version>1.0-SNAPSHOT</version>
</dependency>
```

## License

This project is licensed under GPLv3, honoring that the original native code is licensed under GPLv3.

[jmccs]: https://github.com/pitkley/jmccs
[jna]: https://github.com/twall/jna
[ddcciosx]: http://github.com/jontaylor/DDC-CI-Tools-for-OS-X