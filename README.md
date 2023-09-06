Symbol table implemented with linked list and hash table

In Linux, a type of abstract data types (ADTs) is symbol table. It is an unordered collection of bindings. A binding consists of a key and a value. A key is a string that uniquely identifies its binding; a value is data that is somehow pertinent to its key. A symbol table allows its client to insert (put) new bindings, to retrieve (get) the values of bindings with specified keys, and to remove bindings with specified keys. Symbol tables are used often in programming systems; compilers, assemblers, and execution profilers use them extensively.

This repository will implement the symbol table using two approaches: 1, a simple implementation might store the bindings in a linked list. The linked list is a linear collection of data elements whose order is not given by their physical placement in memory. Instead, each element points to the next. It is a data structure consisting of a collection of nodes which together represent a sequence. 2, a more efficient implementation might use a hash table. A hash table uses a hash function to compute an index, also called a hash code, into an array of buckets or slots, from which the desired value can be found.

The task is to create an ADT named SymTable. Each SymTable object must be a symbol table. A SymTable object must be generic. That is, a SymTable object must contain values which are void pointers, and thus can point to data of any type. Two implementations will be used to for the SymTable ADT: one that uses a linked list and another that uses a hash table.

This project is a COS217 assignment. https://www.cs.princeton.edu/courses/archive/spr23/cos217/asgts/03symtable/index.html

A complete code is a private repository and it is available upon request only for employment purpose.
