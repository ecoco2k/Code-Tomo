README:

Note: Our current jar file is only supported on machines using Java 19 as well as JavaFX 19
Note: As JavaFX is no longer included in Java SDK Releases the project relies on JavaFX Dependencies.
Instructions to execute jar file -
1. Download JavaFX on your system, link: https://openjfx.io/
2. Download tomo.jar, note: Double-clicking will not work for execution
3. Open system terminal
4. Change current directory to directory housing tomo.jar
5. Find path for javafx-sdk-19/lib
6. Run the following command: java --module-path "JAVAFX-PATH-HERE" --add-modules javafx.controls,javafx.fxml -jar tomo.jar
7. Enjoy!

Note: Source code can be ran on Java 12 and above through a supported IDE
Instructions to run source code in IDE -
1. Download JavaFX on your system / Add JavaFX plugin to Eclipse or other IDE, link: https://openjfx.io/
2. Download SQLite jar, link: https://github.com/xerial/sqlite-jdbc#download
3. Place tomotemp folder into IDE as project
4. Include JavaFX SDK Library, JRE System Library (above Java-SE 12), JavaFX lib folder jars, and SQLite jar in project's MODULEPATH

Issues and Resolutions for jar file execution -
Note: When running in a supported IDE, older Java versions are supported.
Note: Current jar file was compiled with JDK19 and will need JDK19 to run.
Error: java.lang.UnsupportedClassVersionError
Solution: Update to current Java JDK version 19 
