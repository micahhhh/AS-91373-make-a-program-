#mmmmmmmmm think it finally works, not fully sure yet though.
#26/05/2017
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
  guesses_taken = 0
  while guesses_taken == 0 and guesses_taken < 10:
      for i in range(0,10):
        guess = input('what letter shall you guess? ')
        if guess is not word:
          for char in word:
            if char in guess:
                print(char)
                guesses_taken = guesses_taken + 1
            else:
                print("_")
                guesses_taken = guesses_taken + 1
        if guess is not word:
            if guesses_taken == 10:
                if guesses_taken > 10:
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
