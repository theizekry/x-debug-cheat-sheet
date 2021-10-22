# **X-Debug cheat sheet.**

###### It's just cheat sheet, for X - debug to anyone wants to start to use this amazing tool.



### In order to use the debugger you need to know about the following concepts:



## Breakpoints

> Please BREAK at this point and tell the server what's going on

## Call stack

>  A list of functions in the debugger that explains how the program got to where it currently is.
>
> Think of this as a live stack trace, without the exception.

## Stepping

> Stepping is the action of "telling the debugger" to advance through your program one line at a time. Remember, a computer program is many small steps combined to form a large goal. It is often the case that one of these small steps is "incorrect". To identify which step is incorrect, we **"step"** through the program, looking at each line of code as we come to it, and seeing what effect this has on the **VARIABLES** (really the data in the variables)

> ## ## **There** are several  ways to tell the debugger to move through the code:

> # Step over
>
> Step Over the current function/method. 
>
> Runs the function/method, **but doesn't debug into it**.

> # Step into 
>
> Step Into the current function/method.
>
> Move to the file the function was declared and **steps over** that function.

> # Step Out
>
> Step Out of the current function/method.
>
> Move to the place that the return value is used.

## ***Sources:***

> Step Into Step-through Debugging.
>
> https://www.fourkitchens.com/blog/article/step-step-through-debugging/

>  Step Into Debugging with PhpStorm
>
>  https://www.youtube.com/watch?v=GokeXqI93x8

>  Learn How to Debug PHP with Xdebug and VsCode
>
>  https://www.cloudways.com/blog/php-debug/
>
>  https://docs.microsoft.com/en-us/visualstudio/debugger/debugger-feature-tour?view=vs-2019

