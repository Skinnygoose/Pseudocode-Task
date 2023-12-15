CASE
A CASE construct indicates a multiway branch based on conditions that are mutually exclusive. Four keywords, CASE, OF, OTHERS, and ENDCASE, and conditions are used to indicate the various alternatives. The general form is:

CASE expression OF
condition 1 : sequence 1
condition 2 : sequence 2
...
condition n : sequence n
OTHERS:
default sequence
ENDCASE
The OTHERS clause with its default sequence is optional. Conditions are normally numbers or characters

indicating the value of "expression", but they can be English statements or some other notation that specifies the condition under which the given sequence is to be performed. A certain sequence may be associated with more than one condition.
Example
        CASE  Title  OF
                Mr      : Print "Mister"
                Mrs     : Print "Missus"
                Miss    : Print "Miss"
                Ms      : Print "Mizz"
                Dr      : Print "Doctor"
        ENDCASE
Example
        CASE  grade  OF
                A       : points = 4
                B       : points = 3
                C       : points = 2
                D       : points = 1
                F       : points = 0
        ENDCASE