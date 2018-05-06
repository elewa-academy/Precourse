## Separation of Concerns


This project is designed to illustrate one of, if not __the most__, fundamental principle of software design:

> SEPARATION OF CONCERNS

"Separation of concerns" means that each file, each piece of code, has one simple and well defined purpose.  In this project you will be exploring the separation of UI framework, input handling, and application logic.  You will build a basic calculator object then use that same object to take arguments from the terminal and the browser.  The concerns are:
* UI - command line, HTML
* Middleware - process.argv, event listeners
* Logic - the cleancalc object

It is very important that you build your calc object with exactly the property names, arguments, and return values specified.  Doing this is called "developing to an interface".  If you do this correctly you will be able to replace anyone's cleancalc object with yours and your application will continue working.  The magic of software design!

Understanding this principle will help with testing, development scheduling, collaboration, maintenance, ... _everything_. In our experience, understanding separation of concerns is the most important thing a new programmer can learn.  Far more important than learning new libraries, powerful devtools, or even being good at solving programming challenges.  

So if this project feels too easy and you find yourself wanting to make it more complicated, remember that the code isn't the point of this project.  The design is the point.  Pay attention to how we use specs to define and develop the calculator, and how we integrate that object into the HTML.

___
___
### <a href="http://elewa.education/blog" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/34921062-506450ae-f97d-11e7-875f-6feeb26ad72d.png" width="100" height="40"/></a>
