# What is Recursion

function calls itself directly or indirectly is called recursion.
Other word , a function is said to be recursive if it calls itself.
```dart
  void helloWorld(int n){
if(n < 1) returnProint("hello world") else helloWorld(n - 1);
  }

```

Recursion is a technique where the solution to a problem (case) depends on solutions to smaller instances of the same problem  (case) .


# Syntax of  Recursion : 

 demonstrates some key considerations in designing a recursive algorithm:
There must be  some base condition   that will terminate method.

```dart

Return_Type fun_Name(x)
{
// the three main components that are required for every recursive function.

If(base condition)  // base case

//logic or   problem

fun_Name(x- 1); // smaller instances of the same problem - never go to infinity.
}

```

examples : https://github.com/AhmedAboughosen/problem_sets/tree/master/out/production/problem_sets/com/problems/recursion
