# Learn Java
<h1 align="center">
  <br>
  <img src="learnjava.png" />
   
  </h1>
A brief tutorial about Java and JEE.
## Getting Started

**Java** is a high-level programming language originally developed by Sun Microsystems and released in 1995. Java runs on a variety of platforms, such as Windows, Mac OS, and the various versions of UNIX. This tutorial gives a complete understanding of Java. This reference will take you through simple and practical approaches while learning Java Programming language
<br>
Java is 
<br>
<ul>
<li>Object Oriented − In Java, everything is an Object. Java can be easily extended since it is based on the Object model.</li>

<li>Platform Independent − Unlike many other programming languages including C and C++, when Java is compiled, it is not compiled into platform specific machine, rather into platform independent byte code. This byte code is distributed over the web and interpreted by the Virtual Machine (JVM) on whichever platform it is being run on.</li>

<li>Simple − Java is designed to be easy to learn. If you understand the basic concept of OOP Java, it would be easy to master.</li>

<li>Secure − With Java's secure feature it enables to develop virus-free, tamper-free systems. Authentication techniques are based on public-key encryption.</li>

<li>Architecture-neutral − Java compiler generates an architecture-neutral object file format, which makes the compiled code executable on many processors, with the presence of Java runtime system.</li>

<li>Portable − Being architecture-neutral and having no implementation dependent aspects of the specification makes Java portable. Compiler in Java is written in ANSI C with a clean portability boundary, which is a POSIX subset.</li>

<li>Robust − Java makes an effort to eliminate error prone situations by emphasizing mainly on compile time error checking and runtime checking.</li>

<li>Multithreaded − With Java's multithreaded feature it is possible to write programs that can perform many tasks simultaneously. This design feature allows the developers to construct interactive applications that can run smoothly.</li>

<li>Interpreted − Java byte code is translated on the fly to native machine instructions and is not stored anywhere. The development process is more rapid and analytical since the linking is an incremental and light-weight process.</li>

<li>High Performance − With the use of Just-In-Time compilers, Java enables high performance.</li>

<li>Distributed − Java is designed for the distributed environment of the internet.</li>

<li>Dynamic − Java is considered to be more dynamic than C or C++ since it is designed to adapt to an evolving environment. Java programs can carry extensive amount of run-time information that can be used to verify and resolve accesses to objects on run-time.</li>

### Prerequisites
For performing the examples discussed in this tutorial, you will need a Pentium 200-MHz computer with a minimum of 64 MB of RAM (128 MB of RAM recommended).

You will also need the following softwares −

Linux 7.1 or Windows xp/7/8 operating system
Java JDK 8
Microsoft Notepad or any other text editor
This tutorial will provide the necessary skills to create GUI, networking, and web applications using Java.
### Java Basics
When we consider a Java program, it can be defined as a collection of objects that communicate via invoking each other's methods. Let us now briefly look into what do class, object, methods, and instance variables mean.

<ul>
<li>Object − Objects have states and behaviors. Example: A dog has states - color, name, breed as well as behavior such as wagging their tail, barking, eating. An object is an instance of a class.

<li>Class − A class can be defined as a template/blueprint that describes the behavior/state that the object of its type supports.

<li>Methods − A method is basically a behavior. A class can contain many methods. It is in methods where the logics are written, data is manipulated and all the actions are executed.

<li>Instance Variables − Each object has its unique set of instance variables. An object's state is created by the values assigned to these instance variables.
</ul>

```
public class MyFirstJavaProgram {

   /* This is my first java program.
    * This will print 'Hello World' as the output
    */

   public static void main(String []args) {
      System.out.println("Hello World"); // prints Hello World
   }
}
```

## Java basic systax

About Java programs, it is very important to keep in mind the following points.
<ul>
<li>Case Sensitivity − Java is case sensitive, which means identifier Hello and hello would have different meaning in Java.</li>

<li>Class Names − For all class names the first letter should be in Upper Case. If several words are used to form a name of the class, each inner word's first letter should be in Upper Case.</li>

Example: class MyFirstJavaClass

<li>Method Names − All method names should start with a Lower Case letter. If several words are used to form the name of the method, then each inner word's first letter should be in Upper Case.</li>

Example: public void myMethodName()

<li>Program File Name − Name of the program file should exactly match the class name.</li>
</ul>
When saving the file, you should save it using the class name (Remember Java is case sensitive) and append '.java' to the end of the name (if the file name and the class name do not match, your program will not compile).

Example: Assume 'MyFirstJavaProgram' is the class name. Then the file should be saved as 'MyFirstJavaProgram.java'

public static void main(String args[]) − Java program processing starts from the main() method which is a mandatory part of every Java program.


A step by step series of examples that tell you have to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds


## Authors

* **Aymanov** - *Initial work* - [Aymanov1](https://github.com/Aymanov1)


## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* etc
