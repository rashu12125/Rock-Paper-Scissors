# Rock-Paper-Scissors
import random
print("===================")
print("Rock Paper Scissors")
print("===================")
print("1) ✊")
print("2) ✋")
print("3) ✌️")


player = 0
computer = random.randint(1,3)

player = int(input("Pick a number: " ))


if player == 1 and computer == 1:
    player = "✊"
    computer = "✊"
    print("You chose:", player )
    print("CPU chose: ", computer)
    print("The Draw!")

elif player == 1 and computer == 2:
    player = "✊"
    computer = "✋"
    print("You chose:", player )
    print("CPU chose: ", computer)
    print("The computer Won!")

elif player == 1 and computer == 3:
    player = "✊"
    computer = "✌️"
    print("You chose:", player )
    print("CPU chose: ", computer)
    print("The player Won!")

elif player == 2 and computer == 1:
    player = "✋"
    computer = "✊"
    print("You chose:", player )
    print("CPU chose: ", computer)
    print("The player Won!")

elif player == 2 and computer == 2:
    player = "✋"
    computer = "✋"
    print("You chose:", player )
    print("CPU chose: ", computer)
    print("The  Draw!")

elif player == 2 and computer == 3:
    player = "✋"
    computer = "✌️"
    print("You chose:", player )
    print("CPU chose: ", computer)
    print("The computer Won!")

elif player == 3 and computer == 1:
    player = "✌️"
    computer = "✊"
    print("You chose:", player )
    print("CPU chose: ", computer)
    print("The computer Won!")

elif player == 3 and computer == 2:
    player = "✌️"
    computer = "✋"
    print("You chose:", player )
    print("CPU chose: ", computer)
    print("The player Won!")

elif player == 3 and computer == 3:
    player = "✌️"
    computer = "✌️"
    print("You chose:", player )
    print("CPU chose: ", computer)
    print("The  Draw!")

else:
    print("Invalid input")

