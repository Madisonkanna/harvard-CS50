# Notes 🔎

C

## TABLE OF CONTENTS

- [C Language](#c)

## C language

**Source code** is the general term for what programemrs write. Of course, computers don't undestand source code, they only understand binary - information represented in binary. The techincal term now for language that computers understand is called **machine code.**

Source code is the input, the output is machine code (put diagram). The purpose of compilers is to convert source code to machine code.

Your source code should be correct, well designed, and styled well - the aesthetics of your code.

For CS50, we use VSCode to write our code, this will be our text editor. VSCode has within it a terminal window. A terminal window provides what is generally called a CLI, a command-line interface. This is in contrast with a GUI (a graphical user interface) - we use GUIs every single day - on our phones, computers, it's just graphical - menus, icons, buttons - we use our fingers or a mouse to interact with it. Yet most programmers come to prefer CLIs over time, where you do everything (somewhat arcanly) with a keyboard alone. Why? There's more features built in to most computers if you can access them with a keyboard - you can also type faster than you can point and click. Over time, you can get comfortable using your terminal window.

Functions have arguments and sometimes side effects. For exampe, printing out 'hello world' is a side effect. "/n" adds a new line.

Semicolons are put after statements, semicolons are similar to english periods when a sentence is finished.

#include <stdio.h> is a header file that declares (printf) to exist in your file. The reaon for this - efficiency. Computers used to be slower and you didn't want to give yourself access to the entire kitchen sink of functionality. Header files contain enough info about all of the functions in what is called the standard IO library. Standard IO just means standard input and ouput. This line (#include <stdio.h>) is just telling the compiler we want to use functionality from this library in this file of code.

https://manual.cs50.io/ is the simplified verson of the official C docs. In the world of C and other langs, there are manual pages - text-based docs that are hard for new programers to understand.

In C, if you want to get back a return value from a function like get_string, you have to do this:

`string answer = get_string("What's your name? /n")`

This is assignment and it means copy the value on the right over to the value on the left.

`printf("hello, %s ");` This is a format code in C - it means this is a placeholder for a string. %S is treated specially to mean, plug in some value here. Prtinf is smart about this - if you have 1 %S and 1 additional arg after a comma, it plugs the variable in.

## Conditionals in C

Decision-making in our code.

```c
#include <cs50.h>
#include <stdio.h>
int main(void)
{
    int x = get_int("What's an x? ")
    int y = get_int("What's an y? ")

    if (x < y) {
        printf("x is less than y\n")
    }
}
```

Our terminal will show 'What's x/y' and we give it input.

## Loops and Variables

Creating a variable: `int counter = 1`;

```c
int counter = 3;
while (counter > 0) {
    printf("meow\n");
    counter = counter - 1;
}
```

## Command-line interface

Most of us run MacOS or Windows, but another operating system is Linux, often used on servers. Linux is just an alternative to MacOS or Windows that proides you with a GUI and CLI environment. Windows and MacOS do have terminal windos but Linux is really know for its CLI / the terminal window. The terminal window is really just your CLI to your own server in the cloud. Some commands:

`cd
cp
ls - list. 
mkdir
mv
rm 
rmdir`
