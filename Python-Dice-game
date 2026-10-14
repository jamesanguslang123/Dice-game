import random

playAgain = input("Do you want to play a game (yes/no)? ").lower()

while playAgain == "yes":

    print("\nThe game is: You need to land on an even number!")
    print("🎲 Roll the dice! Evens add 1 point.")
    print("Keep rolling to build your score, but land on an odd")
    print("number and your points reset! Most points wins.\n")

    points = 0
    pointsTwo = 0
    roll = "yes"

    # Player One's turn
    print("Player One's turn!")

    while roll == "yes":
        diceNumber = random.randint(1, 6)
        print(f"\nThe number you landed on was: {diceNumber}")

        if diceNumber % 2 == 0:
            print("Your number was even! +1 point!")
            points += 1
            roll = input("Do you want to risk it again (yes/no)? ").lower()
        else:
            print("Your number was odd! Unlucky! Your points reset!")
            points = 0
            roll = "no"

    print(f"\nPlayer One's final score: {points} points!\n")

    # Player Two's turn
    print("Player Two's turn!")
    roll = "yes"

    while roll == "yes":
        diceNumber = random.randint(1, 6)
        print(f"\nThe number you landed on was: {diceNumber}")

        if diceNumber % 2 == 0:
            print("Your number was even! +1 point!")
            pointsTwo += 1
            roll = input("Do you want to risk it again (yes/no)? ").lower()
        else:
            print("Your number was odd! Unlucky! Your points reset!")
            pointsTwo = 0
            roll = "no"

    print(f"\nPlayer Two's final score: {pointsTwo} points!\n")

    # Decide the winner
    if points > pointsTwo:
        print("Congratulations Player One! You have won!")
    elif pointsTwo > points:
        print("Congratulations Player Two! You have won!")
    else:
        print("Equal points = Draw!")

    # Ask whether to play again
    playAgain = input("\nDo you want to play again (yes/no)? ").lower()

print("\nThanks for playing!")
