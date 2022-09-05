# Flight-Scheduling-CSP-

Constraint Satisfaction Problem:

Problem statement: Airport Flight Scheduler

In an airport management portal, an AI agent is built to prepare an auto schedule for the below Jet-Airways flights take off time among the four available slots: 06:00AM IST, 07:00AM IST, 08:00AM IST, 09:00AM IST.
Flight numbers: J-9W4569, J-9W377, J-9W4331, J-9W601, J-9W665.
Some of the operational inter-flight implicit binary constraints are given below: J-9W4331 and J-9W4569 can start at the same time.

J-9W4331 and J-9W601 can start at the same time.
J-9W4331 and J-9W377 can start at the same time.
J-9W4331 should start any time after the takeoff of J-9W665
J-9W4331 should take off exactly one hour after the J-9W601
J-9W665 should start any time before the takeoff of J-9W601
J-9W4569 should start any time after the takeoff of J-9W601
J-9W4569 may take off at the same time or any time before flight J-9W377

In case of any multiple constraints for same set of variables, all the constraints must be satisfied. 
If there are any contradictory constraints, state the same explicitly in the answer and choose one with your justification.

a. Draw the constraint satisfaction graph to represent this problem.
b. Implement Python code for the design under part a, using DFS with
Backtracking and heuristics including MCV and MRV.
c. Print the Flight wise scheduling details.

