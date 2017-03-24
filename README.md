There are two web tasks from ZeroNights HackQuest 2016 http://hackquest.zeronights.org/.

They consist of some unusual, but real vuln types.

Also they demostrate a part of research about Spring MVC - http://agrrrdog.blogspot.com/2017/03/autobinding-vulns-and-spring-mvc.html

All sources are in "src" folder.

# Justice League 
Task name -  Bad Assistant

It contains vuln types:
- Session Puzzling (Session Variable Overloading)
- Autobinding (Mass Assignment)
- Insecure JSON deserialization using XStream lib

Installation process:
- just deploy justiceleague.war and justiceleaguedb.war files to any Tomcat (or something similiar)

# The First School of Bulemia - Edik
Task name -  I wanna be better

It contains vuln types:
- Autobinding (Mass Assignment)
- Expression Language injection
- Sensetive information disclosure (OSINT related part of task)

Installation process:
- install jdk1.6
- install Tomcat 6
- deploy edik.war file to the Tomcat
