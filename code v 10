#29/05/2017
wordlist = ['fragment', 'life', 'penguin', 'empathic', 'bloody', 'perverted', 'eternity', 'alibi', 'fragile', 'cursed', 'suicide', 'aesthetic', 'vaporwave']
guessing = True
max_guess_no = 10
win = False
lost = False
def games_module():
  games = (input('how many games do you want to play? '))
  return games
def word_chosen():
  global word
  import random
  word = (random.choice(wordlist))
def guesses():
    guesses = 0
    while guesses == 0 and guesses < max_guess_no:
        for i in range(0,10):
            guess = input('what letter shall you guess? ')
            if guess != word:
                if guesses == max_guess_no:
                    print("you couldn't guess the word, which was {}".format(word))
                for char in word:
                    if char in guess:
                        print(char)
                        guesses = guesses + 1
                    else:
                        print("_")
                        guesses = guesses + 1
            if guess == word:
                guesses == 10
                print("\( ' Ɛ ' \) Congratulations! You guessed the word! (/ ' 3 ' )/")
                win = True                
games_module()
word_chosen()
guesses()
