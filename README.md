# Lessons Learned about Exception Handling

During my training, I learned that an exception is an event that interrupts the normal processing flow of a class and that the proper use of exceptions makes the program more robust and reliable.

Furthermore, I understood that with exception handling, a program can continue to execute after dealing with a problem. I learned that it's important to incorporate the exception handling strategy into the system from the beginning of the design process, as it can be difficult to include efficient exception handling after a system has been implemented.

I understood that there are three types of exceptions: Error, Unchecked Exception, and Checked Exception. Checked Exceptions must be handled by the developer for the program to function, while Unchecked Exceptions can be avoided with proper coding.

I also learned about creating Custom Exceptions, which are useful for handling specific problems. Before creating my own exception, I should check if there's already an exception in the Java library that can provide what I need.

Finally, I understood the importance of the try/catch/finally blocks. The try block is where the code we want to verify whether it will or will not throw an exception is located. The catch block is the region where the possible exception handling is located, while the finally block is usually used when we need to execute some code regardless of whether an exception occurs or not.

I also learned about the throws and throw clauses. The throws clause is used in the method signature and is only required for checked exceptions. The throw clause explicitly throws an exception.

With all of these learnings, I'm more prepared to handle exceptions in my programs.
