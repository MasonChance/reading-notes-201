# Functional Programming

functional programming revolves around the idea that  

``` " Complexity is anything that makes software hard to understand or to modify." 

~John Outerhout~
```

By making sure that functions follow the single purpose principle and that in executing their purpose thier return is the same across any iteration with identical arguments passed in upon invocation. 

by limiting the mutability of any global variables used in the function, and limiting the internal dependency on mutable values, code becomes much easier to read, understand, and modify.

functions that rely on information such as external files or random value generation are considered impure.