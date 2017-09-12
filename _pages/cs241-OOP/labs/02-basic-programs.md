---
layout: lecture
title: "First C++ Programs"
permalink: '/labs/oop-lab/02-basic-programs'
---

<p class="message">
  Learn how to write and compile a C++ program.
</p>

Lab 2

- Write a simple Helo World Program
- Compile and Run the program using command line
- Write Two Practice Programs

<h4>
	<span class="fa fa-code fa-lg main-list-item-icon"></span>
	Tutorial
</h4>

## Compilation Process


 if you have a C++ source code file named prog1.cpp and you execute the compile command
```
   g++  -std=c++11 -o prog1 prog1.cpp
```
if no erros are encountered by the compiler then an executable with the name of prog1 will be generated.
To run the program, go to the directory (using cd command ) where the executable is generated and run  as

```
    ./prog1

```

## Exercise 1

### Task 1
Type the following program and compile and run it.

```cpp
#include<iostream>


using namespace std;

class GradeBook {
public:
  void displayMessage(){
    cout <<" Getting Started with oop \n" ;
  }

};


int main()
{
  GradeBook gradebook;
  gradebook.displayMessage();

}

```


### task 2
- Add another method  "showcourse()"  to the class. The method should take one argument of type string.
- call the method main function and pass a course name as an argument;
- Remember to include relevant header file for string
