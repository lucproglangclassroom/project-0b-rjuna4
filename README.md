[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=11701439&assignment_repo_type=AssignmentRepo)
# Overview

Very simple example including an App and a few tests 
(illustrating different testing styles).

# Running the app

    sbt run

# Running the tests

    sbt test

# Determining test coverage

    sbt coverage test
    sbt coverageReport
	
Now open this file in a web browser:

    target/scala-2.13/scoverage-report/index.html
    
# Running a Scala console

This allows you to explore the functionality of the classes in this
project in a Scala REPL while letting sbt set the classpath for you.

    sbt console
