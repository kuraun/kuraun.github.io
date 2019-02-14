---
layout: default
---

[](Text can be **bold**, _italic_, or ~~strikethrough~~.)

[]([Link to another page](./another-page.html))

## Products
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

**Welcome pull requests.**

## Contact Us
Kuraun Developers: kuraun.dev@gmail.com
