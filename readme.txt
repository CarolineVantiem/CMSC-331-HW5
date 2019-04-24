The goal of this exercise is to acquaint yourself with two very powerful tools for the
generation of compilers: flex and bison. 

Your job is to modify the application to add logical operators as in the following table. All
operators will have left associativity.

Operator Meaning Precedence Description
& Logical and Lowest This is equivalent to && in C language. It is a
binary operator. If it evaluates to true, it
returns 1 and if evaluates to false it returns 0.

| Logical or Same as & This is equivalent to || in C language. It is a
binary operator. If it evaluates to true, it
returns 1 and if evaluates to false it returns 0.

== Equal Higher than
& and |,
lower than >
It is a binary operator. If both sides are of
equal values, it returns 1, otherwise it returns
0.

> Greater
than
Highest It is a binary operator. If left operand has a
greater value than right operand, it returns 1,
otherwise it returns 0.
