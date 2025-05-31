# C-Snake-Water-Gun
A simple Snake-Water-Gun game in C where the user plays against the computer. Built using basic conditionals, random number generation, and console input/output. Perfect for beginners learning C programming and game logic!

# 🐍 Snake Water Gun Game in C

This is a fun and simple command-line game written in C, where you play the classic **Snake 🐍 – Water 💧 – Gun 🔫** game against the computer. It's similar to Rock-Paper-Scissors, with a twist!

## 🎮 How to Play

- Run the program.
- Choose one of the following options:
  - `0` for Snake
  - `1` for Water
  - `2` for Gun
- The computer randomly chooses one of the three.
- The result is displayed based on simple game rules.

## 🧠 Game Rules

- Snake drinks Water → **Snake wins**
- Water douses Gun → **Water wins**
- Gun kills Snake → **Gun wins**
- Same choice → **Draw**

## 📦 Features

- Simple input/output logic using `scanf` and `printf`.
- Random computer move using `rand()` seeded with `time(0)`.
- Fully beginner-friendly and easy to modify.

## 🔧 How to Compile & Run

### On Linux/Mac:
```bash
gcc snake_water_gun.c -o game
./game
