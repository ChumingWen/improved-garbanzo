# X-Team 5 Project Proposal: Where To Party?

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

Suppose that there are several friends trying to shrow a party. Each of them lives at a different location that is capable of hosting one. The program helps calculate the optimal venue of the party so that each of the friends travels the least distance.

Our program will utilize a graph to store uses' location and calculate distances from each other. May consider incorporating Google Maps API for practicality of the program.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)
Where To Party?


2. Output: Describe the output your program will produce.  Include and example format of the output produced.
The program will return the ideal location of the party.

Sample output:

The party will be hosted at Jerry's house:
777 University Ave
Madison, WI 53715

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.
Each user will enter his/her name and address(for primary versions we will be using made up coordiantes to represent locations, ideally addresses will be stored in accordance with the Google Map API). 

Sample input:
(String) Name: Jerry
(Coordiante) Location: (100.23, 653.94)
(String) Address: 777 University Ave, Madison, WI 53715

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.
The program will have a GUI for user interactions. The users will search and save their locations on a map and there will be a "party" button for generating results.

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.
class User: 
    Attributes: name, location, adjacency list of other users
    Functions: accessors and mutators

class Graph:
    Attributes: list of users
    Functions: calculate distance for each user


Name each interface or class and briefly describe its function or purpose.
see 4 and 5.

## Edit and Submit this file and any figures referenced by this document.

