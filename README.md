# PC-RAT-Code-Python
A basic Python reverse shell developed for ethical hacking training. It demonstrates TCP socket programming, remote communication, command handling, file system navigation, and system command execution using Python's `socket`, `os`, `subprocess`, and `sys` modules. Intended for use only in authorized educational lab environments.


# Python Reverse Shell (Educational Lab Project)

## Description

This project is a basic Python reverse shell created as a learning exercise during an ethical hacking course. It demonstrates how network sockets, operating system interaction, and Python modules can work together to establish a remote communication channel in a controlled laboratory environment.

The program creates a TCP socket and attempts to connect to a predefined IP address and port. After a successful connection, it continuously waits for incoming commands from the connected host. Based on the received command, it performs different actions such as listing the contents of the current directory, changing the working directory, clearing the console, or executing system commands. The result or any error message is then sent back through the same socket connection.

## Python Modules Used

* **socket** – Establishes the TCP network connection.
* **os** – Performs operating system tasks such as listing files and changing directories.
* **subprocess** – Executes system commands and captures their output.
* **sys** – Terminates the program when execution is complete.

## Features

* TCP socket communication
* Persistent command-processing loop
* Directory listing
* Working directory navigation
* Console clearing
* Execution of operating system commands
* Error handling using `try` and `except`
* Graceful socket closure and program termination

## Learning Objectives

This project helps demonstrate the following Python concepts:

* Socket programming
* Client-server communication
* Basic networking concepts (IP addresses and ports)
* Process execution with the `subprocess` module
* File system interaction using the `os` module
* Exception handling
* String encoding and decoding (`encode()` / `decode()`)
* Loop control and program flow

**Note:** This project is intended solely for educational use in an authorized and controlled lab environment. It should only be used on systems that you own or have explicit permission to test.
