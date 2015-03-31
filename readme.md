# The Michael Jordan Game

* First the game asks the user how many championships Michael Jordan earned in his career.
#Next, once the user guesses the correct answer, he is treated to a bonus question, asking how many points Jordan scored in his career with the bulls.
#Once the user guesses the correct answer, he is congratulated.

#The game was originally about characters on "The Ghostbusters", but we changed games to enchance the UX.

## Case sensitivity
### The var is stored as 'yes', so to fix the user's input, I used the
### method .toLowerCase()
```javascript
if (guess.toLowerCase() === answer) {
'''
