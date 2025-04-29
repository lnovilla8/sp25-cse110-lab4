1. What is printed by line 9? If the code returns an error, explain why.
Line 9 prints: "values added: 20".

2. What is printed by line 13? If the code returns an error, explain why. 
Line 13 prints: "final result: 20".

3. Why should you not use var? Explain why. 
You should avoid using var because it can lead lead to errors because of its scope being accessible anywhere in the function block.

4. What is printed by line 9? If the code returns an error, explain why.
Line 9 prints: "values added: 20".

5. What is printed by line 13? If the code returns an error, explain why. 
Line 13 results in an error because result is initialized as a let, meaning that it is only accessible in the black it was made in. So, line 13 cannot access it, resulting in an error.

6. What is printed by line 9? If the code returns an error, explain why. 
Line 9 does not print because an error is returned before it is executed. On line 7, it tries to modify the initial value of result from 0 to num1 + num2, but this is not allowed because it is a const variable.

7. What is printed by line 13? If the code returns an error, explain why. 
Line 13 is not printed because of the error discusses in question 6. Furthermore, if line 7 did not result in an error, line 13 would still return another error since you cannot access a const outside of its scope block.