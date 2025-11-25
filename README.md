# LLD
## Creational Design Pattern
- It is a category of design patterns in object-oriented programming which focuses on  how the objects are created.
- It helps in hiding the internal implementation of the object initialization.

## Types of Creational Design Patterns
- Singleton
- Factory Method
- Abstract Factory
- Builder
- Prototype

## Singleton Design Pattern
It is a creational design patterns which ensures or restricts a class to have only one instance throughout the application and provides global point of access to it.
Example: Logger,DB Connections
```
public class Logger {
   
    private static Logger instance;

   
    private Logger() {
        // initialization code
    }

   
    public static syncronized Logger getInstance() {
        if (instance == null) {
            instance = new Logger(); 
        }
        return instance;
    }
}
```
## Behavioral Design pattern
It is a category of design patterns which are concerned with algorithms and the assignment of responsibilities between objects.
## Types of behavioral design pattern




