# FirstProjectRepo
Cucumber Automation Project Framework
Cucumber-JVM is a pure Java implementation of Cucumber that supports the most popular programming languages for the JVM.

Introduction to BDD and Gherkin language

This test automation framework, which provides structured and standard way of creating automated test scripts for GUI.

This is a reusable automation framework that blends together Selenium WebDriver and Cucumber JVM (incorporating Gherkin and the BDD 'Given, When Then' testing construct)

The framework incorporates design principle of BDD (Behavior driven development) which promotes writing acceptance tests by describing Behavior of application under test in simple English language from the perspective of its stakeholders. Having test written in Natural language helps the Project Team (Product Owners, Business Analysts, Development and QA team) to understand and track the requirements

Further to understand more on Gherkin language please refer to this [ https://github.com/cucumber/cucumber/wiki/Given-When-Then ] or [ https://github.com/cucumber/cucumber/wiki/Feature-Introduction ]

Supports Custom Page Object model and Page Factory which represents the screens of AUT as a series of objects and encapsulates the fields represented by a page which ultimately avoids duplication and improves code maintainability and readability.

Installation

Install Java [http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html]
Download Maven [https://maven.apache.org/download.cgi] [Windows]
sudo apt-get install maven (To download's maven) [ for LINUX]
Configuration

Set Environmental variables

Windows

Add java path to System variables as JAVA_HOME=path/of/your/java/
Add path to system variable as MAVEN_HOME=path/of/your/Maven/
Add both java and maven path until bin folder to PATH of the system

LINUX

Java setUp

*whereis java 
*export JAVA_HOME=/path/to/jdk/folder
*export PATH=$PATH:$JAVA_HOME/bin
Maven setUp

*whereis maven 
*export M2_HOME=/path/to/maven/folder
*export PATH=$PATH:$M2_HOME/bin
Quick check to see installation is done

Run in command line

     mvn -version 

     Output as follow 
     Maven home: C:\Users\xxxxx\Downloads\apache-maven-3.2.2\bin\..
     Java version: 1.7.0_60, vendor: Oracle Corporation
     Java home: C:\Program Files\Java\jdk1.7.0_60\jre
How to Run

From Eclipse

Open Wrapper package and run RunCukesTest with JUnit
From Command Line

run mvn test
Tools

Eclipse Version: 4+
Java 7+
Selenium WebDriver
JUnit
Log4j
Maven
