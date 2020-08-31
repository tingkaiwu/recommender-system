## Recommender System

<p>
  <img src="https://github.com/tingkaiwu/tingkaiwu/blob/master/recommender.gif">
</p>

## Overview

Recommender System is an interactive web application for job seekers to search and apply openings. 
The purpose of this project was to learn how to use J2EE to develop RESTful API. 
In addition, I also implemented a content-based  job recommender system to recommend jobs to users. 
I built RESTful APIs using Java Servlets to retrieve job description using GitHub API and store data in MySQL, 
and I use the MonkeyLearn API to extract the keywords of the job description. in order to build the Content-based algorithm.

## Requirement
- Java 8 or higher
- Eclipse for Enterprise Java Developers
- Apache Tomcat
- Register Monkey Learn API
- AWS Account

## Installation
1. Set Tomcat to Eclipse
2. Clone Recommender System from GitHub
3. Use Maven install the dependences
```
git clone git@github.com:tingkaiwu/recommender-system.git
cd recommender-system
mvn install
```
4. Start your Tomcat
5. http://localhost:8080/jupiter/

## Skills

- Java
- JavaScript
- Java Servlet
- HTML
- CSS
- AWS RDS
- AWS EC2

<p>
  <img width="500" align='right' src="https://github.com/tingkaiwu/recommender-system/blob/master/readme.image/recommender.png?raw=true">
</p>

<br/>

## Structure

I used Tomcat as HTTP Server in this project, and used Java Servlet to build six API endpoints to handle HTTP request and response, including search, recommendation, history, login, logout and register. 

In addition, I built two clients to operate GitHub API & Monkey Learn API, and access MySQL database deployed on AWS.

<br/>

## Program Flow
<p>
  <img width="800" src="https://github.com/tingkaiwu/recommender-system/blob/master/readme.image/recommender_functions.png">
</p>

## Database Structure
<p>
  <img width="800" src="https://github.com/tingkaiwu/recommender-system/blob/master/readme.image/recommender_database.png">
</p>

<!--
<p align=center>
  <img src="https://github.com/tingkaiwu/recommender-system/blob/master/readme.image/recommender_auth.png">
</p>

<p align=center>
  <img src="https://github.com/tingkaiwu/recommender-system/blob/master/readme.image/recommender_method.png">
</p>

<p align=center>
  <img src="https://github.com/tingkaiwu/recommender-system/blob/master/readme.image/recommender_recommend_structure.png">
</p>
-->

## API Endpoint
- /jupiter

- /jupiter/search

- /jupiter/recommendation

- /jupiter/history

- /jupiter/login

- /jupiter/logout

- /jupiter/register

<!--
名字
簡介/目的
功能
安裝配置
快速教程
API 文档
-->
