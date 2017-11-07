
Answer the following questions:
1. What is one benefit of using generics in Java classes?
  - Classes become more flexible. Enable to specify types at the point of instantiation.

2. Name an example of a generic class that we have used in Java?
  - ArrayList
3. What is the syntax for declaring a generic class?
  - Angle brackets e.g. <ArrayList>
4. At what point does the generic type get specified?
  I need clarification on this question so will put both answers.
  - After the class name in the type parameter section e.g. public Account(T id, String name)
  - The type also needs to be put within angle brackets when creating instance of a new class.
5. Can generic types be of primitive type?
  - No, they can be changed at the point of instantiation to primitive types but cannot be primitive themselves. To quote user 'thecoop' from stackoverflow "So, anything that is used as generics has to be convertable to Object ... and the primitive types aren't. So they can't be used in generics."
6. Can a generic class take more than one type parameters?
  - Yes.

