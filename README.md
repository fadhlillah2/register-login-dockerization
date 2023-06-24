# Registration-Login-Spring-Boot-Security-Thymeleaf

## Project Description

This is a demo project showcasing a simple registration and login system using Spring Boot, Thymeleaf, and Hibernate. The application uses Spring Security for authentication and authorization, and connects to a MySQL database using Spring Data JPA and Hibernate.

The project uses the following main dependencies:

- Spring Boot Starter Data JPA: Provides Spring Data JPA, Hibernate, JPA API, JPA Implementation (default is Hibernate), JDBC and other needed libraries.
- Spring Boot Starter Security: It is a powerful and customizable authentication and access-control framework. It is the de-facto standard for securing Spring-based applications.
- Spring Boot Starter Thymeleaf: It is a modern server-side Java template engine for both web and standalone environments. Thymeleaf's main goal is to bring elegant natural templates to your development workflow.
- Thymeleaf Extras Springsecurity5: A Thymeleaf integration package for Spring Security 5.
- Spring Boot Starter Web: Starter for building web, including RESTful, applications using Spring MVC. Uses Tomcat as the default embedded container.
- Spring Boot Devtools: Provides fast application restarts, LiveReload, and configurations for enhanced development experience.
- MySQL Connector Java: JDBC Type 4 driver for MySQL.
- Spring Boot Starter Test: Starter for testing Spring Boot applications with libraries including JUnit, Hamcrest and Mockito.

## Getting Started

These instructions will guide you on how to get the project up and running on your local machine.

### Prerequisites

- JDK 1.8
- Maven
- MySQL

### Installation

1. Clone the repo
```sh
git clone https://github.com/fadhlillah2/registration-login-spring-boot-security-thymeleaf.git
```
2. Navigate to project directory
```sh
cd registration-login-spring-boot-security-thymeleaf
```
3. Install Maven dependencies
```sh
mvn install
```
4. Edit the `application.properties` file with your MySQL credentials
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/mydb
spring.datasource.username=root
spring.datasource.password=yourpassword
```
5. Run the Spring Boot application
```sh
mvn spring-boot:run
```
6. Open your browser and visit `http://localhost:8080`

## Usage

After running the application, navigate to the registration page and create a new user. You can then log in with this user to access the home page.

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Your Name - your@email.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)

## Acknowledgements

* [Spring Boot](https://spring.io/projects/spring-boot)
* [Thymeleaf](https://www.thymeleaf.org/)
* [Spring Security](https://spring.io/projects/spring-security)
* [Hibernate](https://hibernate.org/)
* [MySQL](https://www.mysql.com/)

## Running Tests

The application uses Spring Boot's built-in testing capabilities to provide unit and integration tests. You can run the tests by using the following command in the project directory:

```sh
mvn test
```

## Deployment

The application can be deployed on any platform that supports Java 8. You need to first package the application into a JAR file, then you can run this JAR file on the deployment platform.

To package the application, use the following command:

```sh
mvn package
```

This will create a JAR file in the `target` directory. You can then move this JAR file to the deployment platform and run it using the following command:

```sh
java -jar target/registration-login-spring-boot-security-thymeleaf-0.0.1-SNAPSHOT.jar
```

## Built With

- [Spring Boot](https://spring.io/projects/spring-boot)
- [Thymeleaf](https://www.thymeleaf.org/)
- [Spring Security](https://spring.io/projects/spring-security)
- [Hibernate](https://hibernate.org/)
- [Maven](https://maven.apache.org/)
- [Java 8](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html)

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your_username/repo_name/tags).

## Authors

- Fadhlillah - Initial work - [fadhlillah2](https://github.com/fadhlillah2)

See also the list of [contributors](https://github.com/your_username/repo_name/contributors) who participated in this project.

## Support

If you encounter any issues or require further assistance, you can create an issue in the repository. Make sure to describe the issue and include any relevant details like error messages or screenshots to help understand the problem better.

