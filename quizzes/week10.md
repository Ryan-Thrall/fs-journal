# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
 - namespace helps the computer know where you are in your file structure and for finding files when they're needed somewhere else in the project.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
 - structs are light versions of classes that can be used to create objects but are limited to built in types.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
 - void
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
 - public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
 - the return type.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
 - abstract prevents Car from being instantiated on it's own and can only be used in other not abstract classes.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
 - Virtual allows the variable to be overridden elsewhere
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
 - public, private, internal, protected
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
 - Private methods can only be accessed by the class they're in and classes can't be referenced outside the class objects.
```