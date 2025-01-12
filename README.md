Overview
This is a simple Spring Boot application showcasing the basics of web development with Spring. It includes a controller for serving static and dynamic content using Thymeleaf.

To get access use:
Default: http://localhost:8080/
Greeting: http://localhost:8080/greeting?name=YourName

How it works
The HelloController handles two routes:
/ – Returns a plain text response.
/greeting – Passes the name parameter to a Thymeleaf template (greeting.html).
The Thymeleaf template dynamically renders the greeting and includes a placeholder image.

Technologies
Spring Boot
Thymeleaf
Maven

Additional resources
Vistula photo: https://www.facebook.com/uczelniavistula/
