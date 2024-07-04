# 81-python-projects

## Introduction
My code from working with THE BIG BOOK OF SMALL PYTHON PROJECTS.
The projects are in alphabetical order but youll notice stars (:star:) next to the more complex projects. more stars being more complex

---
## Getting Started

Install Python 3 using Homebrew or your fav package manager:

1. **Install Homebrew** (if you haven't already):

   - Run the following command to install Homebrew:
     ```sh
     /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
     ```

2. **Install Python 3**:
   - Run the following command to install Python 3:
     ```sh
     brew install python
     ```

3. **Verify the Installation**:
   - After the installation is complete, run the following command to ensure Python 3 is installed correctly:
     ```sh
     python3 --version
     ```
   - You should see output indicating the version of Python 3 that is installed, such as:
     ```sh
     Python 3.x.x
     ```

4. **Git Clone**
    - Use Git Clone to get the directory of projects
    ```sh
    git clone git@github.com:GnarlyLasagna/81-python-projects.git
    ```

5. **Cd in and use script**
    -Cd into the directory of the desired project:
    ```sh
    cd bagels
    ```

    ```sh
    python3 bagels.py
    ```

---
## Table of Contents
1. [Bagels](#Bagels)
2. [Birthday Paradox](#Birthday-Paradox)
3. [Bitmap Message](#Bitmap-Message)
4. [Blackjack](#blackjack)
5. [Bouncing DVD Logo](#bouncing-dvd-logo)
6. [Caesar Cipher](#caesar-cipher)
7. [Caesar Hacker](#caesar-hacker)
8. [Calendar Maker](#calendar-maker)
9. [Carrot In A Box](#carrot-in-a-box)
10. [Cho-Han](#cho-han)
11. [Clickbait Headline Generator](#clickbait-headline-generator)
12. [Collatz Sequence](#collatz-sequence)
13. [Conways Game Of Life](#conways-game-of-life)
14. [Countdown](#countdown)
15. [Deep Cave](#deep-cave)
16. [Diamonds](#diamonds)
17. [Dice Math](#dice-math)
18. [Dice Roller](#dice-roller)
19. [Digital Clock](#digital-clock)
20. [Digital Stream](#digital-stream)
21. [DNA Visualization](#dna-visualization)
22. [Ducklings](#ducklings)
23. [Etching Drawer](#etching-drawer)
24. [Factor Finder](#factor-finder)
25. [Fast Draw](#fast-draw)
26. [Fibonacci](#fibonacci)
27. [Fish Tank](#fish-tank)
28. [Flooder](#flooder)
29. [Forest Fire Sim](#forest-fire-sim)
30. [Four In A Row](#four-in-a-row)
31. [Guess The Number](#guess-the-number)
32. [Gullible](#gullible)
33. [Hacking Minigame](#hacking-minigame)
34. [Hangman And Guillotine](#hangman-and-guillotine)
35. [Hex Grid](#hex-grid)
36. [Hourglass](#hourglass)
37. [Hungry Robots](#hungry-robots)
38. [J'accuse!](#jaccuse)
39. [Langton's Ant](#langtons-ant)
40. [Leetspeak](#leetspeak)
41. [Lucky Stars](#lucky-stars)
42. [Magic Fortune Ball](#magic-fortune-ball)
43. [Mancala](#mancala)
44. [Maze Runner 2D](#maze-runner-2d)
45. [Maze Runner 3D](#maze-runner-3d)
46. [Million Dice Roll Statistics Simulator](#million-dice-roll-statistics-simulator)
47. [Mondrian Art Generator](#mondrian-art-generator)
48. [Monty Hall Problem](#monty-hall-problem)
49. [Multiplication Table](#multiplication-table)
50. [Ninety-Nine Bottles](#ninety-nine-bottles)
51. [Ninety-Nniine Boottels](#ninety-nniine-boottels)
52. [Numeral System Counters](#numeral-system-counters)
53. [Periodic Table Of The Elements](#periodic-table-of-the-elements)
54. [Pig Latin](#pig-latin)
55. [Powerball Lottery](#powerball-lottery)
56. [Prime Numbers](#prime-numbers)
57. [Progress Bar](#progress-bar)
58. [Rainbow](#rainbow)
59. [Rock Paper Scissors](#rock-paper-scissors)
60. [Rock Paper Scissors (Always Win Version)](#rock-paper-scissors-always-win-version)
61. [Rot13 Cipher](#rot13-cipher)
62. [Rotating Cube](#rotating-cube)
63. [Royal Game of Ur](#royal-game-of-ur)
64. [Seven-Segment Display Module](#seven-segment-display-module)
65. [Shining Carpet](#shining-carpet)
66. [Simple Substitution Cipher](#simple-substitution-cipher)
67. [Sine Message](#sine-message)
68. [Sliding tile puzzle](#sliding-tile-puzzle)
69. [Snail race](#snail-race)
70. [Soroban Japanese Abacus](#soroban-japanese-abacus)
71. [Sound Mimic](#sound-mimic)
72. [Spongecase](#spongecase)
73. [Sudoku puzzle](#sudoku-puzzle)
74. [Text-to-speech talker](#text-to-speech-talker)
75. [Three-card monte](#three-card-monte)
76. [Tic-tac-toe](#tic-tac-toe)
77. [Tower of Hanoi](#tower-of-hanoi)
78. [Trick Questions](#trick-questions)
79. [Twenty Fourty-Eight](#twenty-fourty-eight)
80. [Vigenere Cipher](#vigenere-cipher)
81. [Water Bucket Puzzle](#water-bucket-puzzle)


---
## Bagels

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/bagels/bagels.py)

In Bagels, a deductive logic game, you
must guess a secret three-digit number
based on clues. The game offers one of
the following hints in response to your guess:
“Pico” when your guess has a correct digit in the
wrong place, “Fermi” when your guess has a correct
digit in the correct place, and “Bagels” if your guess
has no correct digits. You have 10 tries to guess the
secret number.

---
## Birthday Paradox

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/birthdayParadox/birthdayParadox.py)

The Birthday Paradox, also called the
Birthday Problem, is the surprisingly high
probability that two people will have the
same birthday even in a small group of people.
In a group of 70 people, there’s a 99.9 percent chance
of two people having a matching birthday. But even
in a group as small as 23 people, there’s a 50 percent
chance of a matching birthday. This program performs several probability experiments to determine
the percentages for groups of different sizes. We call these types of experiments, in which we conduct multiple random trials to understand the
likely outcomes, Monte Carlo experiments.

---
## Bitmap Message

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/bitmapMessage/bitmapMessage.py)

This program uses a multiline string as a
bitmap, a 2D image with only two possible
colors for each pixel, to determine how it
should display a message from the user. In this
bitmap, space characters represent an empty space,
and all other characters are replaced by characters in
the user’s message. The provided bitmap resembles
a world map, but you can change this to any image
you’d like. The binary simplicity of the space-or-message-characters
system makes it good for begin-
ners. Try experimenting with different messages to
see what the results look like!

---
## Blackjack
:star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/blackJack/blackJack.py)

Blackjack, also known as 21, is a card game
where players try to get as close to 21 points
as possible without going over. This program
uses images drawn with text characters, called
ASCII art. American Standard Code for Information
Interchange (ASCII) is a mapping of text characters
to numeric codes that computers used before Unicode
replaced it.

---
## Bouncing DVD Logo

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/bouncingDvd/bouncingDvd.py)

If you are of a certain age, you’ll remember
those ancient technological devices called
DVD players. When not playing DVDs, they
would display a diagonally traveling DVD logo
that bounced off the edges of the screen. This program simulates this colorful DVD logo by making it
change direction each time it hits an edge. We’ll also
keep track of how many times a logo hits a corner of
the screen. This creates an interesting visual animation to look at, especially for the magical moment
when a logo lines up perfectly with a corner.

You can’t run this program from your integrated development environment (IDE) or editor because it uses the bext module. Therefore, it must be
run from the Command Prompt or Terminal in order to display correctly.
You can find more information about the bext module at https://pypi.org/
project/bext/.

---
## Caeser Cipher

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/caesarCipher/caesarCipher.py)

The Caesar cipher is an ancient encryption algorithm used by Julius Caesar. It
encrypts letters by shifting them over by a
certain number of places in the alphabet. We
call the length of shift the key. For example, if the
key is 3, then A becomes D, B becomes E, C becomes
F, and so on. To decrypt the message, you must shift
the encrypted letters in the opposite direction. This
program lets the user encrypt and decrypt messages
according to this algorithm.

In modern times, the Caesar cipher isn’t very sophisticated, but that
makes it ideal for beginners. The program in Project 7, “Caesar Hacker,”
can brute-force through all 26 possible keys to decrypt messages, even if
you don’t know the original key. Also, if you encrypt the message with the
key 13, the Caesar cipher becomes identical to Project 61, “ROT 13 Cipher.”

Learn more about the Caesar cipher at https://en.wikipedia.org/wiki/Caesar_
cipher. If you’d like to learn about ciphers and code breaking in general, you
can read my book Cracking Codes with Python (No Starch Press, 2018; https://
nostarch.com/crackingcodes/).

---
## Caeser Hacker

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/caesarHacker/caesarHacker.py)

This program can hack messages encrypted
with the Caesar cipher from Project 6, even
if you don’t know the key. There are only 26
possible keys for the Caesar cipher, so a computer can easily try all possible decryptions and display the results to the user. In cryptography, we call
this technique a brute-force attack.

---
## Calendar Maker

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/calendarMaker/calendarMaker.py)

This program generates printable text
files of monthly calendars for the month
and year you enter. Dates and calendars are
a tricky topic in programming because there
are so many different rules for determining the number of days in a month, which years are leap years,
and which day of the week a particular date falls on.
Fortunately, Python’s datetime module handles these
details for you. This program focuses on generating
the multiline string for the monthly calendar page.

---
## Carrot In A Box
:star: :star: 
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/carrotInABox/carrotInABox.py)

This is a simple and silly bluffing game for
two human players. Each player has a box.
One box has a carrot in it, and each player
wants to have the carrot. The first player looks
in their box and then tells the second player they
either do or don’t have the carrot. The second

---
## Cho-Han

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/choHan/choHan.py)

Cho-han is a dice game played in gambling
houses of feudal Japan. Two six-sided dice
are rolled in a cup, and gamblers must guess
if the sum is even (cho) or odd (han). The
house takes a small cut of all winnings. The simple
random number generation and basic math used to
determine odd or even sums make this project especially suitable for beginners. More information about
Cho-han can be found at https://en.wikipedia.org/wiki/
Cho-han.

---
## Clickbait Headline Generator
:star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/clickBaitHeadlineGenerator/clickBaitHeadlineGenerator.py)

Our website needs to trick people into
looking at advertisements! But coming up
with creative, original content is too hard.
Luckily, with the clickbait headline generator,
we can make a computer come up with millions of
outrageous fake headlines. They’re all low quality, but
readers don’t seem to mind. This program generates
as many headlines as you need from a Mad Libs–style
template.

---
## Collatz Sequence

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/collatzSequence/collatzSequence.py)

The Collatz sequence, also called the 3n + 1
problem, is the simplest impossible math
problem. (But don’t worry, the program
itself is easy enough for beginners.) From a
starting number, n, follow three rules to get the next
number in the sequence:
1. If n is even, the next number n is n / 2.
2. If n is odd, the next number n is n * 3 + 1.
3. If n is 1, stop. Otherwise, repeat.

---
## Conways Game Of Life

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/conwaysGameOfLife/conwaysGameOfLife.py)

Conway’s Game of Life is a cellular automata simulation that follows simple rules to
create interesting patterns. It was invented
by mathematician John Conway in 1970 and
popularized by Martin Gardner’s “Mathematical
Games” column in Scientific American. Today, it’s a
favorite among programmers and computer scientists,
though it’s more an interesting visualization than a true “game.” The two dimensional board has a grid of “cells,” each of which follows three simple
rules:
• Living cells with two or three neighbors stay alive in the next step of the
simulation.
• Dead cells with exactly three neighbors become alive in the next step of
the simulation.
• Any other cell dies or stays dead in the next step of the simulation.

The living or dead state of the cells in the next step of the simulation depends entirely on their current state. The cells don’t “remember”
any older states. There is a large body of research regarding the patterns
that these simple rules produce. Tragically, Professor Conway passed
away of complications from COVID-19 in April 2020. More information
about Conway’s Game of Life can be found at https://en.wikipedia.org/wiki/
Conway%27s_Game_of_Life, and more information about Martin Gardner at
https://en.wikipedia.org/wiki/Martin_Gardner.


---
## Countdown

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/countDown/countDown.py)

This program displays a digital timer that
counts down to zero. Rather than ­ render
numeric characters directly, the sevseg.py
­ module from Project 64, “Seven-Segment
Display Module,” generates the drawings for each
digit. You must create this file before the Countdown
program can work. Then, set the countdown timer to
any number of seconds, minutes, and hours you like.
This program is similar to Project 19, “Digital Clock.”


---
## Deep Cave

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/deepCave/deepCave.py)

This program is an animation of a deep
cave that descends forever into the earth.
Although short, this program takes advantage of the scrolling nature of the computer
screen to produce an interesting and unending visualization, proof that it doesn’t take much code to produce something fun to watch. This program is similar
to Project 58, “Rainbow.”


---
## Diamonds

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/diamonds/diamonds.py)

This program features a small algorithm
for drawing ASCII-art diamonds of various sizes. It contains functions for drawing
either an outline or filled-in-style diamond of
the size you dictate. These functions are good practice
for a beginner; try to understand the pattern behind
the diamond drawings as they increase in size.

---
## Dice Math
:star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/diceMath/diceMath.py)

This math quiz program rolls two to six
dice whose sides you must add up as quickly
as possible. But this program operates as
more than just automated flash cards; it draws
the faces of the dice to random places on the screen.
The ASCII-art aspect adds a fun twist while you practice arithmetic.

---
## Dice Roller

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/diceRoller/diceRoller.py)

Dungeons & Dragons and other tabletop
role-playing games use special dice that
can have 4, 8, 10, 12, or even 20 sides. These
games also have a specific notation for indicating which dice to roll. For example, 3d6 means rolling three six-sided dice, while 1d10+2 means rolling
one ten-sided die and adding a two-point bonus to
the roll. This program simulates this dice rolling, in
case you forgot to bring your own. It can also simulate rolling dice that don’t physically exist, such as a
38-sided die.

---
## Digital Clock

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/digitalClock/digitalClock.py)

This program displays a digital clock
with the current time. Rather than render numeric characters directly, the
sevseg.py module from Project 64, “Seven-Segment Display Module,” generates the drawings
for each digit. This program is similar to Project 14,
“Countdown.”

---
## Digital Stream

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/digitalStream/digitalStream.py)

This program mimics the “digital stream”
visualization from the science fiction movie
The Matrix. Random beads of binary “rain”
stream up from the bottom of the screen, creating a cool, hacker-like visualization. (Unfortunately,
due to the way text moves as the screen scrolls down,
it’s not possible to make the streams fall downward
without using a module such as bext.)

---
## DNA Visualization

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/dnaVisualization/dnaVisualization.py)

Deoxyribonucleic acid is a tiny molecule
that exists in every cell of our bodies and
contains the blueprint for how our bodies grow. It looks like a double helix (a sort of
twisted ladder) of pairs of nucleotide molecules:
­ guanine, cytosine, adenine, and thymine. These are
represented by the letters G, C, A, and T. DNA is a
long molecule; it’s microscopic, but if it were stretched
out, its 3 billion base pairs would be 2 meters long!
This program is a simple animation of DNA.

---
## Ducklings
:star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/ducklings/ducklings.py)

This program creates a scrolling field of
ducklings. Each duckling has slight variations: they can face left or right and have
two different body sizes, four types of eyes, two
types of mouths, and three positions for their wings.
This gives us 96 different possible variations, which
the Ducklings program produces endlessly.

---
## Etching Drawer
:star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/etchingDrawer/etchingDrawer.py)

When you move a pen point around the
screen with the WASD keys, the etching
drawer forms a picture by tracing a continu-
ous line, like the Etch A Sketch toy. Let your
artistic side break out and see what images you can
create! This program also lets you save your draw-
ings to a text file so you can print them out later.
Plus, you can copy and paste the WASD movements
of other drawings into this program, like the WASD
commands for the Hilbert Curve fractal presented on
lines 6 to 14 of the source code.

---
## Factor Finder

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/factorFinder/factorFinder.py)

A number’s factors are any two other num-
bers that, when multiplied with each other,
produce the number. For example, 2 × 13 =
26, so 2 and 13 are factors of 26. Also, 1 × 26 =
26, so 1 and 26 are also factors of 26. Therefore, we
say that 26 has four factors: 1, 2, 13, and 26.
If a number only has two factors (1 and itself), we call that a prime
number. Otherwise, we call it a composite number. Use the factor finder to
discover some new prime numbers! (Hint: Prime numbers always end with
an odd number that isn’t 5.) You can also have the computer calculate them
with Project 56, “Prime Numbers.”

---
## Fast Draw

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/fastDraw/fastDraw.py)

This program tests your reaction speed:
press ENTER as soon as you see the word
DRAW. But careful, though. Press it before
DRAW appears, and you lose. Are you the fastest keyboard in the west?

---
## Fibonacci

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/fibonacci/fibonacci.py)

The Fibonacci sequence is a famous mathematical pattern credited to Italian mathematician Fibonacci in the 13th century
(though others had discovered it even earlier).
The sequence begins with 0 and 1, and the next number is always the sum of the previous two numbers.
The sequence continues forever:
0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, 233, 377, 610, 987 . . .
The Fibonacci sequence has applications in music composition, stock
market prediction, the pattern of florets in the head of sunflowers, and
many other areas. This program lets you calculate the sequence as high as
you are willing to go. More information about the Fibonacci sequence can
be found at https://en.wikipedia.org/wiki/Fibonacci_number.

---
## Fish Tank
:star: :star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/fishTank/fishTank.py)

Watch your own virtual fish in a virtual
fish tank, complete with air bubblers and
kelp plants. Each time you run the program,
it randomly generates the fish using different
fish types and colors. Take a break and enjoy the calm
serenity of this software aquarium, or try programming
in some virtual sharks to terrorize its inhabitants! You
can’t run this program from your IDE or editor. This
program uses the bext module and must be run from
the Command Prompt or Terminal in order to display
correctly. More information about the bext module can
be found at https://pypi.org/project/bext/.

---
## Flooder
:star: :star: 
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/flooder/flooder.py)

Flooder is a colorful game where a player
tries to fill the board with a single color
by changing the color of the tile in the
upper-left corner. This new color spreads to
all neighboring tiles that matched the original color.
It’s similar to the Flood It mobile game. This program
also has a colorblind mode, which uses shapes instead
of flat colored tiles. It relies on the recursive flood
fill algorithm to paint the board and works similarly
to the “paint bucket” or “fill” tool in many painting
applications.

---
## Forest Fire Sim

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/forestFireSim/forestFireSim.py)

This simulation shows a forest whose trees
are constantly growing and then being
burned down. On each step of the simulation, there is a 1 percent chance that a blank
space grows into a tree and a 1 percent chance that a
tree is struck by lightning and burns. Fires will spread
to adjacent trees, so a densely packed forest is more
likely to suffer a larger fire than a sparsely packed
one. This simulation was inspired by Nicky Case’s
Emoji Sim at http://ncase.me/simulating/model/.

---
## Four In A Row
:star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/fourInARow/fourInARow.py)

In this classic tile-dropping board game
for two players, you must try to get four of
your tiles in a row horizontally, vertically,
or diagonally, while preventing your opponent from doing the same. This program is similar
to Connect Four.

---
## Guess The Number

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/guessTheNumber/guessTheNumber.py)

Guess the Number is a classic game for
beginners to practice basic programming
techniques. In this game, the computer
thinks of a random number between 1 and 100.
The player has 10 chances to guess the number. After
each guess, the computer tells the player if it was too
high or too low.

---
## Gullible

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/gullible/gullible.py)

In this short and simple program, you can
learn the secret and subtle art of keeping
a gullible person busy for hours. I won’t
spoil the punch line here. Copy the code and
run it for yourself. This project is great for beginners,
whether you’re smart or . . . not so smart.

---
## Hacking Minigame
:star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/hackingMinigame/hackingMinigame.py)

In this game, the player must hack a computer by guessing a seven-letter word used
as the secret password. The computer’s memory banks display the possible words, and the
player is given hints as to how close each guess was.
For example, if the secret password is MONITOR but
the player guessed CONTAIN, they are given the hint
that two out of seven letters were correct, because both
MONITOR and CONTAIN have the letter O and N as
their second and third letter. This game is similar to
Project 1, “Bagels,” and the hacking minigame in the
Fallout series of video games.

---
## Hangman And Guillotine
:star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/hangmanAndGuillotine/hangmanAndGuillotine.py)

This classic word game has the player guess
the letters to a secret word. For each incorrect letter, another part of the hangman is
drawn. Try to guess the complete word before
the hangman completes. The secret words in this version are all animals like RABBIT and PIGEON, but
you can replace these with your own set of words.

---
## Hex Grid

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/hexGrid/hexGrid.py)

This short program produces a tessellated image of a hexagonal grid, similar to
chicken wire. It shows that you don’t need a
lot of code to make something interesting. A
slightly more complicated variation of this program is
Project 65, “Shining Carpet.”
Note that this program uses raw strings, which prefix the opening
quote with a lowercase r so that the backslashes in the string aren’t interpreted as escape characters.

---
## Hourglass
:star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/hourglass/hourglass.py)

This visualization program has a rough
physics engine that simulates sand falling
through the small aperture of an hourglass.
The sand piles up in the bottom half of the
hourglass; then the hourglass is turned over so the
process repeats.

---
## Hungry Robots
:star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/hungryRobots/hungryRobots.py)

You are trapped in a maze with hungry
robots! You don’t know why robots need
to eat, but you don’t want to find out. The
robots are badly programmed and will move
directly toward you, even if blocked by walls. You must
trick the robots into crashing into each other (or dead
robots) without being caught.
You have a personal teleporter device that can send you to a random
new place, but it only has enough battery for two trips. Also, you and the
robots can slip through corners!

---
## J'accuse!
:star: :star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/jaccuse/jaccuse.py)

You are the world-famous detective Mathilde
Camus. Zophie the cat has gone missing,
and you must sift through the clues. Suspects
either always tell lies or always tell the truth.
Will you find Zophie the cat in time and accuse the
guilty party?
In this game, you take a taxi to different locations around the city. At
each location is a suspect and an item. You can ask suspects about other
suspects and items, compare their answers with your own exploration notes,
and determine if they are lying or telling the truth. Some will know who has
catnapped Zophie (or where she is, or what item is found at the location of
the kidnapper), but you must determine if you can believe them. You have
five minutes to find the criminal but will lose if you make three wrong accusations. This game is inspired by Homestar Runner’s “Where’s an Egg?” game.

---
## Langton's Ant
:star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/langtonsAnt/langtonsAnt.py)

Langton’s Ant is a cellular automata simulation on a two-dimensional grid, similar to
Project 13, “Conway’s Game of Life.” In the
simulation, an “ant” begins on a square that is
one of two colors. If the space is the first color, the ant
switches it to the second color, turns 90 degrees to the
right, and moves forward one space. If the space is the
second color, the ant switches it to the first color, turns
90 degrees to the left, and moves forward one space.
Despite the very simple set of rules, the simulation displays complex emergent behavior. Simulations can feature multiple ants in the same space, causing interesting interactions when they cross paths with each other. Langton’s
Ant was invented by computer scientist Chris Langton in 1986. More infor-
mation about Langton’s Ant can be found at https://en.wikipedia.org/wiki/
Langton%27s_ant.

---
## Leetspeak

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/leetSpeak/leetSpeak.py)

There’s no better way to demonstrate your
mad hacker skills than by replacing letters in your text with numbers: m4d h4x0r
5k1llz!!! This word program automatically converts plain English into leetspeak, the coolest way to
talk online. Or at least it was in 1993.
It takes a while to get used to, but with some practice, you’ll eventually be able to read leetspeak fluently. For example, 1t +@]<3s 4 w|-|1le +o
g37 |_|s3|) 70, b|_|+ y0u (an 3\/3nt|_|/-\lly r3a|) l33t$peak phl|_|3n+ly.
Leetspeak may be hard to read at first, but the program itself is simple
and good for beginners. More information about leetspeak can be found
at https://en.wikipedia.org/wiki/Leet.

---
## Lucky Stars
:star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/luckyStars/luckyStars.py)

In this push-your-luck game, you roll dice
to collect stars. The more you roll, the more
stars you can get, but if you get three skulls
you lose everything! This quick multiplayer
game can support as many players as you want, making it ideal for parties.
On your turn, you pull three random dice from the dice cup and roll
them. You can roll Stars, Skulls, and Question Marks. If you end your
turn, you get one point per Star. If you choose to roll again, you keep the
Question Marks and pull new dice to replace the Stars and Skulls. If you
collect three Skulls, you lose all your Stars and end your turn.
When a player gets 13 points, everyone else gets one more turn before
the game ends. Whoever has the most points wins.
There are six gold dice, four silver dice, and three bronze dice in the
cup. Gold dice have more Stars, bronze dice have more Skulls, and silver
is even.

---
## Magic Fortune Ball

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/magicFortuneBall/magicFortuneBall.py)

The Magic Fortune Ball can predict the
future and answer your yes/no questions
with 100 percent accuracy using the power
of Python’s random number module. This program is similar to a Magic 8 Ball toy, except you don’t
have to shake it. It also features a function for slowly
printing text strings with spaces in between each character, giving the messages a spooky, mysterious effect.
Most of the code is dedicated to setting the eerie atmosphere. The
program itself simply selects a message to display in response to a random
number.

---
## Mancala
:star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/mancala/mancala.py)

The board game Mancala is at least 2,000
years old, making it almost as old as Project
63, “Royal Game of Ur.” It is a “seed-sowing”
game in which two players select pockets of
seeds to spread across the other pockets on the board
while trying to collect as many in their store as possible. There are several variants of this game across different cultures. The name comes from the Arab word
naqala, meaning “to move.”
To play, grab the seeds from a pit on your side of the board and place one
in each subsequent pit, going counterclockwise and skipping your opponent’s
store. If your last seed lands in an empty pit of yours, move the opposite pit’s
seeds into that pit. If the last placed seed is in your store, you get a free turn.
Mancala 207
The game ends when all of one player’s pits are empty. The other player
claims the remaining seeds for their store, and the winner is the one with
the most seeds. More information about Mancala and its variants can be
found at https://en.wikipedia.org/wiki/Mancala.

---
## Maze Runner 2D
:star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/mazeRunner2D/mazeRunner2D.py)

This two-dimensional maze runner shows
the player a top-down, bird’s-eye view of a
maze file you create in a text editor, such as
the IDE you use to write your .py files. Using
the WASD keys, the player can move up, left, down,
and right, respectively, to navigate the @ symbol
toward the exit marked by the X character.
To make a maze file, open a text editor and create the following pattern. Don’t type the numbers along the top and left side; they are only there
for reference:
123456789
1#########
2#S# # # #
3#########
4# # # # #
5#########

---
## Maze Runner 3D
:star: :star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/mazeRunner3D/mazeRunner3D.py)

This three-dimensional maze runner provides the player with a first-person view
from inside a maze. Try to find your way out!
You can generate maze files by following the
instructions in Project 44, “Maze Runner 2D,” or by
downloading maze files from https://invpy.com/mazes/.

---
## Million Dice Roll Statistics Simulator

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/millionDiceRollStatisticsSimulator/millionDiceRollStatisticsSimulator.py)

When you roll two six-sided dice, there’s
a 17 percent chance you’ll roll a 7. That’s
much better than the odds of rolling a 2: just
3 percent. That’s because there’s only one combination of dice rolls that gives you 2 (the one that
occurs when both dice roll a 1), but many combinations add up to seven: 1 and 6, 2 and 5, 3 and 4, and
so on.
But what about when you roll three dice? Or four? Or 1,000? You could
mathematically calculate the theoretical probabilities, or you can have
the computer roll a number of dice one million times to empirically figure them out. This program takes that latter approach. In this program,
you tell the computer to roll N dice one million times and remember the
results. It then displays the percentage chance of each sum.
This program does a massive amount of computation, but the computation itself isn’t hard to understand.

---
## Mondrian Art Generator
:star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/mondrianArtGenerator/mondrianArtGenerator.py)

Piet Mondrian was a 20th-century Dutch
painter and one of the founders of neoplasticism, an abstract art movement. His most
iconic paintings relied on blocks of primary
colors (blue, yellow, red), black, and white. Using a
minimalist approach, he separated these colors with
horizontal and vertical elements.
This program generates random paintings that follow Mondrian’s style.
You can find out more about Piet Mondrian at https://en.wikipedia.org/wiki/
Piet_Mondrian.

---
## Monty Hall Problem
:star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/montyHallProblem/montyHallProblem.py)

The Monty Hall Problem illustrates a surprising fact of probability. The problem
is loosely based on the old game show Let’s
Make a Deal and its host, Monty Hall. In the
Monty Hall Problem, you can pick one of three doors.
Behind one door is a prize: a new car. Each of the
other two doors opens onto a worthless goat. Say you
pick Door #1. Before the door you choose is opened,
the host opens another door (either #2 or #3), which leads to a goat. You
can choose to either open the door you originally picked or switch to the
other unopened door.
It may seem like it doesn’t matter if you switch or not, but your odds do
improve if you switch doors! This program demonstrates the Monty Hall
problem by letting you do repeated experiments.
To understand why your odds improve, consider a version of the Monty
Hall Problem with one thousand doors instead of three. You pick one door,
and then the host opens 998 doors, which all reveal goats. The only two
Monty Hall Problem 239
doors that are unopened are the one you selected and one other door. If
you correctly picked the car door to begin with (a 1 in a 1,000 chance), then
the host left a random goat door closed. If you picked a goat door (a 999 in
a 1,000 chance), the host specifically chose the car door to leave closed. The
choice of which doors to open isn’t random; the host knows to leave the car
door closed. It’s almost certain that you didn’t pick the car door to begin
with, so you should switch to the other door.
Another way to think of it is that you have 1,000 boxes and one box contains a prize. You guess which box the prize is in and the host puts it in your
hands. Do you think the prize is in your box or one of the 999 other boxes?
You don’t need the host to open 998 of the 999 boxes that don’t contain a
prize; the amount of choice is the same as with the 1,000 doors. The odds
that you guessed correctly in the beginning are 1 in 1,000, while the odds
that you did not (and that the prize is in one of the other boxes) is a near certain 999 in 1,000.
More information about the Monty Hall Problem can be found at
https://en.wikipedia.org/wiki/Monty_Hall_problem.

---
## Multiplication Table

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/multiplicationTable/multiplicationTable.py)

This program generates a multiplication
table from 0 × 0 to 12 × 12. While simple, it provides a useful demonstration of
nested loops.

---
## Ninety-Nine Bottles

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/ninetyNineBottles/ninetyNineBottles.py)

“Ninety-Nine Bottles” is a folk song of
undetermined origin known for its length
and repetitiveness. The lyrics go, “Ninety-
nine bottles of milk on the wall, ninety-nine
bottles of milk. Take one down, pass it around, ninety-
eight bottles of milk on the wall.” As the lyrics repeat,
the number of bottles falls from ninety-eight to ninety-
seven, then from ninety-seven to ninety-six, until it
reaches zero: “One bottle of milk on the wall, one
bottle of milk. Take it down, pass it around, no more bottles of milk
on the wall!”
Luckily for us, computers are excellent at performing repetitive
tasks, and this program reproduces all of the lyrics programmatically.
An extended version of this program is in Project 51, “niNety-nniinE
BoOttels.”

---
## Ninety-Nniine Boottels

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/ninetyNineBottles2/ninetyNineBottles2.py)

In this version of the song “Ninety-Nine
Bottles,” the program introduces small
imperfections in each stanza by either
removing a letter, swapping the casing of a
letter, transposing two letters, or doubling a letter.
As the song continues to play, these mutations add up, resulting in
a very silly song. It’s a good idea to try Project 50, “Ninety-Nine Bottles,”
before attempting this one.

---
## Numeral System Counters

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/numeralSystemCounters/numeralSystemCounters.py)

We’re used to counting in the decimal
numeral system, which uses 10 digits: 0
through 9. This system likely developed
because humans counted on their fingers, and
most people have 10 fingers. But other number systems exist. Computers make use of binary, a numeral
system with only two digits, 0 and 1. Programmers
also sometimes use hexadecimal, which is a base-16
numeral system that uses the digits 0 to 9 but also
extends into the letters A to F.
We can represent any number in any numeral system, and this program
displays a range of numbers in decimal, binary, and hexadecimal.

---
## Periodic Table Of The Elements

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/periodicTableOfElements/periodicTableOfElements.py)

The periodic table of the elements organizes all known chemical elements into
a single table. This program presents this
table and lets the player access additional
information about each element, such as its atomic
number, symbol, melting point, and so on. I compiled this information from Wikipedia and stored it
in a file called periodictable.csv that you can download
from https://inventwithpython.com/periodictable.csv.

---
## Pig Latin

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/pigLatin/pigLatin.py)

Pig Latin is a word game that transforms
English words into a parody of Latin. In
Pig Latin, if a word begins with a consonant,
the speaker removes this letter and puts it at
the end, followed by “ay.” For example, “pig” becomes
“igpay” and “latin” becomes “atinlay.” Otherwise,
if the word begins with a vowel, the speaker simply
adds “yay” to the end of it. For example, “elephant”
becomes “elephantyay” and “umbrella” becomes
“umbrellayay.”

---
## Powerball Lottery

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/powerballLottery/powerballLottery.py)

The Powerball Lottery is an exciting way to
lose small amounts of money. If you purchase a $2 ticket, you can pick six numbers:
five drawn from 1 to 69, and a sixth “Powerball”
number drawn from 1 to 26. The order of the num-
bers doesn’t matter. If the lottery selects your six numbers, you win $1.586 billion dollars! Except you won’t
win, because your odds are 1 in 292,201,338. But if you
spent $200 on 100 tickets, your odds would be . . . 1 in 2,922,013. You won’t
win that either, but at least you’ll lose 100 times as much money. The more
you like losing money, the more fun the lottery is!
To help you visualize how often you won’t win the lottery, this program
simulates up to one million Powerball drawings and then compares them
with the numbers you picked. Now you can have all the excitement of losing
the lottery without spending money.

Fun fact: every set of six numbers is just as likely to win as any other. So
the next time you want to buy a lottery ticket, pick the numbers 1, 2, 3, 4,
5, and 6. Those numbers are just as likely to come up as a more complex set.

---
## Prime Numbers

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/primeNumbers/primeNumbers.py)

A prime number is a number that is evenly
divisible only by one and itself. Prime numbers have a variety of practical applications,
but no algorithm can predict them; we must
calculate them one at a time. However, we do know
that there is an infinite number of prime numbers to
be discovered.
This program finds prime numbers through brute-force calculation.
Its code is similar to Project 24, “Factor Finder.” (Another way to describe
a prime number is that one and the number itself are its only factors.) You
can find out more about prime numbers from https://en.wikipedia.org/wiki/
Prime_number.

---
## Progress Bar

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/progressBar/progressBar.py)

A progress bar is a visual element that shows
how much of a task has been completed.
Progress bars are often used alongside downloading files or software installations. This project creates a getProgressBar() function that returns a
progress bar string based on the arguments passed to
it. It simulates a downloading file, but you can reuse
the progress bar code in your own projects.

---
## Rainbow

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/rainbow/rainbow.py)

Rainbow is a simple program that shows a
colorful rainbow traveling back and forth
across the screen. The program makes use
of the fact that when new lines of text appear,
the existing text scrolls up, causing it to look like it’s
moving. This program is good for beginners, and it’s
similar to Project 15, “Deep Cave.”

---
## Rock Paper Scissors

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/rockPaperScissors/rockPaperScissors.py)

In this version of the two-player hand game
also known as Rochambeau or jan-ken-pon,
the player faces off against the computer.
You can pick either rock, paper, or scissors.
Rock beats scissors, scissors beats paper, and paper
beats rock. This program adds some brief pauses for
suspense.
For a variation of this game, see Project 60, “Rock Paper Scissors
(Always-Win Version).”

---
## Rock Paper Scissors (Always Win Version)

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/rockPaperScissors2/rockPaperScissors2.py)

This variant of Rock Paper Scissors is identical to Project 59, “Rock Paper Scissors,”
except the player will always win. The code
selecting the computer’s move is set so that it
always chooses the losing move. You can offer this
game to your friends, who may be excited when they
win . . . at first. See how long it takes before they catch
on to the fact that the game is rigged in their favor.

---
## Rot13 Cipher

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/rot13Cipher/rot13Cipher.py)

The ROT13 cipher, one of the simplest
encryption algorithms, stands for “rotate
13 spaces.” The cypher represents the letters A to Z as the numbers 0 to 25 in such a way
that the encrypted letter is 13 spaces from the plaintext letter: A becomes N, B becomes O, and so on.
The encryption process is identical to the decryption
process, making it trivial to program. However, the
encryption is also trivial to break. Because of this,
you’ll most often find ROT13 used to conceal non-sensitive information,
such as spoilers or trivia answers, so it’s not read unintentionally. More
information about the ROT13 cipher can be found at https://en.wikipedia.org/
wiki/ROT13. If you’d like to learn about ciphers and code breaking more
generally, you can read my book Cracking Codes with Python (No Starch Press,
2018; https://nostarch.com/crackingcodes/).

---
## Rotating Cube
:star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/rotatingCube/rotatingCube.py)

This project features an animation of a
3D cube rotating using trigonometric functions. You can adapt the 3D point rotation
math and the line() function in your own animation programs.
Although the block text characters we’ll use to draw the cube don’t
look like thin, straight lines, this kind of drawing is called a wireframe model
because it renders only the edges of an object’s surfaces. Figure 62-1 shows
the wireframe model for a cube and an icosphere, a rough sphere made of
triangles.

---
## Royal Game of Ur
:star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/royalGameOfUr/royalGameOfUr.py)

The Royal Game of Ur is a 5,000-year-old
game from Mesopotamia. Archeologists
rediscovered the game in the Royal Cemetery
at Ur, in modern-day southern Iraq, during exca-
vations between 1922 and 1934. The rules were reconstructed from the game board (shown in Figure 63-1)
and a Babylonian clay tablet, and they’re similar to
Parcheesi. You’ll need both luck and skill to win.

Two players each begin with seven tokens in their home, and the first
player to move all seven to the goal is the winner. Players take turns throw-
ing four dice. These dice are four-pointed pyramid shapes called tetrahe-
drons. Each die has two marked points, giving an even chance that the dice
come up marked or unmarked. Instead of dice, our game uses coins whose
heads act as the marked point. The player can move a token one space for
each marked point that comes up. This means they can move a single token
between zero and four spaces, though they’re most likely to roll two spaces.
The tokens travel along the path indicated in Figure 63-2. Only one
token may exist on a space at a time. If a token lands on an opponent’s token
while in the shared middle path, the opponent’s token is sent back home. If
a token lands on the middle flower square, it is safe from being landed on.
If a token lands on any of the other four flower tiles, the player gets to roll
again. Our game will represent the tokens with the letters X and O.

---
## Seven-Segment Display Module

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/sevenSegmentDisplayModule/sevenSegmentDisplayModule.py)

A seven-segment display is a type of LCD
component used to display numbers in
pocket calculators, microwave ovens, and
other small electronic devices. Through differ-
ent combinations of seven line-shaped segments in an
LCD, a seven-segment display can represent the digits
0 through 9. They look like this:
```
__ __ __ __ __ __ __ __
| | | __| __| |__| |__ |__ | |__| |__|
|__| | |__ __| | __| |__| | |__| __|
```
The benefit of this program is that other programs can import it as a
module. Project 14, “Countdown,” and Project 19, “Digital Clock,” import
the sevseg.py file so they can use its getSevSegStr() function. You can find
more information about seven-segment displays and other variations at
https://en.wikipedia.org/wiki/Seven-segment_display.

---
## Shining Carpet

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/shiningCarpet/shiningCarpet.py)

The Shining, a 1980 psychological horror
film directed by Stanley Kubrick, takes
place at the haunted Overlook Hotel. The
hotel carpet’s hexagonal design became an
iconic part of this famous movie. The carpet features
alternating and interlocking hexagons whose mesmerizing effect is well-suited for such an unnerving
film. The short program in this project, similar to
Project 35, “Hex Grid,” prints this repetitive pattern
on the screen.
Note that this program uses raw strings, which prefix the opening
quote with a lowercase r, so that the backslashes in the string aren’t inter-
preted as escape characters.

---
## Simple Substitution Cipher

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/simpleSubstitutionCipher/simpleSubstitutionCipher.py)

The Simple Substitution Cipher substitutes
one letter for another. Since there are 26
possible substitutions for the letter A, 25 possible substitutions for B, 24 for C, and so on,
the total number of possible keys is 26 × 25 × 24 × 23 ×
. . . × 1, or 403,291,461,126,605,635,584,000,000 keys!
That’s far too many keys for even a supercomputer
to brute force, so the code-breaking method used
in Project 7, “Caesar Hacker,” can’t be used against
the simple cipher. Unfortunately, devious attackers
can take advantage of known weakness to break the code. If you’d like
to learn more about ciphers and code breaking, you can read my book
Cracking Codes with Python (No Starch Press, 2018; https://nostarch.com/
crackingcodes/).

---
## Sine Message

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/sineMessage/sineMessage.py)

This program displays a message of the
user’s choice in a wavy pattern as the text
scrolls up. It accomplishes this effect with
math.sin(), which implements the trigonometric sine wave function. But even if you don’t understand the math, this program is rather short and
easy to copy.

---
## Sliding Tile Puzzle
:star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/slidingTilePuzzle/slidingTilePuzzle.py)

This classic puzzle relies on a 4 × 4 board
with 15 numbered tiles and one free space.
The objective is to slide the tiles until the
numbers are in the correct order, going left to
right and top to bottom. Tiles can only slide; you’re
not allowed to directly pick them up and rearrange
them. Some versions of this puzzle toy feature scram-
bled images that form a complete picture once solved.
More information about sliding tile puzzles can be found at https://
en.wikipedia.org/wiki/Sliding_puzzle.

---
## Snail Race

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/snailRace/snailRace.py)

You won’t be able to handle the fast-paced
excitement of these racing . . . snails. But
what they lack in speed they make up for in
ASCII-art cuteness. Each snail (represented by
an @ character for the shell and v for the two eyestalks)
moves slowly but surely toward the finish line. Up to
eight snails, each with a custom name, can race each
other, leaving a slime trail in their wake. This program
is good for beginners.

---
## Soroban Japanese Abacus
:star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/sorobanJapaneseAbacus/sorobanJapaneseAbacus.py)

An abacus, also called a counting frame, is a
calculating tool used in many cultures long
before electronic calculators were invented.
Figure 70-1 shows the Japanese form of the abacus, called a soroban. Each wire represents a place in a
positional numeral system, and the beads on the wire
represent the digit at that place. For example, a soroban
with two beads moved over on the rightmost wire and
three beads moved over on the second-to-rightmost wire
would represent the number 32. This program simulates
a soroban. (The irony of using a computer to simulate a
pre-computer computing tool is not lost on me.)

Each column in the soroban represents a different digit. The rightmost
column is the ones place, the column to its left is the tens place, the column
to the left of that is the hundreds place, and so on. The Q, W, E, R, T, Y,
U, I, O, and P keys along the top of your keyboard can increase the digit at
their respective positions, while the A, S, D, F, G, H, J, K, L, and ; keys will
decrease them. The beads on the virtual soroban will slide to reflect the
current number. You can also enter numbers directly.
The four beads below the horizontal divider are “earth” beads, and lift-
ing them up against the divider counts as 1 for that digit. The bead above
the horizontal divider is a “heaven” bead, and pulling it down against the
divider counts as 5 for that digit, so pulling down one heaven bead and
pulling up three earth beads in the tens column represents the number
80. More information about abacuses and how to use them can be found at
https://en.wikipedia.org/wiki/Abacus.

---
## Sound Mimic

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/soundMimic/soundMimic.py)

Similar to the Simon electronic toy, this
memorization game uses the third-party
playsound module to play four different
sounds, which correspond to the A, S, D, and
F keys on the keyboard. As you successfully repeat the
pattern the game gives you, the patterns get longer
and longer. How many sounds can you hold in your
short-term memory?
If you look at the code, you’ll see that the playsound.playsound() function
is passed the filename of the sound to play. You can download the sound
files from these URLs:
https://inventwithpython.com/soundA.wav
https://inventwithpython.com/soundS.wav
https://inventwithpython.com/soundD.wav
https://inventwithpython.com/soundF.wav

Place these files in the same folder as soundmimic.py before running the
program. More information about the playsound module can be found at
https://pypi.org/project/playsound/. Users on macOS must also install the pyobjc
module from https://pypi.org/project/pyobjc/ for playsound to work.

---
## Spongecase

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/spongeCase/spongeCase.py)

You’ve probably seen the “Mocking
SpongeBob” meme: a picture of SpongeBob
SquarePants, with a caption whose text alternates between upper and lowercase letters to
indicate sarcasm, like this: uSiNg SpOnGeBoB MeMeS
dOeS NoT mAkE YoU wItTy. For some randomness,
the text sometimes doesn’t alternate capitalization.
This short program uses the upper() and lower() string methods to
convert your message into “spongecase.” The program is also set up so that
other programs can import it as a module with import spongecase and then
call the spongecase.englishToSpongecase() function.

---
## Sudoku Puzzle
:star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/sudokuPuzzle/sudokuPuzzle.py)

Sudoku is a popular puzzle game in newspapers and mobile apps. The Sudoku board
is a 9 × 9 grid in which the player must place
the digits 1 to 9 once, and only once, in each
row, column, and 3 × 3 subgrid. The game begins
with a few spaces already filled in with digits, called
givens. A well-formed Sudoku puzzle will have only
one possible valid solution.

---
## Text-To-Speech Talker

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/textToSpeechTalker/textToSpeechTalker.py)

This program demonstrates the use of the
pyttsx3 third-party module. Any message
you enter will be spoken out loud by your
operating system’s text-to-speech capabilities.
Although computer-generated speech is an incredibly complex branch of computer science, the pyttsx3
module provides an easy interface for it, making this
small program suitable for beginners. Once you’ve
learned how to use the module, you can add generated speech to your own programs.
More information about the pyttsx3 module can be found at https://
pypi.org/project/pyttsx3/.

---
## Three-Card Monte
:star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/threeCardMonte/threeCardMonte.py)

Three-card monte is a common scam
played on gullible tourists and other easy
marks. Three playing cards, one of which is
the “red lady” Queen of Hearts, are put facedown on a cardboard box. The dealer quickly rearranges the cards and then asks the mark to pick the
Queen of Hearts. But the dealer can use all sorts of
tricks to hide the card or otherwise cheat, guaranteeing that the victim never wins. It’s also common for
the dealer to have shills in the crowd who secretly work with the dealer but
pretend to win the game (to make the victim think they too could win)
or purposefully lose badly (to make the victim think they could do much
better).
This program shows the three cards and then quickly describes a series
of swaps. At the end, it clears the screen, and the player must pick a card.

Can you keep up with the “red lady”? For the authentic three-card monte
experience, you can enable the cheat feature, which causes the player to
always lose, even if they select the correct card.

---
## Tic-Tac-Toe

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/ticTacToe/ticTacToe.py)

Tic-tac-toe is a classic pencil-and-paper
game played on a 3 × 3 grid. Players take
turns placing their X or O marks, trying to
get three in a row. Most games of tic-tac-toe
end in a tie, but it is possible to outsmart your opponent if they’re not careful.

---
## Tower Of Hanoi

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/towerOfHanoi/towerOfHanoi.py)

The Tower of Hanoi is a stack-moving puzzle game that features three poles on which
you can stack various-sized disks. The object
of the game is to move one tower of disks to
another pole. However, only one disk can be moved
at a time, and larger disks cannot be placed on top of
smaller ones. Figuring out a certain pattern will help
you solve this puzzle. Can you discover it? (Hint: Try
setting the TOTAL_DISKS variable to 3 or 4 to solve an
easier version first.)

---
## Trick Questions
:star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/trickQuestions/trickQuestions.py)

What does a yellow stone thrown into a blue
pond become? Do they have a 4th of July in
England? How can a doctor go 30 days without sleep? Whatever you think the answers to
these trick questions are, you’re probably wrong. The
54 questions in this program have been specifically
crafted so that their answers are simple, obvious, and
misleading. Finding the true answer will require some
cleverness.
Copying the code from this book will spoil the fun, since you’ll see the
answers, so you might want to download and play this game from https://
inventwithpython.com/trickquestions.py before looking at the source code.

---
## Twenty Fourty-Eight
:star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/twentyFortyEight/twentyFortyEight.py)

Gabriele Cirulli, a web developer, invented
the game 2048 in one weekend. It was
inspired by Veewo Studios’ 1024 game,
which in turn was inspired by Threes!, a game
by the development team Sirvo. In 2048, you must
merge numbers on a 4 × 4 board to clear them from
the screen. Two 2s merge into a 4, two 4s merge into
an 8, and so on. The game adds a new 2 to the board
on each merging. The objective is to reach 2048
before the entire board fills up.

---
## Vigenere Cipher

[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/vigenereCipher/vigenereCipher.py)

The Vigenère cipher, misattributed to 19th-
century cryptographer Blaise de Vigenère
(others had independently invented it earlier), was impossible to crack for hundreds of
years. It is essentially the Caesar cipher, except it makes
use of a multipart key. The so-called Vigenère key is a
word, or even a random series of letters. Each letter
represents a number by which to shift the letter in the
message: A represents shifting a letter in the message
by 0, B represents 1, C represents 2, and so on.
For example, if a Vigenère key is the word “CAT,” the C represents a
shift of 2, the A represents 0, and the T represents 19. The first letter of the
message gets shifted by 2, the second letter by 0, and the third letter by 19.
For the fourth letter, we repeat the key of 2.
This use of multiple Caesar cipher keys is what gives the Vigenère cipher
its strength. The possible number of combinations is too big to brute force.

At the same time, the Vigenère cipher doesn’t suffer from the frequency
analysis weakness that can crack the simple substitution cipher. For centu-
ries, the Vigenère cipher represented the state of the art in cryptography.
You’ll notice many similarities between the code for the Vigenère and
Caesar cipher programs. More info about the Vigenère cipher can be found
at https://en.wikipedia.org/wiki/Vigen%C3%A8re_cipher. If you’d like to learn
more about ciphers and code breaking, you can read my book Cracking
Codes with Python (No Starch Press, 2018; https://nostarch.com/crackingcodes/).

---
## Water Bucket Puzzle
:star: :star:
[link to code](https://github.com/GnarlyLasagna/81-python-projects/blob/main/waterBucketPuzzle/waterBucketPuzzle.py)

In this solitaire puzzle game, you must use
three buckets (three-liter, five-liter, and
eight-liter buckets) to collect exactly four
liters of water in one of the buckets. Buckets
can only be emptied, completely filled, or poured
into another bucket. For example, you can fill the
five-liter bucket and then pour its contents into the
three-liter bucket, leaving you with a full three-liter
bucket and two liters of water in the five-liter bucket.
With some effort, you should be able to solve the puzzle. But can you
figure out how to solve it with the minimal number of moves?
