# Linux For Absolute Beginner

### History of Linux
+ In 1969, a team of developers of Bell Labs started a project to make a common software for all the computers and named it as 'Unix'. It was simple and elegant, used 'C' language instead of assembly language and its code was recyclable. As it was recyclable, a part of its code now commonly called 'kernel' was used to develop the operating system and other functions and could be used on different systems. Also its source code was open source.
+ In 1991, Linus Torvalds a student at the university of Helsinki, Finland, thought to have a freely available academic version of Unix started writing its own code. Later this project became the Linux kernel. He wrote this program specially for his own PC as he wanted to use Unix 386 Intel computer but couldn't afford it. He did it on MINIX using GNU C compiler. GNU C compiler is still the main choice to compile Linux code but other compilers are also used like Intel C compiler. He started it just for fun but ended up with such a large project. Firstly he wanted to name it as 'Freax' but later it became 'Linux'. He published the Linux kernel under his own license and was restricted to use as commercially. Linux uses most of its tools from GNU software and are under GNU copyright. In 1992, he released the kernel under GNU General Public License.

### Types of Linux Distro

![Linux Distro](https://tellmeinsimpleterms.files.wordpress.com/2013/07/linux-tree.png)

### Linux V/S Windows

![Linux V/S Windows](https://cdn.educba.com/academy/wp-content/uploads/2018/08/Linux-vs-Windows-Server-1.jpg)

### CLI V/S GUI

![CLI V/S GUI](https://pediaa.com/wp-content/uploads/2018/07/Difference-Between-GUI-and-CLI-Comparison-Summary.jpg)

### Users in Linux

> Regular User: Home Directory Access

> Root User: Full Access
 
> Server User: Service based Access

### Absolute & Relative Path

![Path](https://1.bp.blogspot.com/-UQ7-sWd_J4w/WmhKIFx7_fI/AAAAAAAAHIE/tixi5SsyI5YzoJygq_JQKL50axe2cAcrQCLcBGAs/s1600/Untitled.png)

### Command and Shell

Gift         ---> English          ---> Present
(Command)	  (Shell)		(Meaning)

Gift         ---> German           ---> Poison
(Command)	  (Shell)		(Meaning)


Conclusion-
Commands are just text you type in Terminal.
Commands are interpreted by the Shell.
Terminal is the window to the Shell.
Commands are case sensitive.
CommandNames needs to be on the Shell's search path.
Commands operate on Inputs.
Options modify a command's behaviours.
Command= CommandName Options Inputs

### Basic Commands
|Command|Output|Shortcut Key|
|-------|------|------------|
|-|Open Terminal|Ctrl + Alt + T|
|echo x OR printf x|Print x|-|
|cal|Shows Calender of current month|-|
|cal 2020|Shows Calender of particular year|-|
|cal -y|Shows Calender of current year|-|
|date|Shows Date and Time|-|
|clear|Clear Terminal screen|Ctrl + L|
|history|Shows History|-|
|!x |Print xth command of history|-|
|!!|Print Recent command of history|-|
|ls|list|-|
|mkdir FolderName|Makes a folder of FolderName|-|
|mv x|Move file x|-|
|cp x|copy file x|-|
|pwd|Print Working Directory|-|
|whoami|Show logged User|-|
|exit|Exit Terminal|Ctrl + D or Alt + F4|

### Advanced Package Tool

> sudo apt-get update

  OR

> sudo apt update

  are used to update list of all repo. available.
```markdown
Form Ubuntu 18.04 we can use `apt` instead of `apt-get`.
```

> sudo apt upgrade

is used to update installed programs.

```markdown
🌟 CLT is case sensitive.
```

### User Permission

To understand this, type 
> ls -l 

in terminal.

![sample](https://i.ibb.co/n356dL1/Screenshot-from-2021-02-28-13-52-09.png)

So question is what -rw-r-r mean ?

![chart](https://assets.digitalocean.com/articles/linux_basics/mode.png)


### chmod

This command is used to modify permission of owner, group and public.

![chmod](https://i.ibb.co/1s9SjRN/Screenshot-from-2021-02-28-15-00-27.png)

Here,<br>
(111)<sub>2</sub> -> (7)<sub>10</sub> <br>
(110)<sub>2</sub> -> (6)<sub>10</sub> <br>
(100)<sub>2</sub> -> (4)<sub>10</sub> <br>

> Refer this as Binary Number

So, we can modify permission with the help of this command like

```Bash
chmod 764 filename.xyz
```
*****

<code>
$ -> Regular User
</code><br>

<code>
# -> Root User
</code><br>

*****

🌟 Some Important Linux Commands
|S. No.|Command|Use|
|-|-|-|
|1|top|Shows resource consumer processes|
|2|ps|Shows ongoing process|
|3|ps -a|All onging process|
|4|kill|To kill process|

```
For example- 
kill 341123
Where, 341123 is PID which we get by using "top" command.
```
