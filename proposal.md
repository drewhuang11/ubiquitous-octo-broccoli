# X-Team 21 Project Proposal Expenditure Tracker

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Briefly describe a problem that your team would like to solve.  
Describe at a high level a program that could solve that problem.

A problem we would to solve is the fastest route to a place in Madison considering distance and bus schedules. 
The program would fundamentally build off a directed graph that has weights and considers time it takes to walk and also bus schedules to find the fastest way to get a location. 

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

UW-Madison Campus Navigator

2. Output: Describe the output your program will produce.  Include an example format of the output produced.

The output would be the ideal route, transportation method, and time needed to get to a location. 

TIME | BUS NUMBER | BUS STOP START | BUS STOP EXIT | WALKING DISTANCE
   8 |         80 |      Lake/Park | Regent/Spring |           0.5 mi

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

The data needed is movement speed, start location, destination, and starting time.

SPEED | START LOCATION| END LOCATION | START TIME
5 mph |   Bascom Hall |    Steenbock |    9:00 AM

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

The user interface would be a text menu that would take the inputs from the user and then just display the ideal route.

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

Name each interface or class and briefly describe its function or purpose.

MapGraph: Graph to hold the nodes
LocationNode: Each individual location on campus
RouteEdge: Edges between LocationNodes that have the weighted edge values for the route distances
MenuUI: Displays User Interface, collects inputs and displays output
Main: Runs the program

## Edit and Submit this file and any figures referenced by this document.

