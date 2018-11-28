# mySpringBoot
spring boot testing project for personal use

# Personal memo (how I set up)
basically according to http://spring.io/guides/gs/maven/#scratch

(Download Maven, create src/main/java/hello etc...)

# Import to eclipse
make the project outside eclipse-workspace
Run `mvn eclipse:clean eclipse:eclipse` in cmd.

After BUILD SUCCESS, go to eclipse, import > Maven > Exsisting Maven Project.

This will automatically import <dependencies> written in pom.xml into referenced libraries.

e.g. joda-time-2.9.2.jar

# Problems encountered (For windows only?)

No compiler is provided in this environment. Perhaps you are running on a JRE rather than a JDK?

Simply set Environment variable to JAVA_HOME C:\Program Files\Java\jdk1.8.0_191\jre

Use jre inside jdk.

DO NOT use C:\Program Files\Java\jre1.8.0_191, this will cause the same error.
