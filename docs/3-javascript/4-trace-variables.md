# Trace

JS & syntax is what most courses focus on.  We focus on what happens behind the syntax, and how to use it wisely.

notional machine & using code

### Index
* [Learning Objectives](#learning-objectives)
* [Specifications](#specifications)
* [Resources](#resources)

---

## Learning Objectives

__Study Techniques:__
* Stepping through run-time behavior
* Tracking variables
* Diagramming flow control
* think of something else?

__JavaScript:__
* Objects (without methods):
  * Accessed by pointer
  * Dot vs. Bracket access
  * "for ... of" loops
* Arrays
  * "for ... in" loops
* Console.log



__Programming Skillzz:__
* Code life-cycle:
  * Source-time
  * Build-time
  * Run-time
* Tracking variables:
  * Creation & hoisting (build-time)
  * Assignment & reassignment
  * Chained assignments
  * Shared references
* Tracking data structures
* Nested flow control:
  * Conditionals in conditionals
  * Loops in loops
  * Conditionals in loops
* Nested data structures:
  * Arrays in Arrays
  * Objects in Objects
  * Arrays in Objects
  * Objects in Arrays

  
[TOP](#javascript-fundamentals)

---

## Specifications

** should this be called 'roles'?
  or should it be split to two - before/after chunk
  how to handle this 
  introduce roles up front
    then introduce the roles as they are relevant

diagram that focuses on values
  - column per variable & structure
    ala changelog
  - track structures
  - track contexts & scopes
    how to differentiate scopes & contexts?
    and to relate vars that share
  - indicate if two vars point to same object
  steps go down
  only steps that effect variables show up

concrete diagram takes shape
  - cases to capture in examples
    let vs var (jit declaration)
    scope
    context
    obj vs var
  for each variable a column
  for each step a variable is modified
    the old value
    the operation
    the new value
  white-space sensitive
    mark that you've tabbed in
  and context sensitive
  to track
    scope where created
    scope where modified
    contexts - can't keep them from using functions

roles for this time around
  - define classifying questions
  constants
    - it is never modified
      ie. only appears on the right hand side of assignments
    const key word
  utilities (infrastructural?)
    - is modified
    - is not on the right hand side of result
      except control flows
    - defined in/for a loop's condition
  grey zone
    is there really one more category?
  ephemeral
    - on the right hand side of result
    - will not matter in a post-chunk test
    fix this name
  result (output?)
    - leaves the chunk
      ie. on the right of a return statement
        or can be put in an assert to validate a chunk
    best practice
      only put it on the left hand side of equal signs
    https://elewa-academy.github.io/Solution-Design/07-place-constraints/
    often a data structure

info must have per var
  role
  scope & context 
    created
    read
    modified
    how it got there
  when used in assignment happens
    right or left side?
    what's on the other side?
      this helps determine it's role

abstract diagram

assert.md moves in here
  https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/debugging
    
  try-catch + console.assert
  chromedev console
  console methods
    assert
    error
  tddbin
    does it have a save feature

*** sajaniemi 2002: from sorva pg 42
	https://pdfs.semanticscholar.org/735e/1f2eedf0b178d27073bffacf04a92e1d31c6.pdf

```js
// reading or writing twice
let a = 9;
let b = a;
let c = a;
let a = b;
```

tracing technologies
	pytut
	roles
		create examples of each in js
		perhaps copy from
			https://en.wikibooks.org/wiki/A-level_Computing/AQA/Problem_Solving,_Programming,_Data_Representation_and_Practical_Exercise/Fundamentals_of_Programming/The_Role_of_Variables
			http://www.cs.joensuu.fi/~saja/var_roles/role_intro.html
	diagram
		try to emulate roles guy's visualization
	instructions
	examples

** find this paper
	Using Tracing and Sketching to Solve Programming Problems: Replicating and Extending an Analysis of What Students Draw

*** https://faculty.washington.edu/ajko/papers/Xie2018TracingStrategies.pdf

works cited
  cunningham
  sketches from 2018
  roles guy

basic debugging
	or not here?
	only in pytut & fcc up to now?
	https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/debugging

concrete tracing. sorva pg 63

[TOP](#javascript-fundamentals)

---

## Resources

js.info: 4.1-4.2, 5.4-5.6, 5.8 

for loop details: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for

scopes in for loops: https://noraesae.net/2017/09/14/lexical-scope-in-js-for-loop/

#### Tools:
* [PythonTutor for JavaScript](http://www.pythontutor.com/javascript.html#mode=edit):
  * For building your Notional Machine: visualizes how the JavaScript engine steps through code, deals with variables, and handles function execution. 
  * Copy your code into the text area and click "visualize execution".  Step through line by line with the "forward" button.  See [this markdown]() for more tips.
* [Step-Through Diagrams](make a folder in this repo):
  * By Step:  Focus on everything that happens in each step of execution. 
  * By Variable:  Focus on how each variable changes over the course of program execution.
* [Parsonizer](https://elewa-academy.github.io/parsons/):
  * Randomizes the lines in your code, you have to put them back in order (tabs count!).  This will help you learn syntactic structures & develop your logical problem solving skills by studying quality examples.
  * Copy paste your code into the text box and click the magic button.  Click "get feedback" to grade your answer.
* [Realtime flow-chart generator](https://bogdan-lyashenko.github.io/js-code-to-svg-flowchart/docs/live-editor/index.html):
  * For visualizing flow control, the logical structure & progression of your code.
  * Copy paste code into this site to automatically generate flow control visualizations.


[TOP](#javascript-fundamentals)

___
___
### <a href="http://elewa.education/blog" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/34921062-506450ae-f97d-11e7-875f-6feeb26ad72d.png" width="100" height="40"/></a>

