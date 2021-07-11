# VideoGameDB
Video Game Database application with API endpoints that support **JSON** and **XML**

This application was developed to support my Udemy courses: 

- [REST Assured Fundamentals](https://www.udemy.com/course/rest-assured-fundamentals/)
- [Gatling Fundamentals for Stress, Load & Performance Testing](https://www.udemy.com/course/gatling-fundamentals/)

# Usage
To run the application from the command line, you have two options:

- **Gradle** - `./gradlew bootRun`
- **Maven**  - `mvn spring-boot:run`

When the application is running, open a browser and go to [http://localhost:8080/swagger-ui/index.html#/](http://localhost:8080/swagger-ui/index.html#/) to explore the API endpoints



# APM 
`
-javaagent:C:\Kuae-WorkSpace\Leaning\VideoGameDB-master\apm-docker\elastic-apm-agent-1.24.0.jar -Delastic.apm.service_name=video-game-db-app -Delastic.apm.server_urls=http://localhost:8200 -Delastic.apm.application_packages=com.techietester

`