answers for the Variable Value Challenge (answers are also listed without work shown at the bottom):

var x = 3
(variable value = 3)

1.) x = x + x
(variable value: x = 3 + 3 = 6)


2.) for (var i = 0; i< 4; i++) {
             x = x + 1
   }
(variable value: 
          i = 0: x = 6 + 1 = 7
          i = 1: x = 7 + 1 = 8
          i = 2: x = 8 + 1 = 9
          i = 3: x = 9 + 1 = 10)

* At this step, I was not sure if i = 0 meant to start counting variable x at 0 or to count 0 times through the loop of the equation given for x.
 (alternative variable value:
          i = 0: x = 0 + 1 = 1
          i = 1: x = 1 + 1 = 2
          i = 2: x = 2 + 1 = 3
          i = 3: x = 3 + 1 = 4)


3.) if (x > 10) {
           x = 2;
  } else {
           x = 3;
  }
(variable value: starting x = 10 (or x = 4). both do not satisfy (x > 10) so x = 3)


4.) function doubleIt(value) {
           return value * 2;
     }

     doubleIt(x);
     x = doubleIt(x);

(variable value: doubleIt(x) yields 6, then x = doubleIt(x) = 12)


5.) var numberArray = [1,2,3];

   for(i = 0; i < numberArray.length; i++) {
            x = x + numberArray[i];
   }
(variable value: 
         i = 0: x = 12 + 1 = 13
         i = 1: x = 13 + 2 = 15
         i = 2: x = 15 + 3 = 18)


So, in summary, here are my answers:

1.) x = 6
2.) x = 10
3.) x = 3
4.) x = 12
5.) x = 18
