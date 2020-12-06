# Nth_Fibonacci

Inspiration "Write a method fib() that takes an integer nn and returns the nnth Fibonacci ↴ number." https://www.interviewcake.com/question/java/nth-fibonacci?course=fc1&section=dynamic-programming-recursion

Let's say our Fibonacci series is 0-indexed and starts with 0. So:

fib(0);  // => 0
fib(1);  // => 1
fib(2);  // => 1
fib(3);  // => 2
fib(4);  // => 3
...


Questions
-----------------------
- Does time and space matter? (efficient or specific technique)?

Assumptions 
-----------------------
- All positive numbers starting at 0
- Follow general fibonacci sequence 0, 1, ,1, 2 , 3 , 5 (f(n-2)+ f(n-1))



Solutions
-----------------------
- Will need to use recursion. Our recursion setup is as follows

Base case: 0 = 0 , 1 = 1
Equation: Fib(n) = Fib(n-1) + Fib(n-2)


Testcases
-----------------------
- Test for 0 and 1 
- Test a larger number
