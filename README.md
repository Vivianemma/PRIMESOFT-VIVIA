# ATM
  
  **step**
  
WHILE TRUE<br>
   
   DISPLAY "Welcome to Python Bank ATM - Cash Withdrawal"
   amount = INPUT "How much would you like to withdraw today?"
   IF (amount MOD 10) != 0 THEN<br>
      DISPLAY "You can only withdraw a multiple of ten!"
   
ELSE  
   IF amount<10 OR amount>200 THEN
    DISPLAY "You can only withdraw between £10 and £200"
      
  ELSE
         notes20 = amount DIV 20
         notes10 = (amount MOD 20) / 10
         DISPLAY "Collect your money: "
         DISPLAY "    >> £20 Banknotes: " + notes20
         DISPLAY "    >> £10 Banknotes: " + notes10
         DISPLAY "Thank you for using this Python Bank ATM."
         DISPLAY "Good Bye."<br>
      END IF
   END IF
  END WHILE
