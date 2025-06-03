# 🕹️ Wumpus Maze Game

A simple Python-based Wumpus game where the player navigates a grid maze to find gold while avoiding pits and the deadly Wumpus.

## 🎯 Objective

Collect the gold `G` and exit safely without falling into a pit `P` or being caught by the Wumpus `W`.

## 📂 Maze Format

The maze is loaded from a `.txt` file in the following format:

```
<rows> <columns>
A <row> <col>       # Agent start position
W <row> <col>       # Wumpus location
G <row> <col>       # Gold location
P <row> <col>       # Pit locations (can be multiple)
```

Example:
```
4 4
A 0 0
W 2 2
G 1 3
P 0 2
P 3 3
```

## 🚀 Features

- Readable maze input format
- Avoidance logic for hazards (Wumpus, pits)
- Goal-oriented movement
- Extensible architecture for future AI agent integration

## 🛠️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/wumpus-maze.git
   cd wumpus-maze
   ```

2. Open `Wumpus_Maze.ipynb` in Jupyter Notebook or VSCode.

3. Modify `Maze_1.txt` to change maze configuration.

## ✅ Future Improvements

- Implement an AI agent with logical inference (like in "Hunt the Wumpus")
- Add visual maze rendering
- Create a CLI or GUI

## 📝 License

MIT © Ceyhun Bozkurt
