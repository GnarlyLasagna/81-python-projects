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
replaced it. The playing cards in this program are an
example of ASCII art:

```
___ ___
|A | |10 |
| ♣ | | ♦ |
|__A| |_10|
```
