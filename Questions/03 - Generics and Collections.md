# Reviewing OCA Collections & Working with Generics


1. Which of the following statements is true about arrays and ArrayLists in Java's Collection Framework?
   a) An array can contain both primitives and objects, while an ArrayList can only contain objects.
   b) An ArrayList is a built-in data structure, while an array is an object that contains other objects or primitives.
   c) Arrays and ArrayLists are interchangeable in Java without any conversions.
   d) ArrayLists are always resizable, whereas arrays are not.

2. What happens when you try to remove an element from a List created using `Arrays.asList(array)` using the `remove` method?
   a) It removes the element successfully.
   b) It throws a `NullPointerException`.
   c) It throws an `UnsupportedOperationException`.
   d) It depends on the type of elements in the list.

3. In Java, which sorting algorithm does the `Arrays.sort` method use?
   a) QuickSort
   b) MergeSort
   c) BubbleSort
   d) SelectionSort

4. What does the term "autoboxing" refer to in Java?
   a) Converting an object to a primitive data type.
   b) Converting a primitive data type to its corresponding wrapper class.
   c) Converting between different wrapper classes.
   d) Converting an ArrayList to an array.

5. When does autoboxing and unboxing occur in Java?
   a) Only during compilation.
   b) Only during runtime.
   c) Both during compilation and runtime as needed.
   d) Autoboxing occurs during compilation, and unboxing occurs during runtime.

6. What is the purpose of the diamond operator (`<>`) in Java, as shown in the example?
   a) It represents a wildcard in generic type declarations.
   b) It signifies the start of a comment in Java code.
   c) It denotes a placeholder for an unknown type in a generic class or method.
   d) It represents the multiplication operator in Java.

7. Which of the following statements about generics in Java is NOT true?
   a) Generics provide compile-time type safety.
   b) Generics allow you to create classes and methods that operate on types as parameters.
   c) Generics are only applicable to collections and not to other parts of Java.
   d) Generics can be used to specify the type of elements in a collection, among other things.

8. What does "type erasure" refer to in the context of Java generics?
   a) It refers to the automatic conversion of generic types to their raw types at runtime.
   b) It is a feature in Java that allows you to erase the type of a variable during runtime.
   c) It refers to the process of removing generic type information from a generic class or method during compilation.
   d) It is a runtime error that occurs when working with generic types.

9. Which of the following statements is true about upper-bounded wildcards in Java?
   a) They allow you to specify that any type is acceptable.
   b) They restrict the types that can be used in a generic parameter.
   c) They are denoted by the `extends` keyword.
   d) They make a list immutable and prevent any modifications.

10. In Java, what is the purpose of lower-bounded wildcards?
    a) To allow any type to be used in a generic parameter.
    b) To restrict the types that can be used in a generic parameter.
    c) To make a list immutable and prevent any modifications.
    d) To specify the exact type that must be used in a generic parameter.

11. Which of the following method declarations is valid in Java?
    a) `<? extends T> T method(List<? extends T> list)`
    b) `<B extends A> B method(List<B> list)`
    c) `<?> <? extends T> method(List<? extends T> list)`
    d) `<T> <? extends T> method(List<T> list)`

12. When working with generics in Java, what is the purpose of using the wildcard `?` without any bounds?
    a) It indicates that the generic type can be any type.
    b) It specifies a lower bound for the generic type.
    c) It restricts the generic type to a specific type.
    d) It is not a valid use of wildcards in generics.


13. What is the main purpose of using a lower-bounded wildcard in Java generics?
    a) To specify that any type is acceptable.
    b) To restrict the types that can be used in a generic parameter.
    c) To make a list immutable and prevent any modifications.
    d) To specify the exact type that must be used in a generic parameter.

14. In the context of Java generics, what is "type erasure"?
    a) A mechanism to automatically convert generic types to their raw types at runtime.
    b) The process of removing generic type information from a generic class or method during compilation.
    c) A runtime error that occurs when working with generic types.
    d) The ability to erase the type of a variable during runtime.

15. Which of the following statements is true about the diamond operator (`<>`) in Java?
    a) It represents a wildcard in generic type declarations.
    b) It signifies the multiplication operator in Java.
    c) It is used to specify a known type for a generic class or method.
    d) It is only applicable to collections and not to other parts of Java.

16. What happens when you attempt to add an element of type `Exception` to a `List<? super IOException>`?
    a) It compiles successfully and adds the element.
    b) It throws a `NullPointerException`.
    c) It throws an `UnsupportedOperationException`.
    d) It depends on the specific types involved and may or may not compile.

17. Which of the following scenarios demonstrates the use of autoboxing in Java?
    a) Converting a `List<Integer>` to a `List<Object>`.
    b) Converting an `int` primitive to an `Integer` object.
    c) Converting an `ArrayList<String>` to an array of strings.
    d) Converting a `List<Object>` to a `List<Integer>`.

18. When working with Java generics, what does the upper-bounded wildcard `<? extends T>` indicate?
    a) It allows any type to be used as a generic parameter.
    b) It restricts the types that can be used as generic parameters.
    c) It specifies that the list is immutable and cannot be modified.
    d) It denotes a placeholder for an unknown type in a generic class or method.

19. In Java, what is the purpose of using generics with a lower-bounded wildcard (`<? super T>`)?
    a) To allow any type to be used as a generic parameter.
    b) To specify that the list is immutable and cannot be modified.
    c) To restrict the types that can be used as generic parameters.
    d) To specify the exact type that must be used as a generic parameter.

20. Which of the following statements is true about generic types and their inheritance in Java?
    a) A generic class can inherit from a non-generic class.
    b) A generic class cannot inherit from a non-generic class.
    c) A generic class can only inherit from another generic class.
    d) Inheritance between generic and non-generic classes is not allowed in Java.

21. When using a generic method in Java, where is the formal type parameter typically declared?
    a) Immediately before the method's return type.
    b) Immediately before the method's name.
    c) Inside the method's implementation.
    d) In the method's parameter list.

22. Which of the following scenarios demonstrates a usage of generics in Java?
    a) Defining a class with multiple constructors.
    b) Implementing an interface with multiple methods.
    c) Writing a method that works with different types using type parameters.
    d) Creating an array with a fixed size.

23. In Java, what is the main difference between an array and an ArrayList?
    a) Arrays are resizable, while ArrayLists have a fixed size.
    b) Arrays can store both primitives and objects, while ArrayLists can only store objects.
    c) Arrays can be used with generics, while ArrayLists cannot.
    d) Arrays can have elements of different types, while ArrayLists require consistent types.

24. Which of the following statements regarding autoboxing and unboxing in Java is true?
    a) Autoboxing converts a wrapper class to a primitive type, while unboxing converts a primitive type to a wrapper class.
    b) Autoboxing and unboxing are the same operations in Java.
    c) Autoboxing converts a primitive type to a wrapper class, while unboxing converts a wrapper class to a primitive type.
    d) Autoboxing and unboxing are not supported in Java.

25. What does the term "type safety" mean in the context of Java generics?
    a) The ability to use wildcard types for any purpose.
    b) Ensuring that all objects in a collection belong to the same type.
    c) Preventing the use of generic types in Java programs.
    d) Ensuring that the types of objects used in generics are compatible to avoid runtime errors.

26. Which of the following scenarios demonstrates the use of a lower-bounded wildcard (`<? super T>`) in Java generics?
    a) Declaring a method that accepts any type as an argument.
    b) Specifying that a list should only contain elements of a specific type.
    c) Allowing a list to store elements of any type without restrictions.
    d) Ensuring that a list can be used to store objects of a superclass of `T`.

27. In Java, what does the term "upper-bounded wildcard" (`<? extends T>`) imply when used in generics?
    a) It allows any type to be used as a generic parameter.
    b) It restricts the types that can be used as generic parameters.
    c) It specifies that the list is immutable and cannot be modified.
    d) It denotes a placeholder for an unknown type in a generic class or method.

28. Which of the following is NOT a valid scenario for using generics in Java?
    a) Creating a class that works with different data types using type parameters.
    b) Specifying the type of elements in a collection to ensure type safety.
    c) Implementing an interface with generic methods.
    d) Declaring a method that accepts an array of any type.

29. What does "type erasure" mean in the context of Java generics?
    a) The process of converting a generic type to its raw type at runtime.
    b) The ability to remove the type of an object during runtime.
    c) A mechanism for enforcing strict type checking in generic code.
    d) The process of converting a primitive type to its wrapper class.

30. Which of the following is a valid reason for using the diamond operator (`<>`) in Java generics?
    a) To represent an unknown type in a generic class.
    b) To specify that any type is acceptable in a generic method.
    c) To specify the exact type that must be used in a generic parameter.
    d) To indicate the multiplication operator in Java.

# Using Lists, Sets, Maps, and Queues & Comparator vs. Comparable

1. What is the main difference between a List and a Set in the Java Collections Framework?
   a) Lists allow duplicate elements, while Sets do not.
   b) Sets allow elements to be accessed by index, while Lists do not.
   c) Lists are unordered collections, while Sets are ordered collections.
   d) Sets can store both primitives and objects, while Lists can only store objects.

2. Which collection type is suitable when you need to maintain elements in a specific order and allow duplicates?
   a) List
   b) Set
   c) Queue
   d) Map

3. What is the primary purpose of a Queue in Java?
   a) To store elements in a random order.
   b) To allow duplicate elements.
   c) To order elements based on their natural order.
   d) To order elements for processing in a specific order, such as FIFO.

4. Which of the following data structures is not part of the Java Collections Framework?
   a) ArrayList
   b) HashMap
   c) ArrayDeque
   d) Stack

5. Which collection type is used to map keys to values in Java?
   a) List
   b) Set
   c) Queue
   d) Map

6. What is the primary benefit of using a TreeMap over a HashMap in Java?
   a) TreeMap allows duplicate keys.
   b) TreeMap maintains elements in insertion order.
   c) TreeMap guarantees that keys are sorted.
   d) TreeMap is more memory-efficient than HashMap.

7. When implementing the Comparable interface in a class, which method must be overridden?
   a) equals()
   b) hashCode()
   c) compareTo()
   d) toString()

8. Which collection interface in Java does not extend the Collection interface?
   a) List
   b) Set
   c) Queue
   d) Map

9. What is the purpose of a Comparator in Java?
   a) To define the natural ordering of elements in a class.
   b) To allow elements to be accessed by index in a collection.
   c) To specify a custom ordering of elements for sorting.
   d) To check if a collection is empty or not.

10. Which of the following collection types does not allow null elements?
    a) ArrayList
    b) HashSet
    c) ArrayDeque
    d) TreeMap


11. What is the primary benefit of using a HashSet over a TreeSet in Java?
    a) HashSet allows duplicate elements.
    b) HashSet maintains elements in sorted order.
    c) HashSet provides constant-time access to elements.
    d) HashSet is more memory-efficient than TreeSet.

12. Which method is used to remove a specific element from a collection in the Java Collections Framework?
    a) clear()
    b) remove()
    c) delete()
    d) discard()

13. What is the purpose of the clear() method in a collection?
    a) To check if a collection is empty.
    b) To remove the first element from the collection.
    c) To remove all elements from the collection.
    d) To retrieve the number of elements in the collection.

14. Which of the following methods is used to check if a specific element is present in a collection?
    a) contains()
    b) includes()
    c) exists()
    d) containsElement()

15. In the context of sorting, what does "FIFO" stand for?
    a) First-In First-Out
    b) First-Index First-Order
    c) Fast-In Fast-Out
    d) First-Iteration First-Out

16. Which collection type allows elements to be added or removed from both the front and back of the collection?
    a) ArrayList
    b) LinkedList
    c) HashSet
    d) TreeMap

17. When implementing the Comparable interface, which data type should the compareTo() method return?
    a) int
    b) boolean
    c) String
    d) Object

18. Which of the following collection types is not synchronized and not thread-safe?
    a) ArrayList
    b) Hashtable
    c) LinkedList
    d) TreeSet

19. In the Java Collections Framework, which collection type guarantees that keys are unique?
    a) List
    b) Set
    c) Queue
    d) Map

20. What is the primary purpose of a Map in Java?
    a) To store elements in a specific order.
    b) To allow duplicate elements.
    c) To map keys to values.
    d) To order elements for processing.

21. Which Java interface represents a collection that maintains a sorted order of its elements?
    a) Set
    b) List
    c) SortedSet
    d) Queue

22. In the context of collections, what does "LIFO" stand for?
    a) Last-In Last-Out
    b) Last-Index First-Out
    c) Latest-In First-Out
    d) Low-In First-Out

23. What is the primary difference between a HashSet and a LinkedHashSet in Java?
    a) HashSet allows duplicate elements, while LinkedHashSet does not.
    b) LinkedHashSet maintains elements in the order they were inserted.
    c) HashSet allows constant-time access to elements, while LinkedHashSet does not.
    d) LinkedHashSet is more memory-efficient than HashSet.

24. Which of the following is NOT a valid method for checking if a collection is empty?
    a) isEmpty()
    b) size()
    c) hasElements()
    d) sizeOf()

25. When implementing the Comparable interface in a custom class, which method must be overridden?
    a) equals()
    b) hashCode()
    c) compareTo()
    d) toString()

26. Which collection type is suitable for implementing a queue with FIFO (First-In First-Out) behavior?
    a) ArrayList
    b) LinkedList
    c) HashSet
    d) TreeMap

27. What is the primary purpose of the Comparator interface in Java?
    a) To compare objects for equality.
    b) To sort elements in a collection based on their natural order.
    c) To provide a custom sorting order for objects.
    d) To check if an element exists in a collection.

28. Which of the following collection types allows duplicate elements but does not maintain their order?
    a) Set
    b) List
    c) Map
    d) Queue

29. In a TreeMap, how are elements sorted by default?
    a) In the order they were inserted.
    b) In ascending numerical order.
    c) In alphabetical order of keys.
    d) In descending order of values.

30. Which collection type in Java is typically used to implement a stack?
    a) ArrayList
    b) Stack
    c) HashSet
    d) TreeMap



# Searching and Sorting & Additions in Java 8

1. What does the `compareTo()` method do in Java when used for sorting objects?
    a) It checks if two objects are equal.
    b) It compares two objects and returns a boolean.
    c) It compares two objects and returns an integer.
    d) It checks if two objects are of the same type.

2. Why does the code `Collection.sort(rabbits);` in Java fail to compile in the given example?
    a) The `Collection` class doesn't have a `sort` method.
    b) The `compareTo()` method is missing in the `Rabbit` class.
    c) The `Rabbit` class doesn't implement the `Comparable` interface.
    d) The `Comparator` is not defined for the `rabbits` collection.

3. In Java, which interface allows you to provide a custom sorting order for objects without modifying their class?
    a) Comparable
    b) Comparator
    c) Sortable
    d) Comparer

4. When using the `sort()` method in Java, what is a common use case for providing a custom `Comparator`?
    a) To check if the collection is empty.
    b) To define a natural sorting order for objects.
    c) To specify a sorting order that is different from the object's natural order.
    d) To add elements to the collection.

5. In Java, which of the following collections allow you to pass a custom `Comparator` for sorting?
    a) ArrayList
    b) HashSet
    c) TreeSet
    d) LinkedList

6. When using a `TreeSet` in Java, which of the following statements is true?
    a) All objects added to the set must implement the `Comparable` interface.
    b) All objects added to the set must provide a custom `Comparator`.
    c) A `TreeSet` can store objects of any type without restrictions.
    d) A `TreeSet` only accepts objects of the same class as the set.

7. What exception is thrown when attempting to add objects to a `TreeSet` that do not implement the `Comparable` interface or provide a custom `Comparator`?
    a) NullPointerException
    b) ClassCastException
    c) IllegalArgumentException
    d) UnsupportedOperationException

8. In Java, which interface allows you to define custom sorting for a class without modifying the class itself?
    a) Sortable
    b) SortingOrder
    c) Comparator
    d) Comparable

9. What does the `Comparator` interface in Java require you to implement?
    a) The `compare()` method.
    b) The `equals()` method.
    c) The `hashCode()` method.
    d) The `toString()` method.

10. In Java 8, what new features were introduced to improve collections and stream processing?
    a) Generics
    b) Lambda expressions
    c) Method references
    d) Enumerations


11. In Java, what does the `equals()` method in the `Comparable` interface allow you to compare?
    a) Two objects' memory addresses.
    b) Two objects' instance variables.
    c) Two objects' types.
    d) Two objects' natural ordering.

12. Which of the following is true about the `Comparator` interface in Java?
    a) It is defined in the `java.util` package.
    b) It contains only one method, `compare()`.
    c) It can be used to modify the internal state of objects.
    d) It is only used for sorting collections.

13. What is a lambda expression in Java?
    a) A way to declare a variable with multiple types.
    b) A block of code that defines a new class.
    c) A concise way to represent an anonymous function.
    d) A predefined function available in the Java library.

14. In Java 8, which functional interface represents a function that accepts two arguments and produces a result?
    a) `Function`
    b) `Predicate`
    c) `BiFunction`
    d) `Consumer`

15. What is the purpose of the `Stream` API introduced in Java 8?
    a) To create custom exceptions for handling streams.
    b) To provide a way to read and write files.
    c) To work with sequences of data and perform operations on them.
    d) To define custom sorting orders for collections.

16. Which Java 8 feature allows you to iterate through a collection and apply a function to each element?
    a) Lambda expressions
    b) Stream API
    c) Comparator
    d) Comparable

17. In Java 8, what method is used to perform a terminal operation on a `Stream` and collect the elements into a collection?
    a) `map()`
    b) `filter()`
    c) `forEach()`
    d) `collect()`

18. Which of the following is NOT a terminal operation in the Java 8 `Stream` API?
    a) `map()`
    b) `forEach()`
    c) `reduce()`
    d) `collect()`

19. What is the purpose of method references in Java 8?
    a) To reference methods within anonymous inner classes.
    b) To create new methods dynamically at runtime.
    c) To simplify the syntax of lambda expressions for existing methods.
    d) To call private methods from outside the class.

20. In Java 8, what interface represents a function that takes no arguments and returns a result?
    a) `Function`
    b) `Supplier`
    c) `Consumer`
    d) `Predicate`


21. Which of the following is NOT a valid primitive data type in Java?
    a) int
    b) float
    c) boolean
    d) string

22. What is the result of the following code snippet?
   
   ```java
   int x = 5;
   int y = x++;
   ```

   a) `x` is assigned the value 6, and `y` is assigned the value 5.
   b) `x` is assigned the value 5, and `y` is assigned the value 6.
   c) Both `x` and `y` are assigned the value 5.
   d) The code contains a compilation error.

23. In Java, what is the purpose of the `break` statement in a loop?
    a) To terminate the program.
    b) To skip the current iteration of the loop and continue with the next.
    c) To restart the loop from the beginning.
    d) To check a condition before each iteration.

24. Which access modifier allows a class or method to be accessed from any other class in any package?
    a) `public`
    b) `private`
    c) `protected`
    d) `default` (no modifier)

25. What is the output of the following code snippet?

    ```java
    String str1 = "Java";
    String str2 = new String("Java");
    System.out.println(str1 == str2);
    ```

    a) true
    b) false
    c) It will result in a compilation error.
    d) It will throw a runtime exception.

26. Which Java keyword is used to declare a method that does not return any value?
    a) `void`
    b) `null`
    c) `return`
    d) `none`

27. What is the primary purpose of an interface in Java?
    a) To provide a concrete implementation of methods.
    b) To represent a class that cannot be instantiated.
    c) To define a contract of methods that implementing classes must adhere to.
    d) To restrict access to certain class members.

28. Which of the following is a correct way to create a multi-threaded Java program?
    a) Create a subclass of `Thread` and implement the `run()` method.
    b) Implement the `Runnable` interface and pass an instance to a `Thread` constructor.
    c) Use the `sync()` keyword to indicate multi-threading.
    d) Use the `await()` method to pause a thread.

29. In Java, what is the purpose of the `finally` block in a try-catch-finally construct?
    a) To catch and handle exceptions.
    b) To define the main logic of the code.
    c) To ensure that a block of code is always executed, whether or not an exception occurs.
    d) To specify conditions for branching in a switch statement.

30. Which of the following collections in Java does NOT allow duplicate elements?
    a) `ArrayList`
    b) `HashSet`
    c) `LinkedList`
    d) `TreeSet`

# Using New Java 8 Map APIs

31. What is the purpose of the `putIfAbsent` method in the `Map` interface in Java?
    a) It always replaces the existing value for a given key.
    b) It updates the value for a key only if the key is not already associated with a non-null value.
    c) It removes the specified key from the map.
    d) It retrieves the value associated with the key, or a default value if the key is absent.

32. Which Java 8 Map API method allows you to apply a custom mapping function to decide which value to keep when updating an existing key-value pair?
    a) `put`
    b) `merge`
    c) `computeIfPresent`
    d) `computeIfAbsent`

33. Consider the following code snippet:

    ```java
    Map<String, String> favorites = new HashMap<>();
    favorites.put("Jenny", "Bus Tour");
    favorites.put("Tom", "Tram");

    String result = favorites.merge("Jenny", "Skyride", (v1, v2) -> v1.length() > v2.length() ? v1 : v2);
    ```

    What is the value of `result` after executing this code?
    a) "Bus Tour"
    b) "Skyride"
    c) "Tram"
    d) "Tom"

34. What is the primary purpose of the `BiFunction` used with the `merge` method in the `Map` interface?
    a) To specify a default value for a key if it doesn't exist.
    b) To remove a key from the map.
    c) To provide a mapping function that decides which value to keep when updating an existing key-value pair.
    d) To retrieve the value associated with a key.

35. When does the `mappingFunction` provided to the `merge` method get invoked in Java 8?
    a) Whenever the key is present in the map.
    b) Whenever the key is absent in the map.
    c) Only when there are two actual values to decide between.
    d) Always, regardless of the key's presence.

36. Which Java 8 Map API methods are NOT part of the OCP (Oracle Certified Professional) objectives but are included in the upgrade exam objectives?
    a) `putIfAbsent`
    b) `merge`
    c) `computeIfPresent` and `computeIfAbsent`
    d) `put`

37. What happens when the `mappingFunction` provided to the `merge` method returns `null` in Java?
    a) The key-value pair is removed from the map.
    b) The key's value remains unchanged.
    c) An exception is thrown.
    d) The key's value is replaced with an empty string.

38. Which of the following Map API methods in Java 8 is used to apply a custom mapping function only when the requested key is found in the map?
    a) `putIfAbsent`
    b) `computeIfAbsent`
    c) `put`
    d) `computeIfPresent`

It seems like you want more questions related to Java 8 Map APIs. Here are some additional multiple-choice questions:

39. What is the purpose of the `computeIfPresent` method in the `Map` interface in Java 8?
    a) It replaces the existing value for a given key.
    b) It computes a new value for a key only if the key is not already associated with a non-null value.
    c) It removes the specified key from the map.
    d) It retrieves the value associated with the key or computes a new value if the key is present.

40. Which of the following statements is true about the `computeIfAbsent` method in Java 8's `Map` interface?
    a) It always replaces the existing value for a given key.
    b) It computes a new value for a key only if the key is not already associated with a non-null value.
    c) It removes the specified key from the map.
    d) It retrieves the value associated with the key or computes a new value if the key is absent.

41. Consider the following code snippet:

    ```java
    Map<String, String> favorites = new HashMap<>();
    favorites.put("Jenny", "Bus Tour");
    favorites.put("Tom", "Tram");

    String result = favorites.computeIfAbsent("Sam", k -> "Skyride");
    ```

    What is the value of `result` after executing this code?
    a) "Bus Tour"
    b) "Skyride"
    c) "Tram"
    d) "Sam"

42. Which Java 8 Map API method allows you to compute a new value for a key only if the key is already present in the map?
    a) `put`
    b) `computeIfPresent`
    c) `computeIfAbsent`
    d) `merge`

43. When using the `computeIfPresent` and `computeIfAbsent` methods in Java 8, under what conditions will the provided mapping function be invoked?
    a) Whenever the key is present in the map.
    b) Whenever the key is absent in the map.
    c) Only when there are two actual values to decide between.
    d) Always, regardless of the key's presence.

44. What is the primary purpose of the `mappingFunction` used with the `computeIfAbsent` method in the `Map` interface?
    a) To specify a default value for a key if it doesn't exist.
    b) To remove a key from the map.
    c) To provide a mapping function that computes and assigns a value to a key when it is absent.
    d) To retrieve the value associated with a key.

45. When using the `computeIfAbsent` method in Java 8, what happens if the key is already present in the map?
    a) The key is removed from the map.
    b) The provided mapping function is called to compute a new value.
    c) The key's value remains unchanged.
    d) An exception is thrown.

46. Which Java 8 Map API method is used to compute a new value for a key and replace the existing value with the computed value?
    a) `put`
    b) `computeIfPresent`
    c) `computeIfAbsent`
    d) `merge`

47. What is the primary purpose of the `merge` method in the Java 8 `Map` interface?
    a) It adds a new key-value pair to the map.
    b) It updates the value for a specific key if the key already exists in the map.
    c) It removes a key-value pair from the map.
    d) It retrieves the value associated with a key.

48. When using the `merge` method in Java 8 with a mapping function, under what conditions will the mapping function be invoked?
    a) Whenever the key is present in the map.
    b) Whenever the key is absent in the map.
    c) Only when there are two actual values to decide between.
    d) Always, regardless of the key's presence.

49. Consider the following code snippet:

    ```java
    Map<String, Integer> scores = new HashMap<>();
    scores.put("Alice", 100);
    scores.put("Bob", 85);

    scores.merge("Alice", 10, (oldScore, newScore) -> oldScore + newScore);
    ```

    What is the value associated with the key "Alice" after executing this code?
    a) 100
    b) 110
    c) 10
    d) 85

50. Which Java 8 Map API method is used to add a key-value pair to the map only if the key is not already present?
    a) `put`
    b) `computeIfPresent`
    c) `computeIfAbsent`
    d) `merge`

51. What happens when you use the `computeIfAbsent` method in Java 8 to compute a new value for an existing key, but the mapping function returns `null`?
    a) The key is removed from the map.
    b) The mapping function is called again until a non-null value is returned.
    c) An exception is thrown.
    d) The key's value remains unchanged.

52. Which of the following methods can be used to both add a new key-value pair to a map and replace the value for an existing key if it already exists?
    a) `put`
    b) `merge`
    c) `computeIfAbsent`
    d) `computeIfPresent`

53. In the `computeIfAbsent` method of the `Map` interface, what is the purpose of the provided mapping function?
    a) To remove a key from the map.
    b) To specify a default value for a key if it doesn't exist.
    c) To provide a mapping function that computes and assigns a value to a key when it is absent.
    d) To retrieve the value associated with a key.

54. When using the `merge` method in Java 8, what happens if the mapping function returns `null`?
    a) The key is removed from the map.
    b) The existing value for the key remains unchanged.
    c) An exception is thrown.
    d) The mapping function is called again until a non-null value is returned.

55. Which Java 8 Map API method allows you to specify a default value for a key if it doesn't exist, and replace the value for an existing key?
    a) `put`
    b) `computeIfAbsent`
    c) `computeIfPresent`
    d) `merge`


