Throw vs Throws in java
1. Throws clause is used to declare an exception, which means it works similar to the try-catch block. 
On the other hand throw keyword is used to throw an exception explicitly.

2. If we see syntax wise than throw is followed by an instance of Exception class and throws is followed by 
exception class names.
For example:

throw new ArithmeticException("Arithmetic Exception");
and

throws ArithmeticException;
3. Throw keyword is used in the method body to throw an exception, while throws is used in method signature 
to declare the exceptions that can occur in the statements present in the method.

For example:
Throw:

...
void myMethod() {
   try {
      //throwing arithmetic exception using throw
      throw new ArithmeticException("Something went wrong!!");
   } 
   catch (Exception exp) {
      System.out.println("Error: "+exp.getMessage());
   }
}
...
Throws:

...
//Declaring arithmetic exception using throws
void sample() throws ArithmeticException{
   //Statements
}
...
4. You can throw one exception at a time but you can handle multiple exceptions by declaring them using throws keyword.
For example:
Throw:

void myMethod() {
   //Throwing single exception using throw
   throw new ArithmeticException("An integer should not be divided by zero!!");
}
..
Throws:

//Declaring multiple exceptions using throws
void myMethod() throws ArithmeticException, NullPointerException{
   //Statements where exception might occur
}
These were the main differences between throw and throws in Java. Lets see complete examples of throw and throws keywords.

