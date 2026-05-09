## Apti

You’ve 1k bottles of wine,exactly one of which is poisoned. The poison kills exactly 24 hours after drinking. 

You’ve 10 test subjects & only 1 round of testing. What is the strategy to guarantee you find the poisoned bottle in 24 hours?

(Max no. of testable bottles using 10 ppl?)

---

Sol :

Subjects: 10 ppl -> [A,B,C,D,E,F,G,H,I,J]

Now, Assign each bottle a unique 10 bit binary ID  as 2^{10} = 1024 combinations.

From bottle if person drinks ->1
Doesn’t drink ->0

From 0000000001 to 1111101000.

Each person drinks from bottle where their specific bit is 1.

---

>After 24hr, the dead ppls pattern creates the binary code for the exact poisoned bottle.  

>If B and C die then poison was in 011000000 bottle. 

(It was a cool apti, calls for revision)



