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


