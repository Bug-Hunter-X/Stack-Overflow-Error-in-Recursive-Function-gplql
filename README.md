# Stack Overflow Error in Recursive Hack Function
This repository demonstrates a common error in recursive functions written in Hack: stack overflow. The `foo` function calculates the factorial of a number using recursion. However, when called with a large input, it leads to a stack overflow because of the excessive number of recursive calls. The solution demonstrates a way to mitigate this by using iteration instead of recursion.