WORKSHOP

TASK 2

START

         INPUT NUMBER1
         INPUT NUMBER2
         INPUT NUMBER3
         TOTAL=NUMBER1+NUMBER2+NUMBER3
         AVG=TOTAL/3
         PRINT AVG
        PRINT TOTAL

END

TASK 3

START

        INPUT Number

        FOR i = 1:10
                    x=Number *i
                    PRINT x

END

TASK 4

 START

         INPUT Number
         
          IF Number > 0 
                    PRINT "Positive"
          IF Number < 0
                PRINT "Negative"
          IF Number == 0
                PRINT "zero"

      END               


      TASK 5


      START 

          INPUT P 
          INPUT R
          INPUT T
         SI = (P*R*T) / 100
         PRINT SI

END

 TASK 6

 START
    
    sum = 0
    day = 1
    WHILE day <= 7 DO
        INPUT temp
        sum = sum + temp
        day = day + 1
    ENDWHILE
    average = sum / 7
    PRINT average

END


TASK 7

START
    
    INPUT length
    INPUT width
    area = length * width
    PRINT area

END


TASK 8


START
    
    INPUT average
    IF average >= 50 THEN
        PRINT Pass
    ELSE
        PRINT Fail
    ENDIF

END


TASK 9


START
    
    INPUT n
    fact = 1
    i = 1
    WHILE i <= n DO
        fact = fact * i
        i = i + 1
    ENDWHILE
    PRINT fact

END


TASK 10 

START
    
    INPUT amount
    IF amount > 1000 THEN
        discount = amount * 0.10
    ELSE
        discount = 0
    ENDIF
    finalAmount = amount - discount
    PRINT discount
    PRINT finalAmount

END
