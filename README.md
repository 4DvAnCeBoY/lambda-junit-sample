## Java-Junit-Selenium

### Environment Setup

1. Global Dependencies
    * Install [Maven](https://maven.apache.org/install.html)
2. Sauce Labs Credentials
    * update username and accesskey in JunitTodo.java.
3. Project Dependencies
    * Check that packages are available
    ```
    $ cd Java-Junit-Selenium
    $ mvn test-compile
    ```
    * You may also want to run the command below to check for outdated dependencies. Please be sure to verify and review updates before editing your pom.xml file as they may not be compatible with your code.
    ```
    $ mvn versions:display-dependency-updates
    ```
    
### Running Tests

#####Testing in Parallel:
```
$ mvn test
```

