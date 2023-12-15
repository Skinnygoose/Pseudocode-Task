INVOKING SUBPROCEDURES

Use the CALL keyword. For example:

CALL AvgAge with StudentAges
CALL Swap with CurrentItem and TargetItem
CALL Account.debit with CheckAmount
CALL getBalance RETURNING aBalance
CALL SquareRoot with orbitHeight RETURNING nominalOrbit

EXCEPTION HANDLING

    BEGIN
        statements
    EXCEPTION
        WHEN exception type
            statements to handle exception
        WHEN another exception type
            statements to handle exception
    END