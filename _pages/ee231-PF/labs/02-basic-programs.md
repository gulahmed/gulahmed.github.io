---
layout: lecture
title: "Getting started with Java "
permalink: '/labs/pf-labs/02-basic-programs'
---

<p class="message">
  Learn how to write and compile a Java program.
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


 if you have a Java source code file named prog1.java and you execute the compile command
```
   javac prog1.java
```
if no erros are encountered by the compiler then generates an outputfile with .class extension. The name of the output file will be the same name as that of the class name of your program. E.g. if your class name was HelloWorld then javac will generate the output with the name of HelloWorld.class.

To run the program, make sure you are in the directory (using cd command ) where the output is generated and run  as

```
    java HelloWorld

```

## Exercise 1

### Task 1

Type the following program and save it as sayHello.java and compile and run it.

```java

class HelloWorld{

public static void main(String args[])
{

  System.out.println("My first Java Program!!");
}

}



```


### task 2

- in the above code, create a variable *message* of type String and initialise it with some text.
- use System.out.println to show the text stored in *message* variable

## Exercies 2

