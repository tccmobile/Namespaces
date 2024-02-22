# Namespaces

* Namespace provide the space where we can define or declare identifier i.e. variable,  method, classes.
* Using namespace, you can define the space or context in which identifiers are defined i.e. variable, method, classes. In essence, a namespace defines a scope.

Advantage of Namespace to avoid name collision.

1. Example, you might be writing some code that has a function called xyz() and there is another library available which is also having same function xyz(). Now the compiler has no way of knowing which version of xyz() function you are referring to within your code.
2. A namespace is designed to overcome this difficulty and is used as additional information to differentiate similar functions, classes, variables etc. with the same name available in different libraries. 
3. The best example of namespace scope is the C++ standard library (std) where all the classes, methods and templates are declared. Hence while writing a C++ program we usually include the directive using namespace std;

**Defining a Namespace:**

A namespace definition begins with the keyword namespace followed by the namespace name as follows:

```
namespace  namespace_name 
{
    // code declarations i.e. variable  (int a;)
    method (void add();)
    classes ( class student{};)
}
```

It is to be noted that, there is no semicolon (;) after the closing brace.
To call the namespace-enabled version of either function or variable, prepend the namespace name as follows:
namespace_name: :code;  // code could be variable , function or class.

[GeeksforGeeks: Namespaces in C++](https://www.geeksforgeeks.org/namespace-in-c/)