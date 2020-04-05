# The Problem Domain, object literals, and the DOM. 

## Problem Domain. 

take the extra time to really understand what you are trying to accomplish, in detail.
writing code is very much like a puzzle. the Artilcle [Understanding the Problem Domain is the Hardest Part of Programming](https://simpleprogrammer.com/understanding-the-problem-domain-is-the-hardest-part-of-programming) by John Sonmez, published on [Simpleprogrammer.com](https://simpleprogrammer.com/); Draws a great comparison to doing a complex jigsaw puzzle. the steps for a puzzle are often the same as the steps for coding and are shown below. 

1. Figure out what the major components of the picture are
1. Sort the pieces by color or component
1. Put together all the border pieces
1. Put together each component of the picture from the piles you created

I'ts difficult to do any of those steps if you do not have a frame of reference to check the components against. the more detailed your frame of reference is, the easier it will be to categorize and put the peices together. 

``` 
" ...Make the problem domain easier Get better at understanding the problem domain
You can often make the problem domain easier by cutting out cases and narrowing your focus to a particular part of the problem.

What I mean by this is that it is often beneficial to take a part of the problem and fully understand that part before expanding the problem domain... he other choice is to become better at understanding problem domains.  As developers, we tend to think that sitting down and talking to customers or business people who know about the problem domain is a waste of time. It is easy to fall into the trap of thinking you understand enough of the problem to get started coding it... It is much more expensive and time consuming to do things over than it is to do them right the first time." ~John Sonmez~
```

## Object Literals. 

the `new` keyword followed by the ***Object Constructor*** `object();` create a blank object much like leaving a variable unassigned ` var varName; ` by using the dot operator `.` properties and property values can be pushed into the blank object. example: ` varName.propertyName = propertyValue; ` and repeated for each property that the now full object will have. functions and expressions can be added the same way but using the *Annonymous function* construction method 
`varName.functionName = *function*(){ *statement/expression defining the tasks of the function}; ` yes declaring a function as a ***property of an object*** requires the use of the semicolon after the end of the code block. 

values of properties can be updated by stating the object name the property name and assigning a new vale as you would for a variable. ` objectName.propertyName = 'newValue';` be sure to state the new value as a string. 

## the DOM

the (D)ocument (O)bject (M)odel is a representation of the Html/CSS/JavaScript Document that comprise the website and is used to navigate the various elements and their attributes, to work with or update the information on the site more easily than sifting through the RaW code to make the modifications. this also allows for an easier method of creating dynamic content. 

The DOM tree is navigated and referred to in the same way that the directories and files in the Terminal on your computer are accessed and uses a similar syntax. 