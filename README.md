# PROGRAM16
import random
target_num = random.randint(1, 10)
guess_num = 0
while target_num != guess_num:
    guess_num = int(input('Guess a number between 1 and 10: '))
    if guess_num < target_num:
         print("Too low! Try again.")
    elif guess_num > target_num:
         print("Too high! Try again.")
print('Well guessed!')         
OUTPUT
 Guess a number between 1 and 10: 5
Too high! Try again.
Guess a number between 1 and 10: 
