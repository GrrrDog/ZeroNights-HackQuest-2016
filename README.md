There are two web tasks from ZeroNights HackQuest 2016 http://hackquest.zeronights.org/.

They consist of some unusual, but real vunl types.

Also they demostrate a part of research about Spring MVC ()

All sources is in "src" folder.

# Justice League // Bad Assistant
It contains next vuln types:
- Session Puzzling (Session Variable Overloading)
- Autobinding (Mass Assignment)
- Insecure JSON deserialization using XStream lib

Installation process:
- just deploy justiceleague.war and justiceleaguedb.war files to any Tomcat (or something similiar)

# The First School of Bulemia - Edik // I wanna be better
It contains next vuln types:
- Autobinding (Mass Assignment)
- Expression Language injection
- Sensetive information disclosure (OSINT related part of task)

Installation process:
- install jdk1.6
- install Tomcat 6
- deploy edik.war file to the Tomcat
