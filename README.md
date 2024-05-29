# Introduction to JUnit 5 with Maven

All source code examples in the repository are for my [Online Course - Testing Spring Beginner to Guru](https://www.udemy.com/testing-spring-boot-beginner-to-guru/?couponCode=GITHUB_REPO)

This source code repository contains JUnit 5 test examples with Maven.

## Setup
### Requirements
* Should use Java 11 or higher. Previous versions of Java are un-tested.
* Use Maven 3.5.2 or higher

## Support
For questions and help:
* Please post in course
* Or post in the Slack Community exclusive to the course.

GitHub Issues will not be addressed.



## Notes

### JUnit Annotations

| Annotation         | Description                                                 |
|--------------------|-------------------------------------------------------------|
| @Test              | Marks a method as a test method                             |
| @ParameterizedTest | Marks method as a parameterized test                        |
| @RepeatedTest      | Repeat test N times                                         |
| @TestFactory       | Test Factory method for dynamic tests                       |
| @TestInstance      | Used to configure test instance lifecycle                   |
| @TestTemplate      | Creates a template to be used by multiple test cases        |
| @DisplayName       | Human friendly name for test                                |
| @BeforeEach        | Method to run before each test case                         |
| @AfterEach         | Method to run after each test case                          |
| @BeforeAll         | Static method to run before all test cases in current class |
| @AfterAll          | Static method to run after all test cases in current class  |
| @Nested            | Creates a nested test class                                 |
| @Tag               | Declare 'tags' for filtering tests                          |
| @Disabled          | Disable test or test class                                  |
| @ExtendWith        | Used to register extensions                                 |

### JUnit Test Lifecycle

@BeforeAll -> @BeforeEach -> @Test -> @AfterEach -> @AfterAll
