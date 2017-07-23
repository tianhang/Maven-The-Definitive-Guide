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

<strong>initial project structure</strong>
<p align="left">
<img alt="structure" src="https://github.com/tianhang/Maven-The-Definitive-Guide/blob/master/assets/struct1.png" width="50%">
</p>

<strong>add missing folder manully, however you might meet error, "the source folder existed already !"</strong>
<p align="left">
<img alt="structure" src="https://github.com/tianhang/Maven-The-Definitive-Guide/blob/master/assets/step3.png" width="50%">
</p>

<strong>open build path -> configure build path , then remove the missing folder</strong>
<p align="left">
<img alt="structure" src="https://github.com/tianhang/Maven-The-Definitive-Guide/blob/master/assets/error1.png" width="50%">
</p>

<strong>add missing source folders , below is the complete project structure</strong>
<p align="left">
<img alt="structure" src="https://github.com/tianhang/Maven-The-Definitive-Guide/blob/master/assets/step5.png" width="50%">
</p>


<strong>check the output folder</strong>
<p align="left">
<img alt="structure" src="https://github.com/tianhang/Maven-The-Definitive-Guide/blob/master/assets/check1.png" width="50%">
</p>

<strong>check the facets to ensure it's a dynamic web project</strong>
<p align="left">
<img alt="structure" src="https://github.com/tianhang/Maven-The-Definitive-Guide/blob/master/assets/check2.png" width="50%">
</p>


<strong>remove the useless folder when deploy</strong>
<p align="left">
<img alt="structure" src="https://github.com/tianhang/Maven-The-Definitive-Guide/blob/master/assets/check3.png" width="50%">
</p>

<strong>maven update project</strong>
<p align="left">
<img alt="structure" src="https://github.com/tianhang/Maven-The-Definitive-Guide/blob/master/assets/step4.png" width="50%">
</p>
