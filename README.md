# swe-sr-1-1

Welcome to your first short response assignment! If the code that you write is what gets your foot in the door for a job interview, how you communicate is what will get you the job. So, treat these assignments seriously! Write your responses as if you were planning on publishing them in a blog for the world to see (and, if you're confident, actually publish them!).

## Setup

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/how-tos/working-with-assignments#how-to-work-on-assignments).

Here are some useful commands to remember.

```sh
npm i                   # install dependencies
git checkout -b draft   # switch to the draft branch before starting

git add -A              # add a changed file to the staging area
git commit -m 'message' # create a commit with the changes
git push                # push the new commit to the remote repo
```

## Prompt

Imagine you are teaching a brand new programmer a brief lesson about functions and function calls. Your lesson should have the following components:

* A technical definition ("According to MDN, a function is...").
* An explanation of the concept with an analogy ("You can think of a function a ...")
* An example of the syntax for an arrow function using a JavaScript code block (triple backticks)
* An explanation of the syntax using the terms **arrow function**, **parameter**, **code block**, **return statement**, and **call/invoke**.

Below, we've provided an outline for your response but feel free to modify it as you see fit.

### Response

According to MDN, a function is a block of code designed to perform a particular task. A function lets you group related code together and reuse it whenever needed instead of writing the same code multiple times.

You can think of a function like a **vending machine** — you put in a specific input (like pressing a button for “chips”), and the machine gives you an output (the chips). The machine itself knows exactly what to do when you press that button, just like a function knows what to do when you call it.


[Replace with your explanation of the concept with an analogy]

Check out this example:

```js
// Add your example here

// This arrow function takes a name and returns a greeting
const greet = (name) => {
  return `Hello, ${name}! Welcome to coding.`;
};
// Calling the function
console.log(greet("Sadia"));








[Replace with your explanation of the example and explanation of the syntax]
const greet = (name) => { ... } defines an arrow function named greet.
The part inside the parentheses (name) is called a parameter — it acts like a placeholder for any value you pass in.
The curly braces { ... } contain the code block, which is the set of instructions that will run when the function is called.
Inside the block, we use a return statement to send a value back to whoever called the function.
Finally, when we write greet("Sadia"), we call (or invoke) the function, which triggers the code to run and outputs the greeting.