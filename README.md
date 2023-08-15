# EduFlow-Course-Dependency-Tracker


This program calculates the topological ordering of a course dependency graph and detects cycles, if any.


## Introduction

This C++ program helps you manage course dependencies and provides insights into the ordering of courses based on their prerequisites. It uses depth-first search to traverse the graph of courses and determine their dependencies and ordering.


### Prerequisites

- C++ compiler (C++11 or later)
- Standard C++ library
- Input: Course names, number of pre-requisites, and their names

##Usage

    1.Run the executable: ./course_dependency_graph
    2.Enter the number of courses and their details as prompted.
    3.The program will display the topological ordering of courses or indicate if a cycle is detected.

##Features
    1. Input the number of courses and their prerequisites.
    2. Detects cycles in the course dependency graph.
    3. Calculates the topological ordering of courses.
    4. Provides a visual representation of the course ordering.
