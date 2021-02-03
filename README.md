[![BCH compliance](https://bettercodehub.com/edge/badge/tommens/calculator-cucumber?branch=master)](https://bettercodehub.com/)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/6856a0f94d25446ca346cbc15a701d43)](https://www.codacy.com/gh/tommens/calculator-cucumber/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=tommens/calculator-cucumber&amp;utm_campaign=Badge_Grade)

# Calculating arithmetic expressions

## About

This repository contains Java 11 code for computing arithmetic expressions. It is deliberately incomplete as it serves to be the basis of all kinds of extensions, such as a more sophisticated Calculator application. The code was written to be used for educational purposes at the University of Mons, Belgium.


### Unit testing

*  All tests can be found in the src\test directory. They serve as executable documentation of the source code.
*  The source code is accompanied by a set of JUnit 5 unit tests. These tests can be written and run in the usual way. If you are not familiar with unit testing or JUnit 5, please refer to https://junit.org/junit5/.

### Prerequisites

*  You will need to have a running version of Java 11 on your machine in order to be able to compile and execute this code.
*  You will also need to have a running version of Gradle, since this project
   is accompanied by a build.gradle file so that it can be installed, compiled,
   tested and run using Gradle. You need at least version 6.4.

### Installation and testing instructions

*  You can compile the source code using "gradle build"
*  Once the code is compiled, you can execute the main class of the Java code
   using "gradle run" 
*  The tests are executable with Gradle using "gradle test"
*  Finally, it is possible to generate an executable .jar file using "gradle
   jar". The file will be generated in the "build/libs" directory.

## Built With

*  [Gradle](https://gradle.org) - an open source build automation and dependency management tool
*  [JUnit5](https://junit.org/junit5/) - a unit testing framework for Java

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/tommens/calculator-cucumber/tags). 

## Authors

*  Tom Mens
*  Gauvain Devillez

## Licence

This code is licensed as CC BY-SA 4.0 (Creative Commons Attribution-ShareAlike 4.0 International)
https://creativecommons.org/licenses/by-sa/4.0/

## Acknowledgments

* Software Engineering Lab, Faculty of Sciences, University of Mons, Belgium.
