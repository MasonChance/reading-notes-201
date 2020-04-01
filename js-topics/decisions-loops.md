# Script Flow and statement evaluation. 

- Declare variables
- Declare values of those variables
- Make statements about those variables describing the relationships between them and the properties they have
- Evaluate the expression
- check the results against predifined outcomes to get a single value. 

There are many statements and comparisons that can be made about variables and their relationships but at it's simplest it follows like this. 

Conditions are usually set in an "if this than do this, otherwise do this instead" format. 

![Anatomy-of-conditionalCode](/reading-notes-201/js-topics/Anatomy of conditional Code.png)

something occurs called an event. values of that event are compared with the expected value, a decision about which code to run next is made based on that comparison and the script either continues down the list or terminates depending on weather the correct conditions were satisfied. 

A breif note on Loops. a loop can be used in the event that the same peice of could needs to be run more than once to get the desired result. loops also depend on conditional statements to tell them weather or not to continue running or to terminate and return the value of the comparison. 

## Switches and Loops

we met the basic conditional statement `if(){}` earlier. now lets talk about switches. a switch statement allows us to set multiple conditions with different outcomes based on input flow and how each successive condition is evaluated. Switch statements function similarily to `if` and `else if` statements but create a default value that runs uless a condition is met. starting with a switch variable the switch value is set. 

``` 
switch(value assigned){
  case 1:
    code to run in case 1;
    break;

  case 2:
    code to run in case 2;
    break;
  ...list each case in this way then:

  default:
    code to run as default;
    break;
}

the break command tells the script to stop when a case evaluates true. 
```

#### loops. 

there are three kinds of loops, all employ a loop counter and are used to run the same peice of code more than once. loop counters prevent infinite repititions of the script from running. 

**for** loop. use this if you know the specific number of times you need the code to run. 
**while** loop. use this if you do not know how many times the code should run. 
**do while** is like the *while* loop but will always run each peice of code at least once even if condition evaluates false. in this case the statements are made ***before the condition is declared***


