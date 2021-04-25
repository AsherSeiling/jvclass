# JVclass
A command line program for MacOS (Some principals may be able to be transferred to Lunix) that automates many complex actions in java.
```
Pyinstaller
OS
python3
```
# Installation instructions
```
git clone https://github.com/AsherSeiling/jvclass
cd java-class-creator
chmod +x config.sh
./config.sh
```
# Commands
The sheet of commands that you can use in jvclass
## Class Creation
### Create new main class
Create a class with "public static void main(String[] args){}"
```
jvclass new-main-class <class name>
```
### Create new class
Creates a basic java class with the basic class sytax already inserted
```
jvclass new-class <class name>
```
## Make new project
```
jvclass new-project <project name> <package name> <main file name>
```
## Building and Compilation
### Compile and run a singlular java file
```
jvclass comp-run <filename>
```
### Build entire project
Must be in the projects directory
```
jvclass pj-build
```
## Running
```
jvclass pj-run
```