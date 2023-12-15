IF-THEN-ELSE
Binary choice on a given Boolean condition is indicated by the use of four keywords: IF, THEN, ELSE, and ENDIF. The general form is:

IF condition THEN
sequence 1
ELSE
sequence 2
ENDIF
The ELSE keyword and "sequence 2" are optional. If the condition is true, sequence 1 is performed, otherwise sequence 2 is performed.
Example

IF HoursWorked > NormalMax THEN
Display overtime message
ELSE
Display regular time message
ENDIF


WHILE
The WHILE construct is used to specify a loop with a test at the top. The beginning and ending of the loop are indicated by two keywords WHILE and ENDWHILE. The general form is:

WHILE condition
sequence
ENDWHILE
The loop is entered only if the condition is true. The "sequence" is performed for each iteration. At the conclusion of each iteration, the condition is evaluated and the loop continues as long as the condition is true.
Example

WHILE Population < Limit
Compute Population as Population + Births - Deaths
ENDWHILE
Example

WHILE employee.type NOT EQUAL manager AND personCount < numEmployees
INCREMENT personCount
CALL employeeList.getPerson with personCount RETURNING employee
ENDWHILE