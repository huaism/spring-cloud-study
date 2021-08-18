# spring-cloud-study
测试spring-cloud

1. Nacos Server Startup
  For details about how to download and start Nacos, refer to the Nacos Website.
After Nacos Server starts, go to http://ip:8848 to view the console (default account name/password is nacos/nacos):

2.sentinel Server Startup
  You can download the latest dashboard JAR file from the Release Page.
You can also get the latest source code to build your own Sentinel dashboard：
Download the Dashboard project.
Run the following command to package the code into a FatJar: mvn clean package
Start the Dashboard
Sentinel dashboard is a standard SpringBoot application, and you can run the JAR file in the Spring Boot mode.
java -Dserver.port=8080 -Dcsp.sentinel.dashboard.server=localhost:8080 -Dproject.name=sentinel-dashboard -jar sentinel-dashboard.jar
