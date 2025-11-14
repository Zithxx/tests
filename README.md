# tests
print("Welcome to Treasure Island.\n Your mission is to find the treasure.")
choice1 = input("You're at a crossroad. Where do you want to go?\n Type 'Left' or 'Right': ").lower()
if choice1 == 'left':
  choice2 = input("You've come to a lake. There is a island in the middle of the lake.\n Type 'wait' to wait for a boat. Type 'swim' to swim across: ").lower()
  if choice2 == 'wait':
    choice3 = input("You've arrived at the island unharmed. There is a house with 3 doors.\n One red, one yellow and one blue.\n Which colour do you choose? ").lower()
    if choice3 == 'red':
      print("It's a room full of fire. Game Over.")
    elif choice3 == 'blue':
      print("You enter a room of beasts. Game Over.")
    elif choice3 == 'yellow':
      print("You found the treasure! You Win!")
    else:
      print('You choose a door that doesnt exist! Game over!')
  else:
    print('Hell is here. Game over')
else:
  print("You fell into a hole. Game Over.")
