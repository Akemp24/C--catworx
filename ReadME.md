# Notes

## Explore
On the very first line, with the using directive, we're importing a common namespace called System. Much like require or import when using modules in Node.js, in C# the using directive lets us use the corresponding namespace (System) without needing to qualify its use when using one of its members. For example, without this naming shortcut, every time Console is used, it would need to be preceded by System and a period.

### Namespaces

Namespaces are used to organize and provide a level of separation in the code—something like modules in Node.js.

Think of namespaces as containers that have members. A member can be another nested namespace, a method, or a class. After namespace CatWorx.BadgeMaker, everything inside the curly braces can be interpreted as members of that namespace.


### Main

Main() is a very special method that serves as the entry point of the application. The Main() method is invoked when the program runs—and it's where we'll place the code.

In order for Main() to be recognized as the program's entry point, the following syntax guidelines must be followed:

    *Main() must be nested in a class.

    *There can only be one entry point to a program.

    *The keyword void signifies that the return of this executable method will be void.

    *The keyword static implies that the scope of this method is at the class level, not the object level, and can thus be invoked without having to first create a new class instance. Hence the Main() method can be run as soon as the program runs.

## DataTypes
