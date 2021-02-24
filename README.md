# CS210ProgrammingLanguagesSNHU21EW3
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
#Summarize the project and what problem it was solving.
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
Title: Clocks Flowchart
  Top of chart begins: “Clear Screen”
    1. “Display time in two formats”.
    2. Decision: “Button Pressed?”
      a. If “No” to button pressed, then to “Add 1 Second”. Then “Wait 1 second”. Then back to “Clear Screen”.
      b. If “Yes” to button pressed, then to “Display Menu”. Then “Read user input”. Then to Decision: “User input = exit?”.
        i. If “Yes” to exit, then endpoint: “End program”.
        ii. If “No” to exit, then Decision: “Add Hour?”
    1. If “Yes” to hour, then “Add 1 hour.” Then back to “Clear screen”.
    2. If “No” to hour, then Decision: “Add Minute?”.
      a. If “Yes” to minute, then “Add 1 minute.” Then back to “Clear screen”.
      b. If “No” to minute, then Decision: “Add Second?”.
        i. If “Yes” to second, then “Add 1 Second.” Then back to “Clear screen”.
        ii. If “No” to second, then back to “Clear screen”.
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>       
This was the first project in the class, a clock display. There were some issues with the project requirements, as they seemed to be flawed. I could not find a good method to simultaneously advance a clock, which necessitated being in a loop, and actively accepting user input as the project requirements asked. I simply coded a clock that allowed the user to set the initial time and advance the clock with the menu choices outlined in the project requirements. I enjoyed the project because it was a good way to practice for loops and see the results of the loop easily.
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
#What did you do particularly well?
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
Because I am still very new to C++ I am not sure I did anything particularly well, I would say that I managed the advancement of both a 24 and 12 hour clock well enough.

#Where could you enhance your code? How would these improvements make your code more efficient, secure, and so on?

This would be an interesting project to come back to if/when I begin learning about GUI programming. I spent days trying to find a way to accept input while in a for loop, I would definitely come back and solve that piece of the challenge. I don't anticipate any security concerns with an app like this, aside from someone writing code to make it seem like an innocent clock and including malicious code that is hidden but now has access to the system it is running on. 
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
#Did you find writing any piece of this code challenging, and how did you overcome this? What tools and/or resources are you adding to your support network?
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
I looked at how other people wrote loops to advance clocks and used them as guidelines, I found many helpful pointers on stackoverflow. 
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
#What skills from this project will be particularly transferable to other projects and/or course work?
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
I think one of the best things about this project is just that it got me in front of the computer and also is great practice for learning how to use github.
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
#How did you make this program maintainable, readable, and adaptable?
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
I tried to convery as much information as possible with my comments, while trying to keep them manageable. I used the comments to leave the remnants of an attempt at getting input while in a loop so that if anyone sees where I messed up while trying that they can point it out. Detecting key hits seemed like a useful skill and so I have this to come back to if I learn enough to do it well. 
