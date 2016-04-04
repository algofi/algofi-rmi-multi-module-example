Example on how to use RMI : Remote Method Invocation (JAVA).

This example is designed around a simple architecture with
* a common project that contains
  * the service description (interface) of the Remote Object 
  * and the serializable objects used in parameters and returned types
* the server side that contains
  * one service implementation 
  * and the main class
* the client side that contains 
  * only the main client of the application that invoke the method of remote object
