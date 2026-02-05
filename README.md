### Goals
* Write your own data structure definition.
* Use a collection (array/list) of structures.
* Apply collection processing algorithms to the data.

### Experimental Protocol (Single-Blind)
**This assignment is part of a single-blind experiment.** You must choose ONE of the paths below to complete the work.

### Submission Instructions
**Submit Source Code:** Message me directly via Discord (aarns) with your source code file attached.
    * *Reminder:* Do **not** include comments in the file revealing if you used AI or not.

**Important:** To ensure unbiased grading, **do NOT** indicate which method you chose in your source code, code comments, or submission text. You will report your method in a separate form (linked below) after submitting.

**Group A: Traditional Approach**
* Write the code entirely by yourself.
* Focus on manual implementation and logic building without external generation tools.

**Group B: AI-Assisted Approach**
* You are permitted to use AI tools (such as ChatGPT, Gemini, Claude, etc.) to help structure, generate, or debug your code.
* *Note:* You must still verify that the code meets all specific constraints below (e.g., using the exact variable names and structure definition required).

### Requirements
Write a program that lets a maker of chips and salsa keep track of sales for five different types of salsa: mild, medium, sweet, hot, and zesty. The program will use a custom data structure (class or record) named `Salsa` that holds the following information:

* `name` - a string to hold the name of the salsa.
* `sold` - an integer that holds the number of jars of that type of Salsa sold during the past month.

Create one collection (array or list) of `Salsa` structures containing 5 elements, one for each salsa type. Initialize the collection in your code (hard-coded) with the names for each Salsa. The program should prompt the user to enter the number of jars sold for each type. Once this sales data has been entered, the program should calculate and display the total sales and the name of the highest selling salsa.

You will create ONE structure definition. Do NOT create nested structures. The structure will have exactly TWO fields - a string and an integer. Use only standard concepts covered in the course. There will be a minimum deduction of two points if you do not follow these constraints. If the program does not run, it will receive 0 points.

### General Scoring Guide
* Defining the structure/class correctly: +5 points
* Correctly creating and initializing the collection with names: +5 points
* Correctly entering the number of jars sold: +2 points
* Correctly display the total sales: +4 points
* Correctly displaying the name of the highest selling salsa: +4 points

### A 20-Point Sample Run
```text
Enter jars of mild sold: 8
Enter jars of medium sold: 6
Enter jars of sweet sold: 7
Enter jars of hot sold: 5
Enter jars of zesty sold: 3

Total sales: 29
Highest selling salsa: mild

### Hints
* The array processing algorithms (e.g., summing, finding max) can be modified to be used on collections of objects.
* Review how to initialize arrays/lists with specific values in your chosen language.
* Review course materials regarding classes or structs.

### Submission Instructions
**Submit Source Code:** Message me directly via Discord (aarns) with your source code file attached.
    * *Reminder:* Do **not** include comments in the file revealing if you used AI or not.
