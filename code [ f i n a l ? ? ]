#Finally
import random #this is used later, to pick a word out of the list below
wordlist = ['fragment','life','penguin','empathetic','bloody','perverted','eternity','alibi','fragile','cursed','suicide','aesthetic','vaporwave']
guessing = True #this is indicating whether or not the game is still going
won = False #indicates whether the user won
lost = False #indicates if the user lost

def games(): #module for the number of games the user wants
    games = input('how many games do you want to play? ')#asks how much games the user wants to play
    return games

def word(): #module for what word is used
    global word #this is so that the word can be used anywhere
    word = (random.choice(wordlist)) #picks a random word out of the wordlist

def guesses(): #this plays the part of the rest of the hangman game
    guesses = 0
    while guesses < 10: #makes sure that you have ten guesses
        guess = input('what letter shall you guess? ') #asks the user for an input
        if guess != word: #if the guess isn't the word
            guesses = guesses + 1 #adds one to the previously 0 number of guesses
            for char in word: #for the number of characters in the word
                if char in guess: #if the characters are in the guess made
                    print(char) #prints out the characters that are in the word
                else:
                    print('_') #prints the number of characters in the word       
        print("You've taken {} guesses so far.".format(guesses))#is used so you know how much guesses you have
        if guess == word: #is if the guess is the word
            guesses == 10 #guess are ten so that you're then finished with the game
            print("Well done, you guessed the word.")
            won == True #the user won the game
            guessing == False #they're no longer guessing
            print("The game's now over. Thanks for playing!")
            exit()
        elif guesses == 10 and guess != word:#if you've had ten guesses and the word wasn't guessed
            print("you couldn't guess the word, which was {}".format(word))#tells you what the word was
            lost == True #indicates that you lost
            guessing == False #you're no longer guessing
            print("The game's now over. Thanks for playing!")
            exit()

#The below commands are used to put the modules into action
games()
word()
guesses()
