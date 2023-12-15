"Adequate"

FOR X = 1 to 10
    FOR Y = 1 to 10
        IF gameBoard[X][Y] = 0
            Do nothing
        ELSE
            CALL theCall(X, Y) (recursive method)
            increment counter                 
        END IF
    END FOR
END FOR

"Better"

Set moveCount to 1
FOR each row on the board
    FOR each column on the board
        IF gameBoard position (row, column) is occupied THEN
            CALL findAdjacentTiles with row, column
            INCREMENT moveCount
        END IF
    END FOR
END FOR


"Not So Good"
FOR all the number at the back of the array
    SET Temp equal the addition of each number
    IF > 9 THEN
        get the remainder of the number divided by 10 to that index
        and carry the "1"
    Decrement one
Do it again for numbers before the decimal




"Pretty Good"  This example shows how pseudocode is written as comments in the source file. Note that the double slashes are indented.

public boolean moveRobot (Robot aRobot)
{
    //IF robot has no obstacle in front THEN
        // Call Move robot
        // Add the move command to the command history
        // RETURN true
    //ELSE
        // RETURN false without moving the robot
    //END IF
}

Example Java Implementation

source code statements are interleaved with pseudocode.
comments that correspond exactly to source code are removed during coding.
public boolean moveRobot (Robot aRobot)
{
    //IF robot has no obstacle in front THEN
    if (aRobot.isFrontClear())
    {
        // Call Move robot
        aRobot.move();
        // Add the move command to the command history
        cmdHistory.add(RobotAction.MOVE);
        return true;
    }
    else // don't move the robot
    {
        return false;
    }//END IF
}