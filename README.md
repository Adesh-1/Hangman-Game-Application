# Hangman-Game-Application

# 📌 Project: Sequential Letter Guessing Game (Hangman-Inspired)
# 📝 Description

This is a simple, terminal-based word guessing game inspired by Hangman, written in Python.
Instead of guessing any position freely, the player must reveal the word sequentially from left to right, making the game logic deterministic and beginner-friendly.

At the start:

A random 6-letter word is selected from a predefined list.

The first and last letters are revealed.

All middle letters are hidden using underscores (_).

The player has 5 attempts to correctly guess each letter in order.
Each correct guess reveals the next character in sequence, while incorrect or invalid inputs reduce the remaining attempts.

# 🎮 How the Game Works

The game randomly selects a word.

First and last letters are shown; middle letters are hidden.

The player:

Enters one alphabetic character at a time.

Must guess the next correct letter position.

Correct guess:

Reveals the next letter.

Wrong or invalid guess:

Decreases remaining tries.

The game ends when:

The word is fully revealed 🎉

OR the player runs out of tries 💀

# ✨ Features

🎯 Random word selection

🔤 Input validation (single alphabetic character only)

🔄 Sequential letter reveal logic

🛑 Graceful handling of Ctrl+C / Ctrl+D

🎨 Emoji-enhanced, user-friendly terminal output

📚 Beginner-friendly structure with comments

🧠 Learning Objectives

This project is ideal for beginners to practice:

Python loops and conditionals

String slicing and formatting

Input validation

Game logic design

Clean and readable code structure

# 🚀 How to Run
python game.py
