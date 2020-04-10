# Dealing with Errors in your Code

### The Console and Dev Tools
One of the first things to consider when dealing with an error is to evaluate each function and not only its scope, but the scope of the statements and variables that comprise whatever statement you are currently having an error with. The second but paralell thing to consider is the Stack. If you've ever played Magic the Gathering this will be a familiar concept. 

The interpreter reads the script one line at a time. When a statement requires a peice of information from another part of the code, the new statement gets put on top of its list of priorities. anything paralel to that, gets put on standby until the initial peice of code is executed. 

``` for example: a function, that needs a peice of information from another(probably nested function) will pause any other operation even if that operation directly follows the initial function, and execute the function that the instigator needs, in order to complete. 
```

an error handler acts like an interupt and lets the user know what went wrong without completely breaking the code and rendering the site completely useless. 

as a programmer you can use the console log to find out more information on what is causing a problem. the console displays the information by filetype, file number, line nubmer and may give some description as to the general nature of the problem. being able to identify roughly where the problem starts, can go a long way to identifying where the error actually started. 

### Common Problems
here are a few common error objects and types. 
- syntax error: syntax was not typed correctly. this is pretty easy to find and fix usually
- reference error: this has to do with variables being declared or not as well as the scope in which they were declared. 
- type error: unexpected data type is returned and cannot be coerced

### Error Handling
There is a sort of workflow to identifying and correcting errors, a PEMDAS if you will. 
1. where is the problem?
  - look at the error for relevant script, the line where it became an issue, the type of error, just dont confuse the point of trigger as the point of problem source
1. use the console to check how far down the script is running. console.log all the major peices to see if the smaller bits need to be logged as well
1. use breakpoints if you think there's a problem area, these allow you to pause the running of the script. 
1. there are built in methods that allow you to address issues in the script.
  - `try` `catch` and `finally` statements. 
