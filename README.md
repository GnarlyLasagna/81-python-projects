# 81-python-projects

**Bold Text**
*Italic Text*

## Introduction
My code from working with THE BIG BOOK OF SMALL PYTHON PROJECTS

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

## Table of Contents
1. [Bagels](#Bagels)
2. [Birthday Paradox](#Birthday-Paradox)
3. [Bitmap Message](#Bitmap-Message)

## Bagels

[test link to code page](https://github.com/GnarlyLasagna/81-python-projects/blob/main/bagels/bagels.py)

In Bagels, a deductive logic game, you
must guess a secret three-digit number
based on clues. The game offers one of
the following hints in response to your guess:
“Pico” when your guess has a correct digit in the
wrong place, “Fermi” when your guess has a correct
digit in the correct place, and “Bagels” if your guess
has no correct digits. You have 10 tries to guess the
secret number.

## Birthday Paradox

The Birthday Paradox, also called the
Birthday Problem, is the surprisingly high
probability that two people will have the
same birthday even in a small group of people.
In a group of 70 people, there’s a 99.9 percent chance
of two people having a matching birthday. But even
in a group as small as 23 people, there’s a 50 percent
chance of a matching birthday. This program per-
forms several probability experiments to determine
the percentages for groups of different sizes. We call these types of experi-
ments, in which we conduct multiple random trials to understand the
likely outcomes, Monte Carlo experiments.

## Bitmap Message

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

## Blackjack

Blackjack, also known as 21, is a card game
where players try to get as close to 21 points
as possible without going over. This program
uses images drawn with text characters, called
ASCII art. American Standard Code for Information
Interchange (ASCII) is a mapping of text characters
to numeric codes that computers used before Unicode
replaced it.

## Bouncing DVD Logo

If you are of a certain age, you’ll remember
those ancient technological devices called
DVD players. When not playing DVDs, they
would display a diagonally traveling DVD logo
that bounced off the edges of the screen. This pro-
gram simulates this colorful DVD logo by making it
change direction each time it hits an edge. We’ll also
keep track of how many times a logo hits a corner of
the screen. This creates an interesting visual anima-
tion to look at, especially for the magical moment
when a logo lines up perfectly with a corner.

You can’t run this program from your integrated development environ-
ment (IDE) or editor because it uses the bext module. Therefore, it must be
run from the Command Prompt or Terminal in order to display correctly.
You can find more information about the bext module at https://pypi.org/
project/bext/.

## Caeser Cipher

The Caesar cipher is an ancient encryp-
tion algorithm used by Julius Caesar. It
encrypts letters by shifting them over by a
certain number of places in the alphabet. We
call the length of shift the key. For example, if the
key is 3, then A becomes D, B becomes E, C becomes
F, and so on. To decrypt the message, you must shift
the encrypted letters in the opposite direction. This
program lets the user encrypt and decrypt messages
according to this algorithm.

## Caeser Hacker

This program can hack messages encrypted
with the Caesar cipher from Project 6, even
if you don’t know the key. There are only 26
possible keys for the Caesar cipher, so a com-
puter can easily try all possible decryptions and dis-
play the results to the user. In cryptography, we call
this technique a brute-force attack.

## Calendar Maker

This program generates printable text
files of monthly calendars for the month
and year you enter. Dates and calendars are
a tricky topic in programming because there
are so many different rules for determining the num-
ber of days in a month, which years are leap years,
and which day of the week a particular date falls on.
Fortunately, Python’s datetime module handles these
details for you. This program focuses on generating
the multiline string for the monthly calendar page.

## Carrot In A Box

This is a simple and silly bluffing game for
two human players. Each player has a box.
One box has a carrot in it, and each player
wants to have the carrot. The first player looks
in their box and then tells the second player they
either do or don’t have the carrot. The second

## Cho-Han

Cho-han is a dice game played in gambling
houses of feudal Japan. Two six-sided dice
are rolled in a cup, and gamblers must guess
if the sum is even (cho) or odd (han). The
house takes a small cut of all winnings. The simple
random number generation and basic math used to
determine odd or even sums make this project espe-
cially suitable for beginners. More information about
Cho-han can be found at https://en.wikipedia.org/wiki/
Cho-han.

## Clickbait Headline Generator

Our website needs to trick people into
looking at advertisements! But coming up
with creative, original content is too hard.
Luckily, with the clickbait headline generator,
we can make a computer come up with millions of
outrageous fake headlines. They’re all low quality, but
readers don’t seem to mind. This program generates
as many headlines as you need from a Mad Libs–style
template.

## Collatz Sequence

The Collatz sequence, also called the 3n + 1
problem, is the simplest impossible math
problem. (But don’t worry, the program
itself is easy enough for beginners.) From a
starting number, n, follow three rules to get the next
number in the sequence:
1. If n is even, the next number n is n / 2.
2. If n is odd, the next number n is n * 3 + 1.
3. If n is 1, stop. Otherwise, repeat.

## Conways Game Of Life

Conway’s Game of Life is a cellular autom-
ata simulation that follows simple rules to
create interesting patterns. It was invented
by mathematician John Conway in 1970 and
popularized by Martin Gardner’s “Mathematical
Games” column in Scientific American. Today, it’s a
favorite among programmers and computer scientists,
though it’s more an interesting visualization than a true “game.” The two-
dimensional board has a grid of “cells,” each of which follows three simple
rules:
• Living cells with two or three neighbors stay alive in the next step of the
simulation.
• Dead cells with exactly three neighbors become alive in the next step of
the simulation.
• Any other cell dies or stays dead in the next step of the simulation.
60 Project #13
The living or dead state of the cells in the next step of the simula-
tion depends entirely on their current state. The cells don’t “remember”
any older states. There is a large body of research regarding the patterns
that these simple rules produce. Tragically, Professor Conway passed
away of complications from COVID-19 in April 2020. More information
about Conway’s Game of Life can be found at https://en.wikipedia.org/wiki/
Conway%27s_Game_of_Life, and more information about Martin Gardner at
https://en.wikipedia.org/wiki/Martin_Gardner.


## Countdown

This program displays a digital timer that
counts down to zero. Rather than ­ render
numeric characters directly, the sevseg.py
­ module from Project 64, “Seven-Segment
Display Module,” generates the drawings for each
digit. You must create this file before the Countdown
program can work. Then, set the countdown timer to
any number of seconds, minutes, and hours you like.
This program is similar to Project 19, “Digital Clock.”


## Deep Cave

This program is an animation of a deep
cave that descends forever into the earth.
Although short, this program takes advan-
tage of the scrolling nature of the computer
screen to produce an interesting and unending visu-
alization, proof that it doesn’t take much code to pro-
duce something fun to watch. This program is similar
to Project 58, “Rainbow.”


## Diamonds

This program features a small algorithm
for drawing ASCII-art diamonds of vari-
ous sizes. It contains functions for drawing
either an outline or filled-in-style diamond of
the size you dictate. These functions are good practice
for a beginner; try to understand the pattern behind
the diamond drawings as they increase in size.

## Dice Math

This math quiz program rolls two to six
dice whose sides you must add up as quickly
as possible. But this program operates as
more than just automated flash cards; it draws
the faces of the dice to random places on the screen.
The ASCII-art aspect adds a fun twist while you prac-
tice arithmetic.

## Dice Roller

Dungeons & Dragons and other tabletop
role-playing games use special dice that
can have 4, 8, 10, 12, or even 20 sides. These
games also have a specific notation for indicat-
ing which dice to roll. For example, 3d6 means roll-
ing three six-sided dice, while 1d10+2 means rolling
one ten-sided die and adding a two-point bonus to
the roll. This program simulates this dice rolling, in
case you forgot to bring your own. It can also simu-
late rolling dice that don’t physically exist, such as a
38-sided die.

## Digital Clock

This program displays a digital clock
with the current time. Rather than ren-
der numeric characters directly, the
sevseg.py module from Project 64, “Seven-
Segment Display Module,” generates the drawings
for each digit. This program is similar to Project 14,
“Countdown.”

## Digital Stream

This program mimics the “digital stream”
visualization from the science fiction movie
The Matrix. Random beads of binary “rain”
stream up from the bottom of the screen, cre-
ating a cool, hacker-like visualization. (Unfortunately,
due to the way text moves as the screen scrolls down,
it’s not possible to make the streams fall downward
without using a module such as bext.)

## DNA Visualization

Deoxyribonucleic acid is a tiny molecule
that exists in every cell of our bodies and
contains the blueprint for how our bod-
ies grow. It looks like a double helix (a sort of
twisted ladder) of pairs of nucleotide molecules:
­ guanine, cytosine, adenine, and thymine. These are
represented by the letters G, C, A, and T. DNA is a
long molecule; it’s microscopic, but if it were stretched
out, its 3 billion base pairs would be 2 meters long!
This program is a simple animation of DNA.

## Ducklings

This program creates a scrolling field of
ducklings. Each duckling has slight varia-
tions: they can face left or right and have
two different body sizes, four types of eyes, two
types of mouths, and three positions for their wings.
This gives us 96 different possible variations, which
the Ducklings program produces endlessly.

## Etching Drawer

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

## Factor Finder

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

## First Draw

This program tests your reaction speed:
press ENTER as soon as you see the word
DRAW. But careful, though. Press it before
DRAW appears, and you lose. Are you the fast-
est keyboard in the west?

## Fibonacci

The Fibonacci sequence is a famous math-
ematical pattern credited to Italian math-
ematician Fibonacci in the 13th century
(though others had discovered it even earlier).
The sequence begins with 0 and 1, and the next num-
ber is always the sum of the previous two numbers.
The sequence continues forever:
0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, 233, 377, 610, 987 . . .
The Fibonacci sequence has applications in music composition, stock
market prediction, the pattern of florets in the head of sunflowers, and
many other areas. This program lets you calculate the sequence as high as
you are willing to go. More information about the Fibonacci sequence can
be found at https://en.wikipedia.org/wiki/Fibonacci_number.

## Fish Tank

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

## Flooder

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

## Forest Fire Sim

This simulation shows a forest whose trees
are constantly growing and then being
burned down. On each step of the simula-
tion, there is a 1 percent chance that a blank
space grows into a tree and a 1 percent chance that a
tree is struck by lightning and burns. Fires will spread
to adjacent trees, so a densely packed forest is more
likely to suffer a larger fire than a sparsely packed
one. This simulation was inspired by Nicky Case’s
Emoji Sim at http://ncase.me/simulating/model/.

## Four In A Row

In this classic tile-dropping board game
for two players, you must try to get four of
your tiles in a row horizontally, vertically,
or diagonally, while preventing your oppo-
nent from doing the same. This program is similar
to Connect Four.

## Guess The Number

Guess the Number is a classic game for
beginners to practice basic programming
techniques. In this game, the computer
thinks of a random number between 1 and 100.
The player has 10 chances to guess the number. After
each guess, the computer tells the player if it was too
high or too low.

## Gullible

In this short and simple program, you can
learn the secret and subtle art of keeping
a gullible person busy for hours. I won’t
spoil the punch line here. Copy the code and
run it for yourself. This project is great for beginners,
whether you’re smart or . . . not so smart.

## Hacking Minigame

In this game, the player must hack a com-
puter by guessing a seven-letter word used
as the secret password. The computer’s mem-
ory banks display the possible words, and the
player is given hints as to how close each guess was.
For example, if the secret password is MONITOR but
the player guessed CONTAIN, they are given the hint
that two out of seven letters were correct, because both
MONITOR and CONTAIN have the letter O and N as
their second and third letter. This game is similar to
Project 1, “Bagels,” and the hacking minigame in the
Fallout series of video games.

## Hangman And Guillotine

This classic word game has the player guess
the letters to a secret word. For each incor-
rect letter, another part of the hangman is
drawn. Try to guess the complete word before
the hangman completes. The secret words in this ver-
sion are all animals like RABBIT and PIGEON, but
you can replace these with your own set of words.

## Hex Grid

This short program produces a tessel-
lated image of a hexagonal grid, similar to
chicken wire. It shows that you don’t need a
lot of code to make something interesting. A
slightly more complicated variation of this program is
Project 65, “Shining Carpet.”
Note that this program uses raw strings, which prefix the opening
quote with a lowercase r so that the backslashes in the string aren’t inter-
preted as escape characters.

## Hourglass

This visualization program has a rough
physics engine that simulates sand falling
through the small aperture of an hourglass.
The sand piles up in the bottom half of the
hourglass; then the hourglass is turned over so the
process repeats.

## Hungry Robots

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

## J'accuse!

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
five minutes to find the criminal but will lose if you make three wrong accusa-
tions. This game is inspired by Homestar Runner’s “Where’s an Egg?” game.

## Langton's Ant

Langton’s Ant is a cellular automata simula-
tion on a two-dimensional grid, similar to
Project 13, “Conway’s Game of Life.” In the
simulation, an “ant” begins on a square that is
one of two colors. If the space is the first color, the ant
switches it to the second color, turns 90 degrees to the
right, and moves forward one space. If the space is the
second color, the ant switches it to the first color, turns
90 degrees to the left, and moves forward one space.
Despite the very simple set of rules, the simulation displays complex emer-
gent behavior. Simulations can feature multiple ants in the same space, caus-
ing interesting interactions when they cross paths with each other. Langton’s
Ant was invented by computer scientist Chris Langton in 1986. More infor-
mation about Langton’s Ant can be found at https://en.wikipedia.org/wiki/
Langton%27s_ant.

## Leetspeak

There’s no better way to demonstrate your
mad hacker skills than by replacing let-
ters in your text with numbers: m4d h4x0r
5k1llz!!! This word program automatically con-
verts plain English into leetspeak, the coolest way to
talk online. Or at least it was in 1993.
It takes a while to get used to, but with some practice, you’ll eventu-
ally be able to read leetspeak fluently. For example, 1t +@]<3s 4 w|-|1le +o
g37 |_|s3|) 70, b|_|+ y0u (an 3\/3nt|_|/-\lly r3a|) l33t$peak phl|_|3n+ly.
Leetspeak may be hard to read at first, but the program itself is simple
and good for beginners. More information about leetspeak can be found
at https://en.wikipedia.org/wiki/Leet.

## Lucky Stars

In this push-your-luck game, you roll dice
to collect stars. The more you roll, the more
stars you can get, but if you get three skulls
you lose everything! This quick multiplayer
game can support as many players as you want, mak-
ing it ideal for parties.
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

## Magic Fortune Ball

The Magic Fortune Ball can predict the
future and answer your yes/no questions
with 100 percent accuracy using the power
of Python’s random number module. This pro-
gram is similar to a Magic 8 Ball toy, except you don’t
have to shake it. It also features a function for slowly
printing text strings with spaces in between each char-
acter, giving the messages a spooky, mysterious effect.
Most of the code is dedicated to setting the eerie atmosphere. The
program itself simply selects a message to display in response to a random
number.

## Mancala

The board game Mancala is at least 2,000
years old, making it almost as old as Project
63, “Royal Game of Ur.” It is a “seed-sowing”
game in which two players select pockets of
seeds to spread across the other pockets on the board
while trying to collect as many in their store as possi-
ble. There are several variants of this game across dif-
ferent cultures. The name comes from the Arab word
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

## Maze Runner 2D

This two-dimensional maze runner shows
the player a top-down, bird’s-eye view of a
maze file you create in a text editor, such as
the IDE you use to write your .py files. Using
the WASD keys, the player can move up, left, down,
and right, respectively, to navigate the @ symbol
toward the exit marked by the X character.
To make a maze file, open a text editor and create the following pat-
tern. Don’t type the numbers along the top and left side; they are only there
for reference:
123456789
1#########
2#S# # # #
3#########
4# # # # #
5#########

## Maze Runner 3D

This three-dimensional maze runner pro-
vides the player with a first-person view
from inside a maze. Try to find your way out!
You can generate maze files by following the
instructions in Project 44, “Maze Runner 2D,” or by
downloading maze files from https://invpy.com/mazes/.

## Million Dice Roll Statistics Simulator

When you roll two six-sided dice, there’s
a 17 percent chance you’ll roll a 7. That’s
much better than the odds of rolling a 2: just
3 percent. That’s because there’s only one com-
bination of dice rolls that gives you 2 (the one that
occurs when both dice roll a 1), but many combina-
tions add up to seven: 1 and 6, 2 and 5, 3 and 4, and
so on.
But what about when you roll three dice? Or four? Or 1,000? You could
mathematically calculate the theoretical probabilities, or you can have
the computer roll a number of dice one million times to empirically fig-
ure them out. This program takes that latter approach. In this program,
you tell the computer to roll N dice one million times and remember the
results. It then displays the percentage chance of each sum.
This program does a massive amount of computation, but the computa-
tion itself isn’t hard to understand.

## Mondrian Art Generator

Piet Mondrian was a 20th-century Dutch
painter and one of the founders of neoplas-
ticism, an abstract art movement. His most
iconic paintings relied on blocks of primary
colors (blue, yellow, red), black, and white. Using a
minimalist approach, he separated these colors with
horizontal and vertical elements.
This program generates random paintings that follow Mondrian’s style.
You can find out more about Piet Mondrian at https://en.wikipedia.org/wiki/
Piet_Mondrian.

## Monty Hall Problem

The Monty Hall Problem illustrates a sur-
prising fact of probability. The problem
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
Another way to think of it is that you have 1,000 boxes and one box con-
tains a prize. You guess which box the prize is in and the host puts it in your
hands. Do you think the prize is in your box or one of the 999 other boxes?
You don’t need the host to open 998 of the 999 boxes that don’t contain a
prize; the amount of choice is the same as with the 1,000 doors. The odds
that you guessed correctly in the beginning are 1 in 1,000, while the odds
that you did not (and that the prize is in one of the other boxes) is a near cer-
tain 999 in 1,000.
More information about the Monty Hall Problem can be found at
https://en.wikipedia.org/wiki/Monty_Hall_problem.

## Multiplication Table

This program generates a multiplication
table from 0 × 0 to 12 × 12. While sim-
ple, it provides a useful demonstration of
nested loops.

## Ninety-Nine Bottles
-50

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
