# Terminology-we-use-in-object-oriented-language (C#)
By using these codes as example analyze, and run the console/terminal/command line application and complete or answer the following challenges or questions.

1. **What is a variable?** A variable is a name given to a storage area that our programs can manipulate. Each variable in C# has a specific type, which determines the size and layout of the variable's memory the range of values that can be stored within that memory and the set of operations that can be applied to the variable.

2. Find an example of variable declaration
3. Find an example of variable initialization.
4. Find an example of variable assignment.

5. **What is a method?** A method is a group of statements that together perform a task. Every C# program has at least one class with a method named Main. 
 To use a method, you need to: _Define the method_ and ****_Call the method_****.
 The syntax for defining a method in C# is as follows: 
 
    **<****Access Specifier****>** **<****Return Type****>** **<****Method Name****>(****Parameter List****)**
    **{**
   **Method Body**
    **}**
 
   **Access Specifier** − This determines the visibility of a variable or a method from another class.

   **Return type** − A method may return a value. The return type is the data type of the value the method returns. If the method is not returning any values, then  the     return type is **void**.

   **Method name** − Method name is a unique identifier and it is case sensitive. It cannot be same as any other identifier declared in the class.

   **Parameter list** − Enclosed between parentheses, the parameters are used to pass and receive data from a method. The parameter list refers to the type, order, and     number of the parameters of a method. Parameters are optional; that is, a method may contain no parameters.

    **Method body** − This contains the set of instructions needed to complete the required activity.

6. Find an example of a method signature
7. Find an example of a method parameter.
8. Find an example of a method return type.

9. **What is a class?**: When you define a class, you define a blueprint(a design) for a data type. This does not actually define any data, but it does define what the class name means. Classes are declared by using the **class** keyword followed by a unique identifier.

10. Find an example of a class.
11. Find an example of instantiation.

12. **What is an instance member?**: An instance member is essentially anything within a class that is not marked as static. That is, that it can only be used after an instance of the class has been made (with the **new** keyword). This is because instance members belong to the object, whereas static members belong to the class.

13. Find an example of an instance variable.
14. Find an example of an instance method.

15. **What is a static member?**: We can define class members as static using the static keyword. When we declare a member of a class as static, it means no matter how many objects of the class are created, there is only one copy of the static member.
The keyword static implies that only one instance of the member exists for a class. Static variables are used for defining constants because their values can be retrieved by invoking the class without creating an instance of it. Static variables can be initialized outside the member function or class definition. You can also initialize static variables inside the class definition.

16. Find an example of a static variable.
17. Find an example of a static method.

18. **What is object composition?** Under Composition, if the parent object is deleted, then the child object also loses its status. The composition is a special type of Aggregation and gives a part-of relationship. For example, A Car has an engine. If the car is destroyed, the engine is destroyed as well.

19. Find an example of object composition.

20. **What is overloading/subtype polymorphism?**
The word polymorphism means having many forms. In object-oriented programming paradigm, polymorphism is often expressed as '**_one interface, multiple functions_**'. 
Polymorphism can be _**static _or_ dynamic**_. In static polymorphism, the response to a function is determined at the compile time. In dynamic polymorphism, it is decided at run-time.

21. Find an example of interface implementation.
22. Find an example of a super class.
23. Find an example of a subclass.
24. Find an example of inheritance.
25. Find an example of method overloading.
26. Find an example of a polymorphic call to an overloaded method.

27. **What is type casting?**: Because C# is statically-typed at compile time, after a variable is declared, it cannot be declared again or assigned a value of another type unless that type is implicitly convertible to the variable's type. For example, the string cannot be implicitly converted to int. However, you might sometimes need to copy a value into a variable or method parameter of another type. For example, you might have an integer variable that you need to pass to a method whose parameter is typed as double. Casting is required when information might be lost in the conversion, or when the conversion might not succeed for other reasons.

     Example: _double x = 1234.7;
            int a = (int)x;
            Console.WriteLine(a);   // output: 1234_

28. Find an example of upcasting.
29. Find an example of downcasting.

30. **What is an access modifier?**: An access specifier defines the scope and visibility of a class member. C# supports the following access specifiers:Public,      Private, Protected, Internal and Protected internal.
  Let us define **Encapsulation**: Encapsulation is defined 'as the process of enclosing one or more items within a physical or logical package'. Encapsulation, in    object oriented programming methodology, prevents access to implementation details. Encapsulation is implemented by using **access specifiers**.

31. Find an example of an access modifier.

32. **What is the difference between the access modifiers public, private,
and protected?**: 
   - Public access specifier allows a class to expose its member variables and member functions to other functions and objects. Any public member can be accessed from  outside the class.
   - Private access specifier allows a class to hide its member variables and member functions from other functions and objects. Only functions of the same class can access its private members. Even an instance of a class cannot access its private members.
   - Protected access specifier allows a child class to access the member variables and member functions of its base class. This way it helps in implementing inheritance.   

33. **What are some other forms of polymorphism?**

34. Find an example of method overriding.
35. Find an example of parametric polymorphism (generics).

36. **What is modularity?**: Modular programming is a software design technique that emphasizes separating the functionality of a program into independent, interchangeable modules, such that each contains everything necessary to execute only one aspect of the desired functionality.

37. **What does the application do?**

38. **What does the application print?**

39. **What are some other programs that we could build by composing the
classes of this program in different ways.**
