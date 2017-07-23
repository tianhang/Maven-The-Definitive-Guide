# Maven-The-Definitive-Guide
## maven project structure
<p align="center">
<img alt="AndroidInterviewQuestions" src="https://github.com/stormzhang/android-interview-questions-cn/blob/master/assets/android-interview-questions.png?raw=true">
</p>
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
   $mvn archetype:generate 
   -DgroupId=com.mycompany.app 
   -DartifactId=my-app 
   -DarchetypeArtifactId=maven-archetype-quickstart 
   -DinteractiveMode=false
```

  
