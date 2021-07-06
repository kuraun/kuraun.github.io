---
layout: default
---

[](Text can be **bold**, _italic_, or ~~strikethrough~~.)

[]([Link to another page](./another-page.html))

## Products
1.
To publish Maven artifacts to S3 a build extension must be defined in a project's pom.xml. The latest version of the wagon can be found on the aws-maven page in Maven    Central.


- [aws-maven](https://github.com/kuraun/aws-maven)
  - Status: Maven Central Released.(Now Available)
  - Features
    - [x] Support [AWS SDK for Java 2.0.](https://github.com/aws/aws-sdk-java-v2)
    - [x] Support `AWS_PROFILE` an environment variable.
    - [ ] Support for cross account S3 access using AssumeRole and AWS_PROFILE variable.

```xml
 <!-- add build extension -->
  <extensions>
    <extension>
      <groupId>io.github.kuraun</groupId>
      <artifactId>aws-maven</artifactId>
      <version>7.0.0.RELEASE</version>
    </extension>
  </extensions>
</build>
```
---
2.
The AWS Secrets Manager JDBC Library enables Java developers to easily connect to SQL databases using secrets stored in AWS Secrets Manager.


- [aws-secretsmanager-jdbc](https://github.com/kuraun/aws-secretsmanager-jdbc)
  - Status: Scheduled to be released to Maven Central (Not Available)
  - Features
    - [x] Support for changing database drivers default secrets cache item TTL using environment variables or system properties.

```xml
<dependency>
    <groupId>io.github.kuraun</groupId>
    <artifactId>aws-secretsmanager-jdbc</artifactId>
    <version>1.0.8-M1</version>
</dependency>
```


**Welcome pull requests.**

## Contact Us
Kuraun Developers: kuraun.dev@gmail.com
