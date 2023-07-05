## Abstract Data Types : 
We can think of an abstract data type (ADT) as a mathematical model with a collection of
operations defined on that model. Sets of integers, together with the operations of union,
intersection, and set difference, form a simple example of an ADT. In an ADT, the
operations can take as operands not only instances of the ADT being defined but other
types of operands, e.g., integers or instances of another ADT, and the result of an operation
can be other than an instance of that ADT. However, we assume that at least one operand,
or the result, of any operation is of the ADT in question.

An implementation of an ADT is a translation, into statements of a programming
language, of the declaration that defines a variable to be of that abstract data type, plus a
procedure in that language for each operation of the ADT. An implementation chooses a
data structure to represent the ADT; each data structure is built up from the basic data
types of the underlying programming language using the available data structuring
facilities. Arrays and record structures are two important data structuring facilities that are
available in Pascal. For example, one possible implementation for variable S of type SET
would be an array that contained the members of S.



