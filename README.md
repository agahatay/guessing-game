We Build a Number guessing game, in which the user selects a range.
Let’s say User selected a range, i.e., from A to B, where A and B belong to Integer.
Some random integer will be selected by the system and the user has to guess that integer in the minimum number of guesses

Step-by-step algorithm:

User inputs the lower bound and upper bound of the range.
The compiler generates a random integer between the range and store it in a variable for future references.
For repetitive guessing, a while loop will be initialized.
If the user guessed a number which is greater than a randomly selected number, the user gets an output “Try Again! You guessed too high“
Else If the user guessed a number which is smaller than a randomly selected number, the user gets an output “Try Again! You guessed too small”
And if the user guessed in a minimum number of guesses, the user gets a “Congratulations! ” Output.
Else if the user didn’t guess the integer in the minimum number of guesses, he/she will get “Better Luck Next Time!” output.
