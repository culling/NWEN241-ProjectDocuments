# NWEN 241 - Systems Programming
https://www.victoria.ac.nz/courses/nwen/241/2019/offering?crn=18315

## Course learning objectives
Students who pass this course will be able to:
1. Use appropriate tools compiling/debugging C/C++ programs.
2. Write C programs using pointers and arrays, user-defined data types, input/output operations, bit-level operations, and user-defined and library routines.
3. Understand the differences between C and C++, and write C++ programs using stream input/output, classes, vectors and templates.
4. Use or understand the main techniques of dynamic memory management in C and C++.
5. Structure larger programs in multiple files.
6. Understand the differences between application software and system software.

## Note
This document covers projects and assignments made while studying NWEN241 - Systems Programming. 

The source files are unable to be published to the public to help ensure academic integrity.

# Assignments

## Text Editor
This assignment required several text editor functions to be implemented using C and C++ for different sections
The functions implemented were
+ Insert
+ Delete 
+ Replace
+ View with word wrapping
+ View with justification

## On Strings and Pointers
This assignment required a number of text editor functions to be written in C and C++
The functions were
+ Line count, based on the number of characters in a buffer for a given screen width
+ Multiple search, to search for all instances of a string within a buffer, returning the locations the string can be found in the buffer as an array
+ Word count
+ Multiple search case insensitive 


## Database Management System - Album
This assignment was to create a database for albums 
The required functions were
+ Add records
+ View records
+ Remove records by ID
+ Manage memory in sets of 5 Albums using alloc, calloc, realloc and free avoiding memory leaks


## Database Management System - Movies
This assignment was to create a database for movies, reading from a file and using abstract classes, vectors and linked lists 
The required functions were
+ Import movies from a CSV file in a defined format
+ Export movies to a CSV file in a defined format
+ Add record
+ View record
+ Remove record

## Database Management System - Movie Server
This assignment was to create a network connected database for movies, building on the previous assignment 
The required functions were
+ Import movies from a CSV file in a defined format
+ Accept network connections on port 12345
+ Hold an interactive session with multiple users at the same time (using fork)
+ Allow users to disconnect with custom commands
+ Return information to the user based on thier commands (Get all movies, get one movie, get an error message or disconnect from server)
