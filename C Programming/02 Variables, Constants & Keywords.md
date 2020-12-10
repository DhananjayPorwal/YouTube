## Variables 
Variables is a container which stores a **value**. Like, glass is a _container_ and water is a _value_. For example:<br>
a = 7<br>
b = 2.14<br>
c = 'A'<br>

#### Rules for naming Variables<br>
+ First character must be an alphabet or underscore.
+ No special symbols other than underscore are allowed.
+ Variables names are case sensitive.
+ Neither comma or blanks are allowed.

### Types of variables
+ Integer Variables - int a = 3;<br>
+ Real Variables - float b = 3.3;<br>
+ Character Variables - char c = 'a';<br
  
## Constants
As the name describe itself, the unchangeble values are called constants.

### Types of constants
+ Integer Constants - 2,0, -1<br>
+ Real Constants - 2.11, -0.99, 3.0<br>
+ Character Constants - 'a', '$'<br>

## Keywords
![Keywords](https://github.com/DhananjayPorwal/YouTube/blob/main/C%20Programming/Gallery/keywords.png)

## Our first C Program
``` C
#include<stdio.h>
int main()
{
    printf("Hello World\n);
    return 0;
}
```
## Basic Structure of C Programs
All C Programs have to follow some basic instructions like C programs starts with a main function and executes instructions line by line inside it.
Each instruction terminate with semicolon.

## Comments
Comments clarify something related to program. Comments are ignored by complier. This are only for reference by which anyone can our code.

Two types of comments:
+ Single-Line Comment:
``` C
//This is Single-Line Comment
```
+ Multi-Line Comment:
``` C
/*This
is
Multi
Line
Comment*/
```
## Compilation and Execution
![Compilation and Execution](https://github.com/DhananjayPorwal/YouTube/blob/main/C%20Programming/Gallery/Compilation%20and%20Execution.png)

## Library Function
C language has several valuable libraries functions which are used to carry out certain tasks. For example printf function is use to display message/text on screen.

##### Receiving Input From User
For receiving input form user we use a function called **scanf**.
scanf("%d", &a);
where %d shows input must be integer value and &a  shows address of variable a.
