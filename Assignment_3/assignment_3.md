## Overview

In this assignment we will focus a bit more on the theoretical side. We will have a look at verifying real-time system by using the cyclic structured construct handled in the course and a simulation environment to automatically schedule a full timeline. The main purpose of the assignment is to expose the student to several ways of planning and verifying a real-time system in practice.

## Pre-requisite

- A PC capable of running python programs
- Pen and paper

After completing this assignment, you will be able to:

- Optimize cyclic structured scheduler by finding the largest frame size
- Use SimSo to simulate a set of tasks
- Verify a set of tasks with SimSo
- Determine the total utilization of a set of tasks

## Theory assignment

The following part of assignment is a purely theoretical task that requires no additional tools. The task is to find the largest possible frame size for the cyclic structured scheduler by following requirements 1,2 and 3 for finding the largest frame size. The following three task sets should be used:

> T1(15, 1, 14) T2(20, 2, 26) T3(22, 3)

> T1(4, 1) T2(5, 2, 7) T3(20, 5)

> T1(5, 0.1) T2(7, 1) T3(12, 6) T4(45, 9)

#### Provide a written report which should contain:

- Calculations for each step for finding the frame size for each task set
- Resulting frame size for each task set
- Simulation assignment

#### The assignment is to use a real-time simulator to verify feasibility of a set of tasks

- Download the SimSo scheduler [Here](http://projects.laas.fr/simso/)
- The example has been run under Windows 7 but other platforms are also supported by the scheduler
- Install SimSo and familiarize yourself with the tool. More information is found in This document
- Input the tasks T1(2, 0.5), T2(3, 1.2), T3(6, 0.5) and the RM scheduler into the SimSo simulator
- Use SimSo to schedule the task set

#### Provide a report answering the following questions:

- What is the utilization factor of the system and what is the value for Urm(3)
- What is the minimum/maximum/average response time of all tasks?
- Is any task missing the deadline? Which task? Where?
- If a deadline is missed, could it be avoided by changing the scheduler?
- Input the tasks T1(2, 0.5, 1.9) T2(5, 2) T3(1, 0.1, 0.5) T4(10, 5, 20) and the EDF scheduler into the SimSo simulator
- Use SimSo to schedule the task set
