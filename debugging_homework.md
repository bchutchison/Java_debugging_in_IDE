# Introduction to Debugging in IDE

## Learning Objectives
- Know how to debug a Java application
- Understand breakpoints
- Understand the debugger console
- Know how to evaluate code fragments

## Task
As an introduction to debugging:
- watch the following video: [Intro to Debugging video](https://youtu.be/ErVZrVWZrko)


Answer the following questions:
1. What is the purpose of a breakpoint? 
- Specifies the point in the code where the the code should pause and the debugger should commence

2. Does the line of code on a breakpoint run when you start debugging?
- No, it stops on the first line of code and updates the arguments.

3. How do we debug the next line of code?
- Press StepOver will run the first line of code specified by the breakpoint and then pause on the next line of code.

4. What does the step into command do?
- StepInto will switch to the deal method and pause at the top of that method.

5. What is the difference between evaluate expression and evaluate code fragment?
- Expression => call methods on instances of objects created. Check values.
- Code Fragment => Run multiple methods on multiple lines of code. Also allows creation of temporary variables to store valeus.

