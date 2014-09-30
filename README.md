#daniel-examples

Create a command prompt, usuable for small examples and eventually also text-based adventure games.

The code should be cleanly split up between header files and code files.

Globals should be avoided if possible, but aren't forbidden: if they're the best tool for a job, use them.

Every function should have a comment describing the function at it's beginning.

Variables and functions should be named in a sensible way, so that the names descrive the function, while not getting excessive long.

## First assignment

Create a basic command prompt. It mus show a ">" when it's ready to accept input, and when you finished typing your command (signified by pressing the ENTER key), a function should should be called. the function should have 2 parameters: the commadn itself, and an array of all the parameters for the command (everything after the command, sperataed by "SPACE"). Once the function is done, the command prompt should be ready to accept further input.

## Second assignment

Create some way to store multiple commands, and access them by name. Every command should be a closed entity, have a function creating it, and a second function executing it, and a third function destroying it.

## Third assignment

Create a command, called "exit", that quits the program

## Fourth assignment

Create a command, called "echo", that will just output the parameters

## Fifth assignment

Create a few commands:

	- "sum", outputs the sum of two parameters if they're numbers, else shows an error message.
	- "sub", outputs the difference between two parameters if they're numbers, else shows an error message.
	- "fact", outputs the factorial of a parameter if it's a number, else shows an error message.
	- "isPrime", outputs "true" if the number is a prime number, and "false" if it isn't.