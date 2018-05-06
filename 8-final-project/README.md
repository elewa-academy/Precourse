# Commander.js

take the project from last time and give it a commander.js handler & view


### Index
* [Learning Objectives](#learning-objectives)
* [Specifications](#specifications)
* [Resources](#resources)

---

## Learning Objectives

overview

list

[TOP](#index)

---

## Specifications

1. Build an object to match [these specs](https://github.com/elewa-academy/Fundamentals/blob/master/3-cleancalc/cleancalc-series/1-cleancalc.js). 
2. Write a JS file to take command line arguments and pass them into your calculator. 
    * Your three layers are:
        a. UI - the terminal
        b. Middleware - process.argsv & console.log
        c. Logic - Cleancalc Object
    * You will write a single JS file that takes in command line args, passes them through the calc Object, and prints the result to the console.
3. Reuse your calc object in a basic browser app.  The event handlers will take the user's input, pass it through the calc object, and write the results to the DOM.  
    * Your three layers:
    a. UI - the browser
    b. Middleware - event listeners & DOM methods
    c. Logic - Cleancalc Object
    * Each event listener will only call the calc object once, and will only ever call the operate() method:
        ```js
            ...
            // get user input from the DOM
            let result = cleancalc.operate(user_operation, arg1, arg2);
            // write 'result' into the DOM
            ...
        ```
    * Your project should have this structure:
        * index.html
        * /public
          * middleware.js
          * cleancalc.js
4. Make a repo for this project and put it on your portfolio. 
    * Gh-pages demo
    * README 
        * Description of app's behavior
        * How to use the app
        * Project structure
        * Specs for your calc
        * Link to a [Gist](https://gist.github.com) with your finished calc object
    * Tests for the calc object
    * Source code for every step you completed in a separate folder
5. Go to Slack and trade Gists. See what happens if you replace your cleancalc.js with someone else's.  Does it make your app crash? (This is called _dependency injection_.)



[TOP](#index)

---

## Resources


https://dom-tutorials.appspot.com/static/index.html




https://github.com/elewa-student/precourse-final-project
https://elewa-student.github.io/precourse-final-project/



[TOP](#index)



___
___
### <a href="http://elewa.education/blog" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/34921062-506450ae-f97d-11e7-875f-6feeb26ad72d.png" width="100" height="40"/></a>
