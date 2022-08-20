Exercise: Defensive programming
Defensive programming is all about assuming that all the arguments a function will receive are of the wrong type,  the wrong value or both.

In other words, you are assuming that things will go wrong and you are proactive in thinking about such scenarios before they happen, so as to make your function less likely to cause errors because of faulty inputs.

How would you then refactor the function given below with defensive programming in mind?

For this exercise, let's make sure that both of the arguments that are passed in satisfy the following criteria:

The length of the word parameter cannot be less than 2.

The length of the match parameter must be 1.

The type of both the word and the match parameters must be string.

You will use the code below to complete your task:
