# Rock-paper-scissors.py
import random as unknown_words
while True:
    choices = ["rock","paper","scissors"]
    computer = unknown_words.choice(choices)
    player = input("Enter your choice (rock, paper, scissors): ").lower()
    while player not in choices:
        player = (input("Invalid input, please enter those choice (rock, paper, scissors): ")).lower()
    if player == computer:
        print("Tie!")
    elif player == "rock" and computer == "scissors":
        print("Congratulations you win the game.")
    elif player == "paper" and computer == "rock":
        print("Congratulations you win the game.")
    elif player == "scissors" and computer == "paper":
        print("Congratulations you win the game.")
    else:
        print("Computer win the game.")
    print("Player chose:",player)
    print("Computer chose:",computer)
    play_again = input("Would you play this game again? (yes) for again (no) for exit: ").lower()
    if play_again != "yes":
        break
print("Bye user, have a nice day!")
