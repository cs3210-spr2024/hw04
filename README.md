# Homework 04 - Linux Environment

This assignment will give you exercises on making system calls and working with files in C.  Assignment is worth **135** points.

## Last name, first name

`Github username`

## Information For **ALL** Exercises

- Must be written in C.
- Must compile and run on Linux (ie. class server or Darwin).
- All input or output file names must be command-line arguments.
- All code (*.c) files must be in the `src/` folder.
- All binary files must be in the `bin/` folder.
- Use a Makefile with targets for each of the exercises.
  - A target named `clean` should remove all the binary and object files for every exercise.
  - Each exercise should have **2** targets.  One for the build and another to run it.
  - Target names must follow this format `ex??_bld` and `ex??_run` (ex. `ex01_bld` and `ex02_run`).
- Don't forget to put your name and Github user name in the `README.md` file.

### Exercise 01 (15 points)

Code a program that splits command-line options from the command line arguments.

### Exercise 02 (15 points)

Code an extended version of `args.c` that flags up illegal options and that expects arguments following some options.

### Exercise 03 (15 points)

Code a program that prints out all the environment variables with their current values.

### Exercise 04 (15 points)

Code a program that prints human time.

### Exercise 05 (15 points)

Code program that prints the local time.

### Exercise 06 (15 points)

Code a program that creates a unique temporary file.

### Exercise 07 (15 points)

Code a program that prints information about the user from the password file.

### Exercise 08 (15 points)

Code program that prints information about the host computer.

### Exercise 09 (15 points)

Code program that writes message to syslog on error.
