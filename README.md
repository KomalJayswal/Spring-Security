# Spring Security

## Problem Statement

Create a fresh Spring Boot application and add Spring Security with customized username and password

## Getting Started with Customized User Name and Password

### <u>Add Customized user name and password </u>

* You can customize username and password by adding it in your application.properties file. 
```bash
  spring.security.user.name=<YourUsername>
  spring.security.user.password=<YourPassword>
```
* Now, do `mvn clean install`, and hit the root URL : `http://localhost:8080/hello` in your browser after running application. You will see there is a sign-in form now. This sign in form also do login validations.

* Enter is the configured customized user ID and password.

**Congratulations! You have secured you springboot application with customized credentials.**

## References

[This Project is Well explained by Java Brains](https://www.youtube.com/watch?v=PhG5p_yv0zs&list=PLqq-6Pq4lTTYTEooakHchTGglSvkZAjnE&index=3)
