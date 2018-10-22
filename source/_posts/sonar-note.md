---
title: sonar note
date: 2018-09-23 23:08:00
tags:
---
### sonar搭建与基本知识笔记  
学习如何改sonar-pmd插件:  
集成阿里p3c  
www.jianshu.com/p/b849175dd38b 
---
sonarqube使用maven-plugin的预设参数:  
https://docs.sonarqube.org/display/SONAR/Analysis+Parameters  
---
**maven sonar插件**  
**mvn**  
参数-D  
sonar.exclusions=`**/test/**`,`**/mock/**`
sonar.dynamicAnalysis=reuseReports  
sonar.cpd.exclusions=  
sonar.jdbc.driver=com.mysql.jdbc.Driver  
sonar.branch=  
sonar.host.username  
sonar.host.password  
sonar.host.url  
sonar.projectName  


[sonar官网地址](https://www.sonarqube.org/)