# Connect Four Web App

## Introduction

This is a web application for playing Connect Four online. Connect Four is a two-player connection game in which the players choose a color and take turns dropping colored discs into a vertically suspended grid. The game's objective is to be the first to form a horizontal, vertical, or diagonal line of four of one's discs.

## How to Play

### Board Setup
The board consists of 6 rows and 7 columns.

### Turns
Players take alternating turns inserting a checker of their color (red or black) at the top of a column.

### Objective
The first player to connect four checkers in a row vertically, horizontally, or diagonally wins the game.

### Tie
If all spaces are filled and no player has achieved a series of four, the game ends in a tie.



## Requirements

- Ruby (2.7.3)
- Rails (>= 5.0.7)
- Sqlite3 (1.3.13)

## Getting Started

Follow these steps to set up and run the Connect Four Web App:

1. Clone the repository:

   ```bash 
   git clone [https://github.com/shoaib-sh/connect_four_app]
   cd connect_four_app
   ```

2. Install the required gems:

   ```bash
   bundle install
   ```

3. Set up the database:

   ```bash
   rails db:create
   rails db:migrate
   ```

4. Start the Rails server:

   ```bash
   rails server
   ```

5. Open your web browser and visit `http://localhost:3000` to access the Connect Four Web App.


## System Tests

Connect Four Web App comes with comprehensive system tests implemented using RSpec. These tests ensure that various user interactions work flawlessly.
