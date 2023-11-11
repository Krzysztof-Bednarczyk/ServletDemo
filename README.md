# ServletDemo
Spring training repo

This demo servlet app renders a "Hello World!" to Your screen.

## Steps to run app

1. Use maven command `mvn -Dmaven.tomcat.port=8189 tomcat7:run` - You can choose Your port running the command. It's 8080 by default.
   The app is using the mvn Tomcat 7 plugin
   Make sure the path and context file are set in the plugin properly.
   ```
   <path>/DemoServlet</path>
   <contextFile>src/main/webapp/WEB-INF/web.xml</contextFile>
   ```
2. The app should run on <http://localhost:8189/DemoServlet/>
