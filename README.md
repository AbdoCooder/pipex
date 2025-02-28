# pipex 🔗

## Overview 📚
**pipex** is a project that involves creating a program to mimic the behavior of the shell pipeline (`|`). This project, part of the **42cursus**, helps in understanding process creation, inter-process communication (IPC), and file handling in Unix-like systems. Through this project, I gained a deep understanding of processes, pipes, and system calls in C.

## Key Skills and Concepts Learned 🛠️

### Process Creation and Management 🏗️
- **Forking Processes**: Learned to use the `fork()` system call to create child processes.
- **Process Synchronization**: Managed synchronization between parent and child processes to ensure proper execution flow.

### Inter-Process Communication (IPC) 🔄
- **Pipes**: Implemented pipes using the `pipe()` system call to facilitate communication between processes.
- **Redirection**: Redirected input and output using `dup2()` to connect file descriptors with pipes.

### File Handling 📂
- **File Descriptors**: Worked with file descriptors to read from and write to files.
- **Error Handling**: Implemented robust error handling to manage system call failures and resource cleanup.

### Code Organization and Best Practices 📏
- **Modular Code**: Organized code into separate modules for better readability and maintainability. Used helper functions to break down complex operations.
- **Norm Compliance**: Adhered to the 42 school's Norm, a set of coding standards that enforce good coding practices, ensuring consistency and readability across the project.

## Project Highlights 🌟

### pipex Implementation 📜
- **Program Execution**: Implemented the `pipex` program to execute a series of commands connected by pipes, mimicking the shell pipeline behavior.
- **Command Parsing**: Parsed command-line arguments to extract and execute the specified commands.
- **File Redirection**: Handled input and output redirection to read from input files and write to output files.

### System Calls and Error Handling 🔧
- **System Calls**: Utilized system calls such as `fork()`, `execve()`, `pipe()`, and `dup2()` to implement the required functionality.
- **Error Management**: Ensured proper error management by checking return values of system calls and providing meaningful error messages.

### Performance Optimization 🚀
- **Efficient Piping**: Optimized the use of pipes to minimize overhead and ensure efficient data transfer between processes.
- **Resource Cleanup**: Implemented resource cleanup to close file descriptors and free allocated memory, preventing resource leaks.

## Bonus Features 🎁
- **Advanced Piping**: Extended the program to handle multiple pipes and commands, enhancing its versatility.
- **Environment Variables**: Implemented support for environment variables to modify the execution environment of commands.

## Conclusion 🏁
Completing the **pipex** project was a significant milestone in my systems programming journey. It provided me with a solid foundation in process management, inter-process communication, and file handling. The skills and knowledge gained through this project have prepared me to tackle more complex systems programming challenges and contribute effectively to any development team.

---

*This project is part of the 42cursus at [42 Network](https://www.42.fr/).*
