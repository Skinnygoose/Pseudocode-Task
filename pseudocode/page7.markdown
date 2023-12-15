REPEAT-UNTIL

This loop is similar to the WHILE loop except that the test is performed at the bottom of the loop instead of at the top. Two keywords, REPEAT and UNTIL are used. The general form is:

REPEAT
sequence
UNTIL condition
The "sequence" in this type of loop is always performed at least once, because the test is peformed after the sequence is executed. At the conclusion of each iteration, the condition is evaluated, and the loop repeats if the condition is false. The loop terminates when the condition becomes true.
 

 FOR

This loop is a specialized construct for iterating a specific number of times, often called a "counting" loop.  Two keywords, FOR and ENDFOR are used. The general form is:

FOR iteration bounds
sequence
ENDFOR
In cases where the loop constraints can be obviously inferred it is best to describe the loop using problem domain vocabulary.
Example

FOR each month of the year (good)
FOR month = 1 to 12 (ok)
FOR each employee in the list (good)
FOR empno = 1 to listsize (ok)