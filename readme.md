# The Ghostbuster game

* First the game asks the question Gozer asks the boys
* I initially had trouble with the user response due to case sensitivity, however googling came to the rescue


## Case sensitivity
### The var is stored as 'yes', so to fix the user's input, I used the
### method .toLowerCase()
```javascript
if (guess.toLowerCase() === answer) {
'''
