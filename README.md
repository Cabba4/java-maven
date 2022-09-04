# java-and-maven

Make a new project using mvn with the command 

```bash
mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false
```

Make changes to the groupID and artifcatID

Then once build succeeds, cd to the new directory and run

```bash
mvn package
```

That should compile the project, error encountered might be regarding mvn-compiler version.

After that you can run the jar with the command

```bash
java -cp target/my-app-1.0-SNAPSHOT.jar com.mycompany.app.App
```

Was unable to figure out how to make the 

```bash
jav -jar target/hello-world-SNAPSHOT.jar 
```

command work (?) Something about App.java file I guess!

