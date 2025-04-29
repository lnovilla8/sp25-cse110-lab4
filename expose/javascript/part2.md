1. What will happen at line 12 and why? If the code causes an error, explain why. 
At line 12, it prints "3" because that is the value of i in the for loop when it finishes executing. i is accessible throughout the function because it is initialized as a var.

2. What will happen at line 13 and why? If the code causes an error, explain why. 
Line 13 will print "150" because that is the value of discounted price when the function finishes executing. It calculate the discounted price of 300 with 0.5, resulting in 150.

3. What will happen at line 14 and why? If the code causes an error, explain why. 
Line 14 will print "150" because that is the value of finalPrice after discountedPrice is rounded. It is accessible because it is a var variable. It is the result of 300 * 0.5 and rounding it.

4. What will this function return? Give a brief explanation why. If the code causes an error, explain why.
This function will return [50, 100, 150]. It calculate the discount by multiplying each of the elements in prices by the discount, which are [100, 200, 300] each by 0.5. Each value is then rounded and pushed into the discount arround. So, the final return value is [50, 100, 150].

5. What will happen at line 12 and why?  If the code causes an error, explain why. ^^^ (assume this function is being called like the others: discountPrices([100, 200, 300], 0.5)).
At line 12, there will be an error because it tries to print the value of i, but it cannot be accessed since it is of type 'let' and initialized in the scope of the loop.

6. What will happen at line 13 and why? If the code causes an error, explain why.
At line 13, there will be an error because it tries to print the value of discountedPrice, but it cannot be accessed since it is of type 'let' and it is initialized in the scope of the loop.

7. What will happen at line 14 and why? If the code causes an error, explain why.
At line 14, it prints '150' because that is the value of finalPrice at the end of the loop. It is accessible because it was initialized in the function scope, which is the same scope of console.log on line 14.

8. What will this function return? Give a brief explanation. If the code causes an error, explain why.
The function will return [50, 100, 150]. It calculates the price after each discount and no errors are thrown because each variable is being accessed in a permitted scope.

9. What will happen at line 11 and why? If the code causes an error, explain why. 
An error is thrown because the variable i is attempted to be accessed, but it is of type let and initialized inside the scope of the for loop.

10. What will happen at line 12 and why? If the code causes an error, explain why. 
At line 12, '3' is printed in the command line because that is the value of price.length. It is accessible because the console.log call and initialization of length are in the same scope.

11. What will this function return? Give a brief explanation. If the code causes an error, explain why.
The function returns [50, 100, 150] as the function calculate the prices after discount by multiplying the prices by 1 - discount. It then pushes each of the prices onto discounted. No error is returned because each variable is accessed within its respective scope and const variables are not modified.

12.  Given the above Object, write the notation for:

A. Accessing the value of the name property in the student objects
student.name

B. Accessing the value of the Grad Year property in the student object
student["Grad Year"]

C. Calling the function for the greeting property in the student object
student.greeting()

D. Accessing the name property of the object in the Favorite Teacher property in student
student["Favorite Teacher"].name

E. Access index zero in the array of the courseLoad property of the student object
student.courseLoad[0]

13.
Arithmetic
A. '3' + 2 = '32'
Integer maps to its string representation

B. '3' - 2 = 1
Minus sign causes '3' to turn into integer representation

C. 3 + null = 3
Null equals 0

D. '3' + null = '3null'
Plus sign causes concatentation and null turns into 'null'

E. true + 3 = 4
True is equal to 1 and added to 3

F. false + null = 0
False is equal to 0 and null is equal to 0

G. '3' + undefined = '3undefined'
Plus sign concatenates and turns undefined into string representation

H.'3' - undefined = NaN
Types cannot be matched

14.
Comparison
A. '2' > 1 
True - comparing sign turns 2 into integer equivalent

B. '2' < '12'
False - both are strings and compared lexicographically

C. 2 == '2'
True - '2' is turned into integer equivalent

D. 2 === '2'
False - === means that types must match

E. true == 2
False - true is equal to 1 and 1 is not equal to 2

F. true === Boolean(2)
True - Boolean(2) results to true and true is equal to true

15. Explain the difference between the == and === operators.
When using ==, it can coerce each of the elements being compared to the same type. When using ===, the types must be the same.

16. in part2-question16.js

17. If the function above is called with the following parameters modifyArray([1,2,3], doSomething), what will be the result? Briefly walk through how you arrived at that result. (This should be in your part2.md). Here we are passing in a function as a parameter, however we can also return a function from another function just as easily, you're encouraged to play around with callbacks as they are used heavily in frontend JS development. 

The result is [2, 4, 6]. The program first calls modifyArray with the parameters [1, 2, 3] and doSomething. It creates a new empty array and loops through each index in the inputte array. It pushes the value returned by callback(array[i]) and pushes it onto the new array. Since callback is doSomething, it calls doSomething with the element from the inputted array, which multiplies the element by 2. So, the loop gets each element in the inputted array, and multipies each element by two, and puts it into a new array.

18. in part2-question18.js 

19. What is the output of the above code? (This should be in your part2.md)
1
4
3
2
