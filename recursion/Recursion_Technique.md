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
# Why use Recursion : 

Where recursion tends to shine is in situations where the problem is a little more complex. Recursion can be applied to pretty much any problem, but there are certain scenarios for which you’ll find it’s particularly helpful.

SCENARIO #1: HIERARCHIES, NETWORKS, OR GRAPHS

In algorithm discussion, when we talk about a graph we’re generally not talking about a chart showing the relationship between variables . Rather, we’re usually talking about a network of things, people, or concepts that are connected to each other in various ways. For example, a road map could be thought of as a graph that shows cities and how they’re connected by roads. Graphs can be large, complex, and awkward to deal with programatically. They’re also very common in algorithm theory and algorithm competitions. Luckily, working with graphs can be made much simpler using recursion.

SCENARIO #2: MULTIPLE RELATED DECISIONS



When our program only has to make one decision, our approach can be fairly simple. We loop through each of the options for our decision, evaluate each one, and pick the best. If we have two decisions, we can have nest one loop inside the other so that we try each possible combination of decisions. However, if we have a lot of decisions to make (possibly we don’t even know how many decisions we’ll need to make), this approach doesn’t hold up.

For example, one very common use of recursion is to solve mazes. In a good maze we have multiple options for which way to go. Each of those options may lead to new choices, which in turn may lead to new choices as the path continues to branch. In the process of getting from start to finish, we may have to make a number of related decisions on which way to turn. Instead of making all of these decisions at once, we can instead make just one decision. For each option we try for the first decision, we then make a recursive call to try each possibility for all of the remaining decisions. 

examples : https://github.com/AhmedAboughosen/problem_sets/tree/master/out/production/problem_sets/com/problems/recursion
