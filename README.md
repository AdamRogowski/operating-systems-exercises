# Practical exercises from Operating Systems area

Assignments for TDT4186 Operating Systems course at NTNU

## Description

### A Unix-based alarm clock

The objective of this exercise is to write a C program for a Unix-like operating system that implements the function of an alarm clock.

The alarm clock program implements the following functionality:

- Schedule a new alarm (input “s”) The program asks for the (absolute) time at which the new alarm should ring.
- List all currently active alarms (input “l”) All active alarms are displayed, each with a unique number
- Cancel a scheduled alarm (input “c”) The number of the alarm to cancel is an input
- Exit the alarm clock program (input “x”)

### A multithreaded web server

The task is to implement a multi-threaded webserver mtwwwd in a file mtwwwd.c. The server listens on a configurable TCP port port and delivers HTML files that are located in a directory hierarchy below the web root directory passed as www-path.

### Unix Shell

The task is to implement a simple Unix shell called the “famous little unix shell” flush. flush should be an interactive shell with minimal functionality that is nevertheless doing some useful things.

- change directories
- I/O redirection for stdin and stdout
- execute background tasks
- print running background processes
- Pipelines

## Authors

Adam Rogowski

[Mikołaj Blinowski](https://github.com/miko3412)

Jonas (the German guy)
