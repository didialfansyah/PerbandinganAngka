DECLAR variable num1
DECLAR variable big AND STORE WITH 0
DECLAR variable count AND STORE WITH 0

WHILE count < 3
    STORE variable num1 WITH INPUT
    IF num1 > big
        STORE variable big WITH num1
    ADD variable count BY 1

DISPLAY big
    

