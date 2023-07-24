# Guess_the-_number
import random
num = random.randint(10,50)
i = 0
while i < 5:
    guess = int(input("Guess a number in range 10..50:"))
    if guess == num:
        print("You win!!!!")
        break
    else:
        i = i + 1
if not i < 5:
    print("You lose:(\n The number was",num)
