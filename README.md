### Introduction
This repository contains resources to generate cgc plugin model class files for Java developers.

To generate jar file containing all the class files execute following commands.
```shell
mvn clean package
```
To generate jar file and install it to local maven repository (.m2 folder) execute following command.
> This command should allow you to import generated jar file into your maven project.  
```shell
mvn clean intall
```