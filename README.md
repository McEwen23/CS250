# CS250

Summarize the project and what problem it was solving.
  
  This program is used to calculate investment returns over a period of time. It is meant to be used as an eduactional tool for a bank to inform prospective clients   on their potential returns if they invested a certain amount of capital over a set interest rate compounded yearly.

What did you do particulary well?
  
  I thought I did a good job of implementing object oriented programming concepts such as encapsulation, abstraction, and inheritance. This made my code simple,       maintainable, and readable. If I wanted to update any part of the program I could implement a new function to add a new banner/prompt or conduct an new             computation to expand the programs capabilities.
  
Where could you enhance your code? How would these improvements make your code more efficient, secure, and so on?
  
  I could enhance the way I handle errors and execeptions throughout my program. The way it is coded now works okay for a small program such as this but if it grew
  to a meaningful size I think it would be beneficial to have the indvidual functions handle the error and exceptions themselves. This would mean I could call one
  function anywhere in the program and trust that it would handle everything from computation to error handling. If an update was ever made the error handling         portion of the code would be in one location instead in many places throught the program. 
  
Which pieces of the code did you find most challenging to write, and how did you overcome this? What tools or resources are you adding to your support network?
 
 A) The pieces of code that I found most challenging to write was how to handle and display the calculations for the investment that the specification document          required. I ultimatley came to the conclusion - after some thought - that the strategy of using a vector as a means of storing data proved difficult because I      had to find a way to calculate and display returns on a yearly basis. I wouldnt know in advance how many years the user entered so I wouldnt know the index          number to pull the data from the vector I needed everytime. I switched methods to using a nested for loop for the calculations, displaying and resetting each        variable after 12 iterations (the months of the year) and adding a year to the main loop until it statisfied the length condidtion the user entered.
  
  B) The tools I've added to my support network are specfically refering to source documentaion and libraries to see if there are any tools that I can use to solve      my problem or to give me a different perspective on how to solve a problem I am stuck on.
  
What skills from this project will be particularly transferable to other projects or course work?
  
  Thinking about in advance how im going to structure my code so that its maintainable and readable using object oriented programming concepts are skills that will   be trasferable to other projects. Additionally, changing methods for solving problems on the fly is a skill I will take with me to future projects.
