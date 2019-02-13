---
layout: default
---

[](Text can be **bold**, _italic_, or ~~strikethrough~~.)

[]([Link to another page](./another-page.html))

## Products
To publish Maven artifacts to S3 a build extension must be defined in a project's pom.xml. The latest version of the wagon can be found on the aws-maven page in Maven    Central.

Support for cross account S3 access using AssumeRole and AWS_PROFILE valiable.

- [aws-maven](https://github.com/kuraun/aws-maven)
  - Status: In development

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
