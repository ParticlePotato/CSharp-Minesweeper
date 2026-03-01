# CSharp-Minesweeper

Custom Windows Forms Minesweeper game built with C# in JetBrains Rider.

## 🎮 Features

- 3 Difficulty levels:
  - 9x9 (10 mines)
  - 16x16 (40 mines)
  - 16x30 (99 mines)
- Left click to reveal
- Right click to place flag
- Auto reveal empty cells (flood fill logic)
- Win detection system
- Color legend for numbers

## 🕹 Controls

- **Left Click** – Reveal cell
- **Right Click** – Place/Remove flag
- **Arrow Up / Down** – Change difficulty
- **Space** – Restart game

## 🧠 How It Works

- Mines are placed randomly.
- Each cell stores:
  - Mine status
  - Adjacent mine count
  - Revealed state
- If a cell with 0 adjacent mines is opened, surrounding cells are automatically revealed.

## 🛠 Technologies Used

- C#
- Windows Forms
- .NET
---
