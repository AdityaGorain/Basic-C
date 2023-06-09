# Basic-C
A simple compiler for a "basic C" language, which supports integer constants, variables, expressions, assignments, for loops, and read and write statements.

# Language Description 
* A program consists of a sequence of statements separated by semi-colons.
* A statement is either a declaration-statement, read-statement, write-statement, declaration-statement, assignment-statement, or a for-loop.
* A declaration-statement is of the form int V1, V2, . . . , Vk; where V1, V2, . . . , Vk are variables of integer type. This statement must be the rst statement in the program if it is presented and not allowed in any other part of the program. Further, no variable which is not listed here cannot be used in the rest of the program.
* A read-statement is of the form read X where X is a variable.
* A write-statement is of the form write Y , where Y is either a variable or an integer constant.
* An assignment statement is a statement of the form V = E where V is a variable and E is an expression. 
* Expressions are obtained by applying binary operations +, −, ∗, /, >, == over variables and constants. Note that ∗, / have higher precedence than +, − and +, − have higher precedence than >, ==. All binary operators associate from left to right. Further, expressions can also be parenthesized using (,).
* A for-loop is a statement of the form for(E1; E2; E3){S}; where E1, E2, E3 are the expressions and S is a sequence of statements separated by semi-colons. Note that for-loop is the same as in C language except all statements must be written between { and } even if S is a single statement and there is a semi-colon (;) after }.
* Variable names are from {a−z}+ but not from the set of keywords {for, int, read, write}.
* In addition to the variables, the language also has support for integer constants of the form {0 − 9}+.



