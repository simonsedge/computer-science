# "Computer Science For Dummies"

2 goals with this repo:
- connect a great majority of relevant computer science concepts
- explain each concept in 2 different ways (analogy/simplistic + technical/definition)

## how 99 concepts connect with each other

1. Turing machine
   - a computer is a piece of tape with 0s and 1s along with a device that can read and write the tape. should be able to compute any algorithm
   - a mathematical model of computation that defines an abstract machine which manipulates symbols on a strip of tape acc. to a set of rules. helps understand the limits of what can be computed.
  
2. CPU (central processing unit)
   - the core of modern computers. has a piece of silicon that contains billions of tiny transistors
   - the primary component of a computer that performs most of the processing. it executes instructions from programs by performing basic arithmetic, logic, control, and input/output operations.
  
3. Transistors
   - like microscopic on-off switches for which each switch has a value called a bit
   - semiconductor devices used to amplify or switch electronic signals. the fundamental building blocks of modern electronic devices, including CPUs
  
4. Bit
   - smallest unit of information a computer can use
   - as info is typically complex, it comes in a pack of 8 combinational bits = byte = 2^8 combinations = 256 combinations
  
5. ASCII
   - ASCII is a character encoding standard that assigns a number to each character (letters, digits, punctuation) to represent text in computers

6. UTF-8
   - (8-bit Unicode Transformation Format) is a character encoding capable of encoding all possible characters in Unicode. It is widely used on the web and is compatible with ASCII for characters     in the 0-127 range
  
7. Binary (0/1)
   - a system for counting like the base10 system when counting on my fingers
   - so binary is just a base2 system where each possible bit value in a pack is multiplied by the correspondent bit placement value in the pack (01111011 = 0x128 + 1*64 + ... + 1x2 + 1x1)
   - base-2 numeral system that uses only two digits, 0 and 1. it is the fundamental language of computers, with all data processed as combinations of binary digits (bits).
  
8. Hexadecimal
   - a system for counting like binary but more human appropriate since we're not digital calculators to read binary
   - so hexadecimal is a base16 system of 01234565789abcdef (10 numbers and 6 letters)
   - a base-16 numeral system using 16 symbols: 0-9 and A-F. It is often used in computing to represent binary data in a more compact and readable form.
  
9. Nibble
   - 4bit group
   - A nibble is a group of four bits, or half of a byte (which is 8 bits). It can represent a single hexadecimal digit.
  
10. Machine code
   - cpu can decode and execute the binary format in the machine code
   - it does not store data for my applications though, that's below
   - the lowest-level programming language, consisting of binary instructions that are directly executed by a computer's CPU. each instruction performs a very specific operation.
  
11. RAM
   - Random Access Memory (RAM) is like a high end slum in which a byte lives in every house. and the address to every house is the definition below.
   - a type of computer memory that can be accessed randomly and is used for storing working data and machine code.
   - RAM + CPU are the brain of the computer. Data is fetched from RAM, CPU decodes control unit, CPU executes arithmetic logic unit, RAM stores overwriten data

11. Memory Address
   - the address of every byte in the RAM slum
   - A memory address is a reference to a specific memory location used to store and retrieve data in a computer's memory.

12. I/O
   - in order for the RAM + CPU brain to be used, needs to handle input and output. An input device can be the keyboard, the output device the monitor
   - Input/Output (I/O) refers to the communication between a computer system and the external world, including devices like keyboards, monitors, and printers.

13. Kernels
   - the reason why programmers dont have to worry about how all the CPU + RAM + I/O fit together. its like operating systems inside OSs (MacOs, windows, linux) that manage hardware resources via     device drivers
   - the kernel is the core component of an operating system, managing system resources, and facilitating communication between hardware and software.

14. Shell
   - if i wanted to start hacking on the operating system, the shell is the first entry point. it's a program that exposes the operating system (say kernel) to the end user. it takes a line of text as input and produces an output in the CLI
   - A shell is a command-line interface that allows users to interact with the operating system by typing commands. it's called a shell because it wraps the kernel.

15. Command Line Interface
   - its a text-based interface where users enter commands to perform specific tasks within an operating system

16. Secure Shell Protocol
   - secure shell (SSH) is a network protocol that allows secure remote login and command execution over a network in the comfort of my CLI

17. Mainframe
   - with SSH i could connect my CLI to a mainframe if i had hacked it or the org gave me access to it
   - a mainframe is a high-performance computer used primarily by large organizations for critical applications, bulk data processing, and enterprise-level computing.

18. Programming Language
   - a tool that uses the abstraction principle to make computers practical to work with for humans by simplifying different systems layer by layer
   - a programming language is a formal language used to write instructions that a computer can execute.

19. Abstraction Principle
   - the abstraction principle involves reducing complexity by hiding the irrelevant details and exposing only essential features.

20. Interpreted Language
   - Interpreted languages are programming languages that are executed line-by-line by an interpreter program rather than being compiled into machine code first.
   - like python

21. Compiled Language
   - Compiled languages are programming languages whose code is translated into machine language (executable code) by a compiler before being run (as in cpu attempts to execute it).
   - like c++

22. Executable
   - the result of a compiled language file is an .exe file that can be run by the operating system without any extra dependencies
   - an executable is a file containing a program that is ready to be executed by a computer.

23. Data Types
   - string, bitmap, bitfield, hash, list, set, sorted set, geospatial, hyperlog, stream, etc...
   - data types available are different in every programming language
   - Data types define the kind of data that can be stored and manipulated within a program, such as integers, strings, and booleans.

24. Variable
   - the most fundamental way to use data in software is to declare a variable and store the data there.
   - A variable is a named storage location in a program that can hold data and be modified during execution.

25. Dynamically Typed Language
   - we dont need to tell the program which data type is assigned to each variable (like it already knows a number data type is an integer, human language is a string, etc)
   - dynamically typed languages determine the type of a variable at runtime rather than at compile-time.

26. Statically Typed Language
   - Statically typed languages require the programmer to declare variable types at compile-time, ensuring type safety.

27. Pointer
   - when i define a variable and store data in it, the data is stored somewhere in RAM and i may need to allocate and free up memory resources throughout the software
   - A pointer is a variable that stores the memory address of another variable, allowing indirect access to data. can be used for low-level memory control
   - many languages dont want to deal with low level memory management and instead implement a garbage collector (see below)

28. Garbage Collection
   - Garbage collection is a form of automatic memory management that reclaims memory occupied by objects no longer in use (no longer referenced in the software)

29. Int
   - An integer (int) is a data type representing whole numbers without fractions, can be signed or unsigned

30. Signed
   - Signed data types can represent both positive and negative numbers, using one bit to denote the sign.

31. Floating Point
   - its called a float because theres only enough memory to represent a certain range of numbers at a certain precision and is basically a form of scientific notation to make computers faster. if i need more range or precision many languages have the double data type
   - A floating-point number is a data type used to represent real numbers with decimal points.

32. Double
   - A double is a floating-point data type that offers double the precision of a standard float.

33. Char
   - A char (character) is a data type used to represent individual characters, typically stored as a numeric value.

34. String
   - A string is a sequence of characters used to represent text in a program.

35. Big Endian
   - ultimately the data types above get stored in a memory address somewhere in RAM but they need to be stored in a certain order. when the order starts with the most significant byte in the smallest memory address its called big endian
   - Big-endian refers to a system of storing the most significant byte of data at the lowest memory address.

36. Little Endian
   - Little-endian is a system of storing the least significant byte of data at the lowest memory address.

37. Data Structures
   - Data structures are ways of organizing and storing data to enable efficient access and modification. examples below

38. Array
   - probablyh the most useful data structure. its like a shopping list as it organizes multiple data points in order, maintaining an index of integers for each item (although for a list you dont need an index)
   - An array is a collection of elements, all of the same type, stored in contiguous memory locations.

39. Linked List
   - each item has a pointer to the next item
   - A linked list is a data structure consisting of nodes, where each node contains data and a reference to the next node in the sequence.

40. Stack
   - stacking a bunch of plates on top of one another and if i want to pop one out i gotta pop the top place first
   - A stack is a data structure that follows a Last In, First Out (LIFO) order for adding and removing elements.

41. Queue
   - literally a fucking queue. you get out first if you get in first.
   - A queue is a data structure that follows a First In, First Out (FIFO) order for adding and removing elements.

42. Hash == Map == Dictionary
   - another useful data structure. like an array but instead of an index of integers i define the keys that point to each individual item, giving me a collection of key value pairs. in many cases tho its not efficient to organize the data in a linear way, hence we have trees (see below)
   - A hash is a function that converts input into a fixed-size string or number, often used for indexing data in hash tables.

43. Tree
   - organizes nodes together in a non linear (hierarchy) that can often be traversed more quickly. but even this can sometimes be too rigid of a data structure so i can create a graph
   - A tree is a hierarchical data structure consisting of nodes, with a single root and branches leading to child nodes.

44. Graph
   - A graph is a data structure consisting of vertices (nodes) and edges that represent connections between multiple nodes in a virtually unlimited number of ways
   - has a node for the data and an edge for the relationship between the data points
   - now data structures in general are essential but they're just ways to structure stored data so they dont do anything by themselves

45. Edge
   - In a graph, an edge represents a connection or relationship between two nodes.

46. Algorithm
   - An algorithm is a step-by-step procedure for solving a problem or performing a task in whatever language

47. Function
   - one of many and one of the most fundamental mechanism for implementing algorithms that takes an input and returns an output. can be called outside the block of code and accepts arguments as inputs
   - A function is a reusable block of code that performs a specific task and can be called with parameters to execute.

48. Return
   - The return statement in a function is used to exit the function and send a value back to the calling context.

49. Arguments
   - Arguments are values passed to a function when it is called, used as input for the function's execution.

50. Operators
   - one thing i may do inside a function is to compare one stored value to another and for that i need operators. each language has its own operators
   - Operators are symbols or keywords used to perform operations on variables and values, such as addition or comparison.

51. Boolean
   - so if in a function i compare 2 stored values, then it forms a value of either true or false (like say i define some function and one line in it is conditional_variable = a > b, that means if a>b then conditional_variable = true)
   - A boolean is a data type that can hold only two possible values: true or false.

52. Expression
   - code that produces a value (like say that conditional_variable = true/flase)
   - An expression is a combination of values, variables, and operators that evaluates to a single value.

53. Statement
   - the opposite of an expression as the line of code does not produce a value (like code "if conditional_variable:" without any =/>/</==/... operator
   - A statement is a single instruction in a program that performs an action.

54. Conditional Logic
   - type of statement still
   - Conditional logic involves using if-else statements to make decisions in a program based on conditions.

55. While Loop
   - another type of statement that iterates block of code over and over until the parenthesis produces a false value (doesnt have to be boolean, false in the sense of "while" condition is no longer met therefore next code iteration is outside the "while" scope
   - A while loop repeatedly executes a block of code as long as a specified condition remains true.

56. Iterable
   - tho the while loop can be useful, more often than not i'll want to loop over an iterable data type like an array.
   - An iterable is an object that can be looped over, such as lists, arrays, or strings.

57. For loop
   - most languages have a for loop that can run some code for every object in the array/iterable data structure
   - A for loop is a control structure used to iterate over a range or collection of elements.

58. Void
   - now in some cases a function may not have an output, so its called a void function (def algo(): return None)
   - Void is a data type used to represent the absence of a value, typically used as a return type for functions that do not return anything.

59. Recursion
   - when a function calls itself like simply writing algo() as in the example above (within or outside block of code). ofc if i call it inside the function and outside as well when the outside call interates its gonna recurse foverever creating an infinite loop ("recursionerror: maximum recursion depth exceeded while calling a Python object")
   - Recursion is a programming technique where a function calls itself in order to solve a problem.

60. Call Stack
   - short term chunk of memory for executing my code - thats why the recursionerror shows. it has a cap on maximum short term storage for function calls so as it keeps pushing frames onto the call stack eventually i will get the maximum depth error
   - The call stack is a data structure that stores information about the active subroutines in a program, including function calls and recursion.

61. Stack Overflow (E)
   - Stack overflow occurs when the call stack exceeds its limit, typically due to deep or infinite recursion.

62. Base Condition
   - basically how to avoid overflow errors. just put a cap on recursion via conditional statements + logic expressions
   - The base condition in a recursive function is the condition that stops the recursion from continuing indefinitely.

63. Big-O-Notation
   - the way to determine if my algorithm is any good. it approximates the performance basically
   - O(log n) is amazing. O(1) is good. O(n) is fair. O(n*log n) is bad. O(n^2), O(2^n), O(n!) are all terrible
   - Big-O notation is a standard format, mathematical representation of the time or space complexity of an algorithm as the input size grows.

64. Time Complexity
   - how fast algorithm will run
   - Time complexity refers to the computational complexity that describes the amount of time it takes for an algorithm to run as a function of the input size.

65. Space Complexity
   - how much memory is required to run the software
   - Space complexity refers to the amount of memory an algorithm requires as a function of the input size.

66. Brute Force
   - one of many algorithm types, the rest will be below
   - Brute force is a problem-solving technique that tries all possible solutions to find the correct one.

67. Divide and Conquer
   - similar to binary search where you cut the problem in halves multiple times according to some criteria to arrive closer and closer to the solution. kinda like how intuitively you search names in a phone book
   - Divide and conquer is an algorithmic technique that breaks a problem down into smaller sub-problems, solves them, and combines their solutions.

68. Dynamic Programming (Nice)
   - how you naturally set goals. you have a tree data structure with the goal on the top and below the top hierarchical node are other goals that in order to be achieved need to have certain nodes below them done first. when you're planning the goals and imagining executing from bottom up it's like you are storing the value of each accomplishment under each branch node just like dynamic programming 
   - Dynamic programming is a method for solving complex problems by breaking them down into simpler subproblems and storing the results of these subproblems to avoid redundant calculations.

69. Memoization
   - the technique responsible for storing the outputs of funtions using a dynamic programming algorithm. so if function has already been called it will use the existing value instead of recomputing it from scratch
   - Memoization is a specific form of dynamic programming where function results are stored to avoid redundant recalculations.

70. Greedy
   - say i have a tree and in each node i have an integer. the goal is to find the node path from top spot to bottom spot for which the sum of the numbers is the greatest value. if greedy algo gets to a point where he has to choose between 2 paths, in this order, (10 then 90) or (20 then 30), he will choose the second option because he doesn't know whats in each 10/20 node after choosing between the 2.
   - Greedy algorithms make the locally optimal choice at each step with the hope of finding a global optimum.

71. Dijkstra's Shortest Path
   - an example of a greedy algorithm
   - Dijkstra's algorithm is used to find the shortest path between two nodes in a graph with non-negative edge weights.

72. Backtracking
   - like how you go about solving ball maze problems as a child. you backtrack from the end until the last mandatory path to get to the end and then explore all options to get there in the first place.
   - Backtracking is a problem-solving technique that involves exploring all possible options and abandoning a solution path if it leads to a dead end.

73. Declarative
   - when it comes to implementing code there are multiple ways and one programming paradigm is declerative where code describes what it does and outcome but doesn't care about things like control flow and its often associated with functional languages
   - Declarative programming focuses on what needs to be done, rather than how to do it, using high-level statements.

74. Functional Languages
   - like haskell
   - Functional languages are programming languages that treat computation as the evaluation of mathematical functions and avoid changing states.

75. Imperative
   - another paradigm is imperative programming where my code uses statements like if and while, providing explicit instructions about how to produce an outcome and its associated with procedural languages
   - Imperative programming is a paradigm that uses statements to change a program's state, defining how tasks are performed step by step.

76. Procedural Languages
   - like C
   - Procedural languages are based on the concept of procedure calls, where the program is structured as a sequence of commands or function calls.

77. Multiparadigm Languages
   - py, js, kotlin, swift, etc.
   - Multiparadigm languages support more than one programming paradigm, such as procedural, object-oriented, and functional programming.

78. Object-oriented
   - you use classes to write a blueprint for the data or objects in my code. a class can encapsulate variables (commonly called properties) as well as functions (commonly called methods in this context). its a common way to organize and reuse code because classes can share behaviours between each other through inheritance
   - Object-oriented programming (OOP) is a paradigm that organizes software design around objects, which are instances of classes.

79. Class
   - A class is a blueprint for creating objects that define properties and methods the objects will have.

80. Property
   - A property is a characteristic or attribute of an object, often represented as a variable within a class.

81. Method
   - A method is a function defined within a class that operates on objects created from that class.

82. Inheritance
   - a subclass can extend and override the behaviours of the parent class, and it opens the door to all kinds of other ideas called design patterns
   - Inheritance is a feature of object-oriented programming where a class can inherit attributes and methods from another class.

83. Design Patterns
   - Design patterns are reusable solutions to common problems in software design, providing best practices for organizing code.

84. Instantiate
   - class by itself wont do shit, its just used to instantiate objects (objects are chunks of data that live in my computer's memory)
   - Instantiating an object means creating a specific instance of a class.

85. Heap
   - if i want to reference the same object over and over again but data is long-lived its not going in the call stack so instead goes to a separate area of memory called the heap which unlike the call stack can grow and shrink based on how my application is used (most languages have it). it also allows me to pass objects by reference which means you can use the same object in multiple variables without increasing memory footprint because it always points to the same chunk of memory object in the heap.
   - The heap is a region of memory used for dynamic memory allocation where variables are allocated and freed as needed.

86. Reference
   - A reference is an alias or pointer to an object or variable, allowing access to the original data.

87. Threads
   - CPUs got'em. takes physical cpu cores and breaks it into virtual cores that allow it to run code simultaneously
   - Threads are units of execution within a process, enabling parallel or concurrent execution of code.

88. Parallelism
   - some programming languages support parallelism where the code i write is executed on 2 different threads
   - Parallelism is a programming technique where multiple tasks are executed simultaneously to improve performance.
   - now many programming languages are single threaded like js but that doesn't mean they cant do 2 things at the same time because they use concurrency

89. Concurrency models
   - like an event loop or co-routines that can pause or delay the normal execution to handle multiple jobs on a single thread at the same time
   - Concurrency is the ability of a system to manage multiple tasks at the same time, often overlapping in execution but not necessarily simultaneously.

90. Bare Metal
   - in modern computing we're rarely working with bare metal cpu and ram, instead we work in the cloud with a virtual machine
   - Bare-metal programming refers to writing software that runs directly on hardware without an underlying operating system.

91. Virtual Machine
   - piece of software that simulates hardware therefore allowing big computers to be split into a bunch of smaller virtual computers and these virtual machines are the backbone of the internet and are connected to each other via the internet protocol where each machine has a unique IP address to identify the machine in the network like a fingerprint
   - A virtual machine (VM) is an emulation of a computer system that allows software to run in a virtualized environment, abstracted from physical hardware.

92. Ip-address
   - usually alias to a url that is registered in a global database called the domain name service (DNS)
   - An IP address is a unique identifier assigned to a device on a network, used to route data between devices.

93. URL
   - A Uniform Resource Locator (URL) is a reference to a resource on the internet, specifying its location and how to access it.

94. DNS
   - The Domain Name System (DNS) translates human-readable domain names into IP addresses that computers use to identify each other on a network.

95. Transmission Control Protocol
   - Transmission Control Protocol (TCP) is a standard communication protocol used for sending data between computers over the internet, ensuring reliable and ordered delivery.

96. Packets (messages in the TCP)
   - Packets are small units of data that are transmitted over a network, containing both the data and information needed to route it to its destination.

97. Secure Sockets Layer
   - Secure Sockets Layer (SSL) is a protocol used to secure communication between web browsers and servers by encrypting the data being transmitted.

98. HTTP
   - now with the protection of SSL computers can securely share data with the hypertext transfer protocol HTTPS. the client may request a web page then the server will respond with some HTML. modern servers provide a standardized way for a client to request data called an API
   - The Hypertext Transfer Protocol (HTTP) is the protocol used for transmitting web pages over the internet, defining how data is exchanged between a web server and browser.

99. Application Programming Interface
   - the most common architecture is REST where urls are mapped to different data entities available on the server
   - An Application Programming Interface (API) is a set of tools and protocols that allow different software applications to communicate with each other.
