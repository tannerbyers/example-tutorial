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

# Step 3: On submit, show the results

We'll need to fill out our showResults function to show the results of our quiz.

Here's how our JavaScript logic will look:

    For each question, find the selected answer
    If the answer is correct, respond accordingly
    If the answer is wrong, respond accordingly
    Show the number of correct answers out of the total

In the line that says "//find selected answer", we did a little trick. We used the || operator, which means "or" to basically say "Give us the selected answer OR if there's not one, then just give us an empty object." That way, trying to get the .value will give us undefined instead of causing an error.

That way, the quiz won't break if someone skips a question.
Show quiz results on submit

The next step is to show quiz results when someone clicks the submit button.

    Note that the submitButton variable comes from our original generateQuiz function as one of the parameters.

# Step 4: Put it all together

Now that you have the pieces, you can generate your very own JavaScript quiz.

You have the questions in the myQuestions variable from Step 2. Now you need to let your JavaScript know which HTML elements to use for the quiz, the results, and the submit button.

Congrats!

# Bonus: The fun part

Now that you have the basic idea of how to make a JavaScript quiz, you can try styling the elements however you want.

Feel free to change whatever you want!