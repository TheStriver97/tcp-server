# Simple TCP Server in C

This is a simple TCP server written in C that listens on a specified port (8080 by default) and accepts incoming connections. Upon accepting a connection, it prints the received data from the client.

## Prerequisites

Before running the server, ensure that you have the necessary tools installed:

- **gcc:** The GNU Compiler Collection for compiling C code.
- **curl:** A command-line tool for making HTTP requests (used for testing).

## Getting Started

1. **Compile the Server:**

    ```bash
    gcc -o server server.c
    ```

2. **Run the Server:**

    ```bash
    ./server
    ```

    The server will start listening on the specified port (8080 by default).

3. **Test the Server:**

    Open a new terminal window and use `curl` to send a request to the server:

    ```bash
    curl http://localhost:8080/
    ```

    You should see the server output in the terminal where the server is running.

## Customization

- **Port Number:**
  You can change the default port number (8080) by modifying the `#define PORT` line in the `server.c` file.

- **Data Processing:**
  Modify the server code to process and respond to the received data as needed.

## Troubleshooting

If you encounter any issues, refer to the troubleshooting section in the README or check the error messages during server execution.

## Source 
Find the Video explanation from Bek Brace on [YouTube](https://www.youtube.com/watch?v=set7R_bHG_k).

## Acknowledgments

- Mention any acknowledgments or credits to external libraries, resources, or individuals if applicable.
