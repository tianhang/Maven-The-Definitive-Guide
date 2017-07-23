# Maven-The-Definitive-Guide
## maven project structure
## maven command line

generate project

``` 
    mvn archetype:generate -DgroupId={project-packaging}
    -DartifactId={project-name}
    -DarchetypeArtifactId=maven-archetype-quickstart
    -DinteractiveMode=false 
```
for example 
```
    $ mvn archetype:generate -DgroupId=com.mkyong 
    -DartifactId=NumberGenerator
	-DarchetypeArtifactId=maven-archetype-quickstart 
    -DinteractiveMode=false
```

  
