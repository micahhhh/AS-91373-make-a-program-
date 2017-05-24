#19/05/2017
wordlist = ['fragment', 'life', 'penguin', 'empathic', 'bloody', 'perverted', 'eternity', 'alibi', 'fragile', 'cursed']
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
  guesses_taken = 0
  while guesses_taken < 10:
    guess = input('what letter shall you guess? ')
    if guess is not word:
      for char in word:
        if char in guess:
          print(char)
          guesses_taken = guesses_taken + 1
        else:
          print("_")
    if guesses_taken == 10 and guess is not word:
         print("Your guessing days are over, fiend. The word you failed to guess was {}".format(word))
         break
    if guess == word:
      guesses == 10
      print("\( ' Ɛ ' \) Congratulations! You guessed the word! (/ ' 3 ' )/")
      win = True
      break
games_module()
word_chosen()
guesses()
