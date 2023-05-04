Download Link: https://assignmentchef.com/product/solved-csci204-mcs9204-csci804-object-and-generic-programming-in-c-laboratory-exercise-4
<br>
<strong>Task: Overloading operators  </strong>




We will reuse some definitions and implementations of the class <strong>BigInteger</strong> defined in the lab 3 for this task.

Define the class <strong>BigInteger</strong> in a file <strong>BigInteger.h</strong> and implement its member functions in a file <strong>BigInteger.cpp</strong> that can be used to store a large positive integer. The class contains two data members: a pointer of short integer and the size of the dynamic short integer array. Define the following member functions:

<ul>

 <li>The default constructor;</li>

 <li>An initialization constructor initializes a BigInteger instance with a char array, in which all elements are decimal digits.</li>

 <li>The copy constructor makes a deep copy from a BigInteger instance.</li>

 <li>The destructor;</li>

 <li>Define insertion operator and extraction operator for the class.</li>

 <li>Define assignment operator for the class that makes a deep copy from a BigInteger object.</li>

 <li>Define addition operator that returns a BigInteger object of addition result. Do not change the operands.</li>

 <li>Define multiplication operator for the class that returns a BigInteger object of multiplication result. Do not change the operands.</li>

 <li>Define comparison operator “equals to” that returns the value “true” if two BigInteger objects contain the same values.</li>

</ul>




Write the driver program include main function in a file <strong>lab4Main.cpp</strong> to declare instances of BigInteger, test all the overloading operators defined above.

<strong>Be careful not to submit the solutions for the lab 4 task.  </strong>




Compile the files by

g++ –o task4 lab4Main.cpp BigInteger.cpp




And execute it. Your program should be run like the following example (Red data means input from keyboard)




./task4

Input a big integer for bi1: 567239745104730482394650169432

Input a big integer for bi2: 882323456205024318310561095 Initial bi3=1234567890

bi3 = bi1 + bi2 = 568122068560935506712960730527 bi3 = bi1 * bi2 = 500488932397662823233748695498247943120741026136737448040 bi1 is not equal to bi2 bi3 = bi2 = 882323456205024318310561095 bi3 is equal to bi2

<strong> </strong>