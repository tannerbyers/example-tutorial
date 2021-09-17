# How to make a simple JavaScript quiz
## What you'll create: 

https://codepen.io/yaphi1/pen/NpZvJp
![finished result quiz](https://github.com/tannerbyers/example-tutorial/blob/master/finished_result_quiz.png?raw=true)
### To make a simple JavaScript quiz, there are four steps:

1. Set up the structure
2. Show the questions
3. On submit, show the results
4. Put it all together

The point of this tutorial is to make the simplest possible JavaScript quiz without any external code needed.

We'll also avoid animations, excessive styles, and anything else that will distract from the JavaScript quiz.

### A Quick Note Before You Start:

This tutorial assumes a basic understanding of JavaScript. If you're not there yet, I've put together [a JavaScript road map to get you comfortable with practical concepts quickly.](https://simplestepscode.com/learn-javascript/)

## Step 1: Set up the structure

First, we'll create divs to hold our quiz and our results.

Then we'll put in a submit button.

Next, we'll create a function to generate a quiz.

Your function will need these inputs:

* The quiz questions
* A place to put the quiz
* A place for the results
* A submit button

And if you put those things in, the function should spit out a fully-formed quiz.

**If you look closely at the JavaScript structure, you'll see that our generateQuiz function contains helper functions to show the quiz, accept submissions, and show the results.**

## Step 2: Show the questions

First we'll need the questions.

Next we'll need a way to show our questions.

For this, we'll fill out our showQuestions function.

### The general idea:
For each question, show the question along with all of its answer choices. Read through the comments in this code to see how it works.

The nice part about our code is that it works for any number of questions or answer choices you might have in your JavaScript quiz.

