#19/05/2017
wordlist = ['fragment', 'life', 'penguin', 'empathic', 'bloody', 'perverted', 'eternity', 'alibi', 'fragile', 'cursed']
guessing = True
max_guess_no = 10
win = False
lost = False
def games_module():
  games = input('how many games do you want to play?')
  games = int
  return games
def word_chosen():
  global word
  import random
  word = (random.choice(wordlist))
def guesses():
  guess = input("Have a guess, user. ")
  guesses_taken = 0
  while guesses_taken < 10:
    while guess is not word:
      for char in word:
        if char in guess:
          print(char)
          guesses_taken = guesses_taken + 1
        else:
          print("_")

      if guess == word:
        print("Congratulations! You guessed the word!")
        win = True
        break
games_module()
word_chosen()
guesses()
