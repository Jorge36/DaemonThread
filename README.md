# DaemonThread
Daemon Threads and Static class in Java.

Coding exercise taken from Udemy course [Java Multithreading, Concurrency & Performance Optimization](https://www.udemy.com/course/java-multithreading-concurrency-performance-optimization/?couponCode=ST21MT60724).

Daemon threads are are low-priority threads whose only role is to provide services to user threads. 
Since daemon threads are meant to serve user threads and are only needed while user threads are running, they won’t prevent the JVM from exiting once all user threads have finished their execution.
Java allows a class to be defined within another class. These are called Nested Classes. The class in which the nested class is defined is known as the Outer Class. Unlike top-level classes, Nested classes can be Static. Non-static nested classes are also known as Inner classes.

More information about these topics:
1. https://www.baeldung.com/java-daemon-thread
2. https://www.geeksforgeeks.org/static-class-in-java/



