Sample Javafx package demonstrating how to package a java desktop application into a windows executable.   

Used maven, jlink and jpackage.  
```
mvn clean package
mvn javafx:jlink
mvn jpackage:jpackage
```

Executable located in ```\demo\target\demo-zip\bin\launcher```