# CodingProject-4-GPU-CUDA

Simple Shell (C, Makefile) – Developed a custom shell running on top of the regular Linux command-line interpreter. The project involved:

Implementing functionality to read and parse user input commands, allowing execution of both absolute paths (e.g., /bin/ls) and commands using path expansion through the execvp() function.
Utilizing system calls like fork() to create new processes and execvp() to execute commands in the context of these processes.
Implementing process control by making the shell wait for child processes to complete, then printing the child process ID (PID) and return status.
Ensuring compatibility with standard Linux commands by enabling users to specify executable file paths or rely on the PATH environment variable for locating executables.
Writing a Makefile to automate compilation and linking of the project, ensuring efficient development and testing workflows.
