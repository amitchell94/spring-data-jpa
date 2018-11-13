# Spring Data JPA
A skeleton project to demo using Spring Data JPA to store and retrieve data in a relational database.

The application stores Customer POJOs in a memory-based h2 database.

## Getting Started

You can get started by cloning the project to your local machine:
```
$ git clone https://github.com/amitchell94/spring-data-jpa.git
```

### Prerequisites

In order to execute this program you will need have the Java JDK installed.

## Running the Application

The application can be run by packaging everything in a single, executable JAR file, driven by a Java `main()` method. 

After running the application, you should see something like this:
```
== Customers found with findAll():
Customer[id=1, firstName='Jack', lastName='Bauer']
Customer[id=2, firstName='Chloe', lastName='O'Brian']
Customer[id=3, firstName='Kim', lastName='Bauer']
Customer[id=4, firstName='David', lastName='Palmer']
Customer[id=5, firstName='Michelle', lastName='Dessler']

== Customer found with findOne(1L):
Customer[id=1, firstName='Jack', lastName='Bauer']

== Customer found with findByLastName('Bauer'):
Customer[id=1, firstName='Jack', lastName='Bauer']
Customer[id=3, firstName='Kim', lastName='Bauer']
```

## Built With

* [Gradle](https://gradle.com/) - Dependency Management

## Authors

* **Andy Mitchell** - *Initial work* - [GitHub](https://github.com/amitchell94)

## Acknowledgments

* Created using the [Spring Accessing Data with JPA Tutorial](https://spring.io/guides/gs/accessing-data-jpa/) 
