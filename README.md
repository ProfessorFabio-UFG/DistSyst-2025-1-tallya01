[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/0NmVE7bP)
# POO-JavaRMI-Hello
Simple example used to teach distributed objects in the OOP course

Based on Oracle's Java RMI Guide: https://docs.oracle.com/javase/8/docs/technotes/guides/rmi/hello/hello-world.html

It is composed by three files:

- Hello.java: description of the remote object's interface
- Server.java: implementation of the remote object + code to start a server process where the object will run
- Client.java: a simple client to demonstrate the invocation of method's on the remote object.

### First, install the JDK on the machines:

  sudo apt install default-jdk

### Then, configure the firewall (security group)

  Open the following ports for TCP: 1099, 1900

### Then, run the server on one machine and the client on another

  java example.hello.Server

  java example.hello.Client <IP_Address_of_Server>
  
### Now, extend the example:

Try adding other methods to the remote object and calling them from the client.
