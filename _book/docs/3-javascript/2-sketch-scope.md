# Step Through

Learn JS the best way: inside out.  This set of exercises and sketches will focus on two key skills:
* Building your understanding of JavaScript's runtime behavior
* Visualizing the behavior of JS variables, types, and control flow

Neither of these skills are very glamorous and both will take plenty of work to master, mastering them now will ensure your success when you encounter more challenging projects later on. Not taking the time to learn these skills now may feel harmless and probably won't stop you from moving forward for the first few weeks, but you will reach a point where not having these skills under your belt will keep you from succeeding.  By then it's too late, you'll need to do some unlearning.  

So take the time now cement these skills.  You'll know you've made it when you can predict what PythonTutor will display __before__ you click the "forward" button.


### Index
* [Learning Objectives](#learning-objectives)
* [Specifications](#specifications)
* [Resources](#resources)

---

## Learning Objectives

__Study Techniques:__
* Stepping through run-time behavior
* Diagramming flow control

__JavaScript:__
* Creation & Execution Phases
  * Creation (step 1 in PythonTutor)
  * Execution (every other step)
* Variables: var, let, const
  * Assignment by value
  * Assignment by pointer
  * Reassignment
  * Scope - Lexical
  * Scope - Block
  * Hoisting
* Scope:
  * Block scope (let)
  * Lexical Scope (var)
* Data types:
  * Primitive vs Objects  
  * Type Conversion
* Operators & Comparisons:
  * 2-value operators
  * Order of operations
  * Truthy & Falsey evaluations
  * Type Coersion
* Control Flow:
  * If, else, else if
  * For
  * While, do while
  * Switch/case

__Programming Skillzz:__
* Code life-cycle:
  * Source-time
  * Build-time
  * Run-time
* Stepping through:
  * (Run-time behavior)
  * Predicting flow control
  * Evaluating operations
  * Evaluating comparisons
* Tracking variables:
  * Creation & hoisting (build-time)
  * Assignment & reassignment
  * Chained assignments
  * Shared references



[TOP](#javascript-fundamentals)

---

## Specifications

completed examples
  basic
    - link these in the lo list above
    - or at least comments in the examples to indicate the lo
    declaring a let
    hoisting a var
    hoisting a function
    executing a function
    primitive variable
    object variable

  complex
    dots n bracks
      make the diagram for this
      https://goo.gl/ezGgh5
    new_context function: https://goo.gl/iZLE5X



exercises

diagram - changelog ala git
  - completely draw initial state
  - later steps note only the changes
  with +'s and -'s ?
  use original step-through diagram
    only you write just what has changed?
    predictions are challenge/optional
  add line numbers to predictions
  info beyond vars & values
    previous line executed
    line # executed
    next line to execute
  behavior-translated code
    control flow?



add to demo a step with bad line guess

simple: just copy
  inneffective?
challenge:  predict
  cognitive conflict

the examples you create and study should (for now) be limited to control flow, primitives, comparisons, arrays and objects.  avoid functions at the moment, and especially objects with functions inside them.  all in due course

step number in pytut is step to be completed
  so it loads at 0


[TOP](#javascript-fundamentals)

---

## Resources

[JavaScript.info](http://javascript.info/) chapters:
* 2.1 -> 2.13 
* 3.1
* 5.1 -> 5.3

[You Don't Know JS]:
* [Types](https://github.com/getify/You-Dont-Know-JS/blob/master/types%20%26%20grammar/ch1.md)
* [Values](https://github.com/getify/You-Dont-Know-JS/blob/master/types%20%26%20grammar/ch2.md)
* [Type Coersion](https://github.com/getify/You-Dont-Know-JS/blob/master/types%20%26%20grammar/ch4.md)

Visualization Tools:
* [PythonTutor for JavaScript](https://github.com/elewa-academy/js-tool-kit/blob/master/learning-environments.md#pythontutor):
  * For building your Notional Machine: visualizes how the JavaScript engine steps through code, deals with variables, and handles control flow. 
  * Copy your code into the text area and click "visualize execution".  Step through line by line with the "forward" button.  
* [Parsonizer](https://github.com/elewa-academy/js-tool-kit/blob/master/learning-environments.md#parsonizer):
  * Randomizes the lines in your code, you have to put them back in order (white space counts!).  This will help you learn syntactic structures & develop your logical problem solving skills by studying quality examples.
  * Copy paste your code into the text box and click the magic button.  Click "get feedback" to grade your answer.
* [Realtime flow-chart generator](https://github.com/elewa-academy/js-tool-kit/blob/master/learning-environments.md#bogdan-lyashenko):
  * For visualizing flow control, the logical structure & progression of your code.
  * Copy paste code into this site to automatically generate flow control visualizations.
* diagram to draw - make it 


Tricky Bits:
* Creation vs Execution phases:
  * _Creation phase_ is what happens before the first line is executed.  Mostly just hoisting. You can see what happened in the creation phase, it's what PythonTutor displays before you click the __forward__ button for the first time.
  * _Execution phase_ is everything that happens after the creation phase.
* Assign by reference vs. value: 
  * [Gist to study](https://gist.github.com/colevandersWands/9f50787fdddfb195d181da94c25536d8)
  * [article 1](https://codeburst.io/explaining-value-vs-reference-in-javascript-647a975e12a0)
  * [article 2](https://medium.com/@naveenkarippai/learning-how-references-work-in-javascript-a066a4e15600)
* Scope:
  * [w3schools](https://www.w3schools.com/js/js_scope.asp)
* Hoisting: 
  * [Article to study with PyTut](https://john-dugan.com/hoisting-in-javascript/)
  * [JS is Compiled](https://medium.com/@nickbalestra/javascripts-lexical-scope-hoisting-and-closures-without-mystery-c2324681d4be)
  * [Creation phase](http://tramaine.me/blog/javascript-variables-and-functions-are-hoisted-prior-to-execution)
  * [Step-through example](./hoisting-example-step-through.md)
  * [Great gist](https://gist.github.com/rishabhgupta/06921ed0fb442071018fc3d643a3f913)
* Scope:
  * [gist to study](https://gist.github.com/colevandersWands/557c6f7f770eaecfcb6216c893e69166)
  * [Let vs var](https://codeburst.io/difference-between-let-and-var-in-javascript-537410b2d707)
  * [Issues with 'var'](https://www.youtube.com/watch?v=7tGmS2SPxBo)
  * [in great detail](http://exploringjs.com/es6/ch_variables.html)
* [Incrementing & Decrementing](https://codeburst.io/javascript-increment-and-decrement-8c223858d5ed)


[TOP](#javascript-fundamentals)

___
___
### <a href="http://elewa.education/blog" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/34921062-506450ae-f97d-11e7-875f-6feeb26ad72d.png" width="100" height="40"/></a>

