R Programming Language

R is an interpreted language that’s strictly case- and character-sensitive,
which means that you enter instructions that follow the specific syntactic
rules of the language into a console or command-line interface. The software then interprets and executes your code and returns any results.
R is what’s known as a high-level programming language. Level refers to the level of
abstraction away from the fundamental details of computer execution. That is, a lowlevel language will require you to do things such as manually manage the machine’s
memory allotments, but with a high-level language like R, you’re fortunately spared
these technicalities.


1. Comments in R
To annotate a comment in R just use # to start the line.

SYNTAX:
#This is a comment in R
--

2. Working Directory
- R always has a working directory associated with it
- Unless there is Directory associated with it, it will use this one

SYNTAX:
# To check the default set work directory
getwd()
--

- File paths are always enclosed in double quotation marks.
- R uses forward slashes, not backslashes, when specifying folder locations.
- Incase you end up using backslashes, R process double backslashes a single forward slash.

SYNTAX
# To set a working directory
setwd("file_Location/file_Name")
setwd("file_location\\file_name")

3.





