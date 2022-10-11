# lesson-7

### Pointers and Arrays
A pointer is a variable that contains the address of a variable. 
Pointers allow us to create more compact and efficient code
Pointers and arrays are closely related
void * (pointer to void) is the proper type for a generic pointer

Machine has an array of consecutively numbered or addressed memory cells that may be manipulated individually or in contiguous groups. 
char - Any byte
short integer - a pair of one-byte cells
Long - four adjacent bytes 
A pointer is a group of cells (often two or four) that can hold an address.


Unary operators:
& 
gives the address of an object, so the statement
p=&c; Assigns the address of c to the variable p, and is said to “point to” c.
The & operator only applies to objects in memory: variables and array elements. It cannot be applied to expressions, constants or register variables.
*
The indirection or dereferencing operator
when applied to a pointer, it accesses the object the pointer points to.
