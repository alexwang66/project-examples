# Clone the code
git clone https://github.com/alexwang66/project-examples.git

# Maven demo
Make sure you are using jdk 1.8
```dtd
/usr/libexec/java_home -V
        1.8.301.09 (x86_64) "Oracle Corporation" - "Java" /Library/Internet Plug-Ins/JavaAppletPlugin.plugin/Contents/Home
        1.8.0_392 (x86_64) "OpenLogic-OpenJDK" - "OpenLogic-OpenJDK 8" /Library/Java/JavaVirtualMachines/openlogic-openjdk-8.jdk/Contents/Home

 export JAVA_HOME=`/usr/libexec/java_home -v 1.8.0_392`
```

## Set up settings.xml
![img_1.png](img_1.png)
copy the settings.xml int ~/.m2/settings.xml

## Maven package
```dtd
cd project-examples/maven-examples/maven-example
mvn package
```
## Maven deploy
![img.png](img.png)

Go to Deploy tab and copy the code snippet, paste into the bottom part of the file
```
/project-examples/maven-examples/maven-example/pom.xml
```
![img_2.png](img_2.png)

Run maven deploy
```dtd
mvn deploy
```
![img_3.png](img_3.png)
You can see the package is download and upload into Artifactory server.

# Docker demo
