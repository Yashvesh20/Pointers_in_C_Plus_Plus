# Pointers_in_C_Plus_Plus
# Software Required:
Visual Studio
# Theory:

A pointer is a special variable that holds the memory address of another variable, rather than storing a direct value itself. Pointers allow programs to access and manipulate data in memory efficiently, making them a key feature for system-level programming and dynamic memory management.

Assign Address:
The addressof operator (&) determines the address of any variable in C++. 
Dereferencing:
The process of accessing the value present at the memory address pointed by the pointer is called dereferencing. The (*) Symbol is used for Dereferencing.

Pointers are a useful concept in C++ that allow direct access to memory addresses, providing greater control over memory and data manipulation. 

+ Implementing Data Structures: Pointers are used to implementing complex data structures such as linked lists, trees, and graphs, where elements are dynamically allocated and linked together.

+ Pass Arguments by Pointer: Pass the argument with their address and make changes in their value using pointer. So that the values get changed into the original argument.


# Implementation:
Pointers in C++ were implemented using the following codes,
+ Increment of pointers
+ Addition or Subtraction of Pointers
+ Reversing an Array using a Pointer
+ Printing a String using Pointer

# Algorithms:
Reverse an Array Using Pointers
- Start
- Declare an integer array arr of size 5.
- Prompt the user to enter 5 elements.
- Use a loop to input values into arr.
- Display the original array using a loop.
- Declare a pointer ptr and set it to point to the last element of arr:
- ptr = &arr[4]
- Display the reversed array using a loop:
- For i from 0 to 4:
- Print the value at *(ptr - i)
- End

Pointer Increment 

  Step 1: Start the program.
  
  Step 2: Declare an integer variable x and initialize it with the value 2022.
  
  Step 3: Declare an integer pointer x1 and assign it the address of x.
  
  Step 4: Display the address stored in x1 (before increment).
  
  Step 5: Increment the pointer x1 by 1.
  
  Step 6: Display the address stored in x1 (after increment).
  
  Step 7: Declare a float variable y and initialize it with the value 22.20.
  
  Step 8: Declare a float pointer y1 and assign it the address of y.
  
  Step 9: Display the address stored in y1 (before increment).
  
  Step 10: Increment the pointer y1 by 1.
  
  Step 11: Display the address stored in y1 (after increment).
  
  Step 12: Declare a double variable z and initialize it with the value 4234234.
  
  Step 13: Declare a double pointer z1 and assign it the address of z.
  
  Step 14: Display the address stored in z1 (before increment).
  
  Step 15: Increment the pointer z1 by 1.
  
  Step 16: Display the address stored in z1 (after increment).
  
  Step 17: Declare a boolean variable t and initialize it with the value true.
  
  Step 18: Declare a boolean pointer t1 and assign it the address of t.
  
  Step 19: Display the address stored in t1 (before increment).
  
  Step 20: Increment the pointer t1 by 1.
  
  Step 21: Display the address stored in t1 (after increment).
  
  Step 22: End the program

# Conlusion:
The concept of pointers were implemented using  codes in C++.
