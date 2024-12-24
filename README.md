Sample Javafx package demonstrating how to package a java desktop application into a windows executable.   

Used maven, jlink, jpackage, wix toolset. In java 13.     

```mvn clean package``` - To reset and remove the target folder    

```mvn javafx:jlink``` - Creating a launcher batch file at ```\target\demo-zip\bin\launcher```   

```mvn jpackage:jpackage``` - Creating an installer at ```\target\dist\DemoApp-1.0.0```