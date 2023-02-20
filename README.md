# :movie_camera: cinema-app :film_strip:

Project description:

    Cinema-app, a web application which accepts http requests, that allows CRUD operations, 
    supports registration and authentication. Each registered user has a role that 
    limits, requests that can be processed. 

## Features:
- Separation of roles for user and administrator;
- User can: 
  - get data about: cinema halls, movies, available sessions and to his own client data;
  - create order and pay for it by users Shopping card;
- Administrator can:
  - add new: cinema halls, movies and movie sessions;
  - delete movie sessions by id;
  - get data about user by his email;
- Unregistered users have access to only two pages:/login /register;
- Some user data, such as the password, is encrypted; 
That protects personal data even when the database is accessed for intruders.

## Tools and Technology:
- [Tomcat](https://tomcat.apache.org) - is an open source implementation of the Jakarta Servlet,
  Jakarta Server Pages, Jakarta Expression Language, Jakarta WebSocket,
  Jakarta Annotations and Jakarta Authentication specifications.
  These specifications are part of the Jakarta EE platform.
- [MySQL](https://dev.mysql.com) - is free and open-source software under the terms of the GNU General Public License,
  and is also available under a variety of proprietary licenses.
- [Apache Maven](https://maven.apache.org) - is a software project management and comprehension tool.
  Based on the concept of a project object model (POM), Maven can manage a project's build,
  reporting and documentation from a central piece of information;
- [Spring](https://www.javatpoint.com/spring-tutorial) - is a lightweight framework. 
  It can be thought of as a framework of frameworks because it provides support to various 
  frameworks such as Struts, Hibernate, Tapestry, EJB, JSF, etc. The framework, in broader 
  sense, can be defined as a structure where we find solution of the various technical problems.
- [Validation](https://www.baeldung.com/spring-boot-bean-validation) - When it comes to validating user input, Spring Boot provides strong support for this common, 
  yet critical, task straight out of the box. Although Spring Boot supports seamless integration with custom validators, 
  the de-facto standard for performing validation is Hibernate Validator, the Bean Validation framework's reference implementation.
- [Spring Security](https://docs.spring.io/spring-security/reference/index.html) -  is a framework that provides authentication, 
  authorization, and protection against common attacks. With first class support for securing both imperative and reactive applications, 
  it is the de-facto standard for securing Spring-based applications.

## Instructions:
- This project requires Tomcat 9.0.5 or newer version and MySQL;
- To connect to a database in file src/main/resources/db.properties
  need to be changed parameters: URL, USERNAME, PASSWORD and JDBC_DRIVER;
- To configure Tomcat Server in the Deployment section in the Application context line, you need to specify only '/';
