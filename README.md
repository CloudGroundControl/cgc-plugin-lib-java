### Introduction
This repository contains resources to generate cgc plugin model class files for Java developers.

Generate jar file containing all the class files.
```shell
mvn clean package
```
Generate jar file and install it to local maven repository (.m2 folder).
> This command should allow you to import generated jar file into your maven project.  
```shell
mvn clean install
```

Generate Java docs
```shell
mvn javadoc:javadoc
```