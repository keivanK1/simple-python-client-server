# Simple Client Server Application with Python

This project provides a very simple client server application in a way that client will send string to the server and server will just echo it.

## Prerequisite

* Python version 3.

## How to use

* Clone the project in your server and client and change the directory. Server can be AWS EC2 or other providers or any other computer.

      git clone https://github.com/keivanK1/simple-python-client-server.git
      cd simple-python-client-server
* Run the server application in your server:

      python3 server.py
* Run the client application in client side:

      python3 client.py [IPofServer]
