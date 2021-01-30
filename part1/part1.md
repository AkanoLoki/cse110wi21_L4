1. It prints the number of iterations of the for loop to the console.
2. It prints the discounted price for the last item calculated, which is the price multiplied by 1 - discount rate. Note this is a float.
3. It prints the final price calculated for the last item, which is the discounted price rounded to 0.01, making it useful as a price.
4. [50,100,150], since we are basically putting in 3 prices and a discount rate of 50% off.
5. Uncaught ReferenceError: i is not defined; i is out of scope out of the loop
6. Uncaught ReferenceError: discountPrice is not defined; discountPrice is out of scope here
7. It prints the final price calculated for the last item. Note this one is in scope and calculates correctly.
8. [50,100,150], as what we expect.
9. Uncaught ReferenceError: i is not defined. i is out of scope here out of the loop.
10. Prints the first discounted price calculated in the loop. Since we are reassigning const in a loop, we should only get the first value assigned and the rest attempts should result in error.
11. Always print 0, since we cannot reassign finalPrice when its declared const.
12. [0,0,0], since we have the finalPrice which is pushed into the array as a const = 0.
13. A.`student.name`
    B.`student.['Grad Year']`
    C.`student.greeting()`
    D.`student.['Favorite Teacher'].name`
    E.`student.courseLoad[1]`
14. A. "32", as this converts the numeric 2 to string.
    B. 1, as js auto converts the'3' string to number.
    C. 3, js converts null to 0
    D. '3null', js converts null to 'null'
    E. 4, js converts true to numeric 1
    F. 0, js converts false to numeric 0, and null to numeric 0
    G. "3undefined", as undefined is converted to "undefined"
    H. NaN, "3" is converted to numeric 3 and undefined is converted to NaN
15. A. True. 2 is converted to numeric 2
    B. False. strings are compared each char, so 2>1 and returns false
    C. true, "2" is converted to numeric 2
    D. False, triple === does not auto convert
    E. False, true is always converted to numerical 1.
    F. True, here 2 is converted to Boolean true.
16. == auto converts the type of input to match, while === does not.
17. prints 'How are you?' to console, as 2==true returns false and 2 is converted to true.
18. see[part1-question18.js](part1-question18.js)
19. it returns a new array[6,8,10]. for each item in the input array, we have it as (num + 2 ) * 2 as aggregate.
20. see[part1-question20.js](part1-question20.js)
21. 1
    4
    3
    2