
Advantage of lambda operation:
1) Lambda supports parallel processing.
2) Enables functional programming.

In order to utilize lambda create/ or use an existing funcational inteface which contains that only one method with the same signature as a return type of lambda and use it as a type of the variable on which lambda is getting assigned.
 
 * Type Interface : Compiler tries to match the lambda expression with the related interface.
 * Functional Interface : can contain only one abstract method and multiple default defined method
 * Default Methods : For creating a default method in java interface, we need to use “default” keyword with the method signature.Now when a class will implement Interface1, it is not mandatory to provide implementation for default methods of interface.But during extending multiple interfaces it’s made mandatory to provide implementation for common default methods of interfaces.
 * Static Methods : we can’t override them in the implementation classes it helps us in providing security by not allowing implementation classes to override them.
