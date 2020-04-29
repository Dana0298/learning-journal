# **Text Editor Notes**

What is a text editor? A text editor is a piece of software that you download and install on your computer, or you access online through your web browser, that allows you to write and manage text.

The following are **features** that you should look for in a text editor
* **Code completion**:allows you to start typing, and the code completion feature will display possible suggestions based on what you originally typed.
* **Syntax highlighting**: takes the text you type and makes it more noticable by coloring the text. 
* **Themes**:having series of themes available
* **Extensions**:you can add more features to the text editor with extension. 

### Text Editor on computer
Every computer will come with its own text editor however there is no code completion, no syntax highlighting, no themes and no extensions. They’re the barest bare bones text editors you’ll encounter.


* **Mac computers** the text editor that comes with your computer is called, “Text Edit.” 
* **Windows computers** the text editor that comes with your computer is called, “Notepad.”
* **Linux computers** each distribution will have its own text editor already installed

### 3rd Party Text Editor
There is software like: Notepad++, Text Wrangler, BB Edit, Visual Studio Code, Atom, Brackets, and Sublime Text (these are all free of charge). They can be downloaded and installed on your computer. Not every software is available to Windows, MAC, or Linux computers. Each of these titles do have some if not all of the features that were listed above. 

### IDE (Integrated Development Environment)
An IDE is a text editor, a file manager, a compiler, and a debugger all in one software package.

# **Path**

We can refer to a location in a variety of different ways. You can use any method you like to refer to a location. Whenever you refer to a file or directory on the command line you are actually referring to a path

Absolute paths specify a location (file or directory) in relation to the root directory. You can identify them easily as they always begin with a forward slash ( / )

Relative paths specify a location (file or directory) in relation to where we currently are in the system. They will not begin with a slash.
* ~ (tilde) - This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to the directory Documents with the path /home/ryan/Documents or ~/Documents
* . (dot) - This is a reference to your current directory. eg in the example above we referred to Documents on line 4 with a relative path. It could also be written as ./Documents (Normally this extra bit is not required but in later sections we will see where it comes in handy).
* .. (dotdot)- This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy. eg if you were in the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory.

cd which stands for change directory

* /etc - Stores config files for the system.
* /var/log - Stores log files for various system programs. (You may not have permission to look at everything in this directory. Don't let that stop you exploring though. A few error messages never hurt anyone.)
* /bin - The location of several commonly used programs (some of which we will learn about in the rest of this tutorial.
* /usr/bin - Another location for programs on the system.

# Files

first thing we need to appreciate with linux is that under the hood, everything is actually a file. A text file is a file, a directory is a file, your keyboard is a file (one that the system reads from only), your monitor is a file (one that the system writes to only) etc.

A file extension is normally a set of 2 - 4 characters after a full stop at the end of a file, which denotes what type of file it is. The following are common extensions:
* file.exe - an executable file, or program.
* file.txt - a plain text file.
* file.png, file.gif, file.jpg - an image.

a path is a means to get to a particular location in the system and that location is a file

# Case Sensitivity

Windows and Mac (? ) are not case sensitive when it comes to referring to files. Linux is case sensitive. For instance with the command ls there are two options s and S both of which do different things.

# Quotes

Spaces in file and directory names are perfectly valid but we need to be a little careful with them. As you would remember, a space on the command line is how we seperate items. Anything inside quotes is considered a single item.

# Escape character

Another method is to use what is called an escape character, which is a backslash ( \ ). What the backslash does is escape (or nullify) the special meaning of the next character

# **The Terminal (AKA: The Command Line Interface (cli))**
A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.

* A command ( ls ). Typically a command is always the first thing you type.
* The first command line argument ( -l ) is also referred to as an option. Options are typically used to modify the behaviour of the command. Options are usually listed before other arguments and typically start with a dash ( - )
* there must be a space between the command and the first command line argument

* mkdir *name of folder*: To create a new folder and name it. 
* ls: it lists all the files and directories in the current directory that you are on.
* cd *name of folder*/: will bring you inside that folder
* pwd: it will spit out the exact file path for the file or folder you are in
* cd .. :  To navigate up one directory level
* code . : takes you to VS code

[Tools & Terminal Notes:](tools-terminal.md)
