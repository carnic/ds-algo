# Recursion

Some computer programming languages allow a module or function to call itself. This technique is known as recursion. In recursion, a function α either calls itself directly or calls a function β that in turn calls the original function α. The function α is called recursive function.

A recursive function can go infinite like a loop. To avoid infinite running of recursive function, there are two properties that a recursive function must have −

#### Base criteria
There must be at least one base criteria or condition, such that, when this condition is met the function stops calling itself recursively.

#### Progressive approach
The recursive calls should progress in such a way that each time a recursive call is made it comes closer to the base criteria.
