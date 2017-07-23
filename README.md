# Maven-The-Definitive-Guide
## maven project structure

<p align="left">
<img alt="structure" src="https://github.com/tianhang/Maven-The-Definitive-Guide/blob/master/assets/proj_structure.png" width="50%">
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

## eclipse with maven

use maven to create web project

  
<p align="left">
<img alt="structure" src="https://github.com/tianhang/Maven-The-Definitive-Guide/blob/master/assets/step1.png" width="50%">
</p>

<p align="left">
<img alt="structure" src="https://github.com/tianhang/Maven-The-Definitive-Guide/blob/master/assets/step2.png" width="50%">
</p>

initial project structure
<p align="left">
<img alt="structure" src="https://github.com/tianhang/Maven-The-Definitive-Guide/blob/master/assets/struct1.png" width="50%">
</p>

<p align="left">
<img alt="structure" src="https://github.com/tianhang/Maven-The-Definitive-Guide/blob/master/assets/step3.png" width="50%">
</p>
