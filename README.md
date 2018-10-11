# Basic Assignment

#### Objective:
Objective of this level, is to ensure that we can deliver a quality solution using a programming language following standard practices.

#### Tools & Technology :

##### Language :
* Java
* C#

##### Source Code Management :
* git (Java & C#)

##### Build Tool :
* maven (Java)
* dotnet CLI (C#)

##### Unit Test:
* JUnit (Java)
* xUnit (C#)

#### Commonly Done Mistakes

* Don't distribute your code as files/folders attaching to an email, rather put your source code on any cloud based git server (like github) and share the source code as a link to your respository.
* Don't keep the files/folders generated by IDE or generated during build process in git, rather ignore them using .gitignore. Only those files/folders should be kept in repository which are necessary to build the code after a fresh checkout.
* Give a proper name to the project and must use a relevant namespace for your project following standard naming convention
* Don't all logic inside main method, rather keep main method in a separate class at the root package level and should just instantiate a class and call one of its method
* Don't keep all your logic in one class/method , rather design it with following OOPS concepts and Single Responsibility Principles.
* Name all packages, classes, methods and variables following standard naming convention suggested by the language community and must be consistent.
* Each public method in a class containing logic should have corresponding unit tests to cover all scenarios.
* Possible exception scenarios must be analyzed and handled appropriately and must have unit tests for them.
* One should be able to build and run the application using the build tool/SDK from a command prompt, without using any IDE. Example: Build Tool -> maven, dotnet CLI, SDK -> JDK, .net Core SDK
* Project structure must follow standard build tool suggested structure (maven/dotnet CLI)and should be made clean and simple as much as you can.
* Must provide a README.md file formatted with github format, at the root of the project documenting how to build and run the project
* README.md file must mention the tools/softwares need to build and run the project with version information
* Proper access specifier must be mentioned, like member variables must be private, methods not invoked must be private/protected
* Methods should not lengthy, rather split it into smaller methods appropriately

Reference :

Best Practices:
https://www.khanacademy.org/computing/computer-programming/programming/writing-clean-code/e/quiz--clean-code
https://www.codingdojo.com/blog/clean-code-techniques/
http://www.garshol.priv.no/blog/105.html
https://www.git-tower.com/learn/git/ebook/en/command-line/appendix/best-practices
https://www.codeproject.com/Articles/768052/Golden-Rules-Of-Good-OOP

Source Code Management :
git : https://www.atlassian.com/git/tutorials

Build Tool :
dotnet CLI(C#) : http://www.tutorialsteacher.com/core/net-core-command-line-interface
maven   (Java) : https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html

Unit Test :
xUnit(C#)   : https://docs.microsoft.com/en-us/dotnet/core/testing/unit-testing-with-dotnet-test
JUnit(Java) : https://dzone.com/articles/junit-testing-part-i-setup-with-simple-example

