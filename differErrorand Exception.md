Recovering from Error is not possible.	We can recover from exceptions by either using try-catch block or throwing exceptions back to caller.
All errors in java are unchecked type.	Exceptions include both checked as well as unchecked type.
Errors are mostly caused by the environment in which program is running.	Program itself is responsible for causing exceptions.
Errors occur at runtime and not known to the compiler.	All exceptions occurs at runtime but checked exceptions are known to compiler while unchecked are not.
They are defined in java.lang.Error package.	They are defined in java.lang.Exception package
Examples :
java.lang.StackOverflowError, java.lang.OutOfMemoryError	Examples :
Checked Exceptions : SQLException, IOException
Unchecked Exceptions : ArrayIndexOutOfBoundException, NullPointerException, ArithmeticException.

