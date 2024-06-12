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

