## Separation of Concerns


This project is designed to illustrate one of, if not __the most__, fundamental principle of software design:

> SEPARATION OF CONCERNS

"Separation of concerns" means that each file, each piece of code, has one simple and well defined purpose.  In this project you will be exploring the separation of UI framework, input handling, and application logic.  You will be taking your CodeWar solutions from before and use each one to make a mini-application that run from the terminal and the browser.  The "concerns" are:
* __UI__ - Command Line or Browser
  * What the user sees and interacts with
  * Will change with each deployment environment
* __Middleware__ - Hanlders 
  * Cleans user input from UI and passes it to the logic
  * Will change with each deployment environment
* __Logic__ - Your CodeWar solutions
  * Pure functions that take in arguments and return new values
  * Can be reused in any JS deployment environment


Understanding this principle will help with testing, development scheduling, collaboration, maintenance, ... _everything_. In our experience, understanding separation of concerns is the most important thing a new programmer can learn.  Far more important than learning new libraries, powerful devtools, or even being good at solving programming challenges! 

So if this project feels too easy and you find yourself wanting to make it more complicated, remember that the code isn't the point of this project.  The design is the point.  Pay attention to how each piece of code is structured, and how you fit them together to reuse your solutions in any JS environment.

___
___
### <a href="http://elewa.education/blog" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/34921062-506450ae-f97d-11e7-875f-6feeb26ad72d.png" width="100" height="40"/></a>
