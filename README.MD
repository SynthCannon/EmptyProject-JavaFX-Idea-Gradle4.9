### gradlewj
The file "gradlewj.bat" defines the path to a JDK. \
It may be used, when another java, than defined via JAVA_HOME is needed for the project. \
Modify that file, so that the path in it points to your JDK.

Use it, as if you would use gradlew.
```
gradlewj <GRADLEW COMMANDS>
```

### Build On Unix
To package the project as a jar type:
```
gradlew build
```
The output will be under `.\out`


### Run On Unix
To run the project as a java applicaiton type
```
gradlew run
```
The application will be started.



### Build On Windows
To package the project as a jar type:
```
gradle build
```
The output will be under `.\out`


### Run On Windows
To run the project as a java applicaiton type
```
gradle run
```
The application will be started.