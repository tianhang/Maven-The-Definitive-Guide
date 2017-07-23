# Maven-The-Definitive-Guide
## maven project structure
## maven command line

generate project

``` 
    mvn archetype:generate 
    -DgroupId={project-packaging}  组织名，公司网址的反写 + 项目名
    -DartifactId={project-name} 项目名 + 模块名
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

  
