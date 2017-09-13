# Development of Real-Time Systems – Assignment 1

## Overview

In the first assignment, you will demonstrate your newly learned skill in defining real-time tasks and make a simple schedule. You are going to familiarize yourself with the [FreeRTOS API](http://www.freertos.org/a00106.html) and handle simple task control. The point of this exercise is to give you practical knowledge in setting up a real-time operating system and defining tasks for execution.

After completing this assignment, you will be able to:

- Set-up and compile FreeRTOS
- Create tasks in FreeRTOS
- Practically demonstrate scheduling of several tasks in FreeRTOS

## Pre-requisite

It is recommended to use the free software Visual Studio Express for this assignment. The FreeRTOS system you are about to setup will execute in Visual Studio Express, and output from the system is available from its console. More help Here about setting up Visual Studio Express with the FreeRTOS project.

It is also possible to use the free software Eclipse for this assignment. Notes on setting up Eclipse with the FreeRTOS project Here.

## Programming assignment

- Download the FreeRTOS project Here

- Import the project into Visual Studio Express 2015. More information from our Documentation.

- In Visual Studio click the “build” menu and “Build solution”. This will compile the project. More information from our Documentation.

- Now run the project. More information from our Documentation

- Familiarize yourself with the FreeRTOS API and locate to the main() function in the FreeRTOS project in Visual Studio Express

- Here, create two tasks with the following parameters seen in the code window (hint look at xTaskCreate() in the API)

                Task1 name="Task1"Task2 name="Task2"
                Task1 stack size = 1000
                Task2 stack size = 100
                Task1 priority = 3
                Task2 priority = 1

- Create task functions containing the following functionality

Task1 should print out "This is task 1" every 100 milliseconds (hint use fflush(stdout) after printf())

Task2 should print out "This is task 2" every 500 milliseconds

- Provide a screenshot of the execution in a report and the source code of your solution.

## Review criteria

Everyone enrolled in this course must review at least three other submissions to ensure everyone receives a grade.