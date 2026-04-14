# Solitaire Game (C++)

A console-based Solitaire game implemented using object-oriented programming in C++. The project simulates a standard 52-card deck, manages multiple piles, and visually renders the game using custom console graphics.

## Features

* Full 52-card deck implementation
* Card properties: rank, suit, color, face-up/down
* Multiple piles:

  * Stock
  * Waste
  * Home cells
  * Playing piles
* Random shuffling of deck
* Proper card dealing logic
* Console-based graphical display with colors
* Cascading card layout (like real Solitaire)

## Concepts Used

* Object-Oriented Programming (OOP)
* Classes & Encapsulation
* Dynamic Memory Management
* Arrays & Pointers
* Operator Overloading
* Console Graphics (custom rendering)

## Classes Overview

* **PlayingCard** → Represents a single card
* **PileofCards** → Manages stack-like card behavior
* **Deck** → Stores and manages full deck
* **Solitaire** → Controls game setup and display

## How to Run

1. Compile:

   ```bash
   g++ main.cpp -o solitaire
   ```
2. Run:

   ```bash
   ./solitaire
   ```

## Output

* Visual representation of:

  * Stock & waste piles
  * Home piles
  * Playing piles (cascading)
* Cards displayed with suit symbols and colors

---

This project focuses on implementing core Solitaire logic and visual representation using C++ and OOP principles.
