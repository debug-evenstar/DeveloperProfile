# Developer Profile CLI

A simple Java command-line application that displays my developer profile: name, learning track, current focus and career goal.

This is my Week 1 project for the Six-Month Software Engineering Programme. It practises Java setup, compiling and running from the terminal, and version control with Git and GitHub.

## Requirements

- Java Development Kit (JDK) installed. Built and tested with JDK 25 (Eclipse Temurin), but any recent JDK should work.
- A terminal (Terminal on macOS/Linux, or Git Bash/Command Prompt on Windows)

To check that Java is installed, run:

    java -version
    javac -version

Both commands should print a version number.

## How to run

1. Clone the repository:

       git clone https://github.com/debug-evenstar/DeveloperProfile.git

2. Move into the source folder:

       cd DeveloperProfile/src

3. Compile the program:

       javac DeveloperProfile.java

   This creates a `DeveloperProfile.class` file containing the compiled bytecode.

4. Run the program:

       java DeveloperProfile

## Expected output

    ========================================
       DEVELOPER PROFILE
    ========================================
    Name: Aniekpeno Undomiel
    Track: Software Engineering
    Learning: Java
    Current Focus: Programming Foundations
    Goal: Build Reliable Software
    ========================================

## Project structure

    DeveloperProfile/
    ├── src/
    │   └── DeveloperProfile.java   # Main program
    ├── .gitignore                  # Excludes compiled files and IDE settings
    └── README.md

## What I learned

- The difference between the JDK, JRE and JVM
- Compiling Java source code into bytecode with `javac` and running it with `java`
- Navigating folders in the terminal using relative and absolute paths
- Using Git branches, merging, and `.gitignore` to keep generated files out of the repository