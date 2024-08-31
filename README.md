# ScoreFour Game 

Welcome to **ScoreFour**, an engaging and strategic two-player game where the objective is to align four beads of the same color in a row. This project is designed with both a text-based interface and a GUI, making it versatile for various types of gameplay. Below you'll find an overview of the key components, gameplay mechanics, and instructions for running the game.

---

## 🛠️ Components of ScoreFour

### 1. **Game Board**
- **Description:** The game board is the central hub where all gameplay occurs, holding the pegs.
- **Actions:**
  - **Set Board:** Lays out the pegs in a 4x4 grid format.
  - **Clear Board:** Resets the board by clearing all beads after each game.

### 2. **Pegs**
- **Description:** The pegs are where the beads are placed. They are arranged in a 4x4 grid, with a total of 16 pegs.
- **Features:**
  - Each peg can hold up to 4 beads.
  - Beads can only be placed on a peg if there are fewer than 4 beads on it.
- **Actions:**
  - **Place Bead:** Place a bead on a specified peg using x, y coordinates.
  - **Remove Bead:** Optionally remove a bead if a player changes their mind.

### 3. **Beads**
- **Description:** Beads come in two colors, each linked to a player.
- **Features:**
  - **Color Assignment:** Randomly assigns black or white to each player.
  - **Ownership:** Beads are linked to the player who placed them.
- **Conditions for Placement:**
  - The peg has fewer than 4 beads.
  - It is the player's turn.
  - No one has won the game yet.

### 4. **Row**
- **Description:** A row is a line of four beads that can be horizontal, vertical, or diagonal.
- **Objective:** The first player to form a row of four beads of their color wins.

### 5. **Players**
- **Human Player:**
  - Interacts with the game through commands to place beads on pegs.
- **Computer Player (AI):**
  - Plays against the human player with strategic move generation.

### 6. **Score Calculation**
- **Description:** The game continuously checks for a winning row after each turn.
- **Win Condition:** A player wins by forming a straight line of four beads.
- **Draw Condition:** If the board is filled without a winning row, the game ends in a draw.

---

## 🎮 How to Play ScoreFour

### **Text-Based Interface**
1. **Start the Game:**
   - Run the `TextInterface.java` file.
   - You will be prompted to start a new game and choose between "text" or "GUI" modes.
2. **Gameplay:**
   - In "text" mode, you’ll interact with the game using commands in the console.
   - The board is displayed in ASCII, and you will be prompted to place your beads by specifying coordinates.
   - Alternate turns with the AI until a player wins, after which you can choose to restart or quit.

### **Graphical User Interface (GUI)**
1. **Launch the GUI:**
   - Enter the "GUI" command after starting the game.
   - The GUI will display a visual representation of the game board.
2. **Gameplay:**
   - Players take turns clicking on pegs to place their beads.
   - The GUI will visually update with each move, showing colored bars that represent beads.
   - Once a game is won, restart by entering the Start → “GUI” command.

*Note: The GUI is currently in development and may not fully support gameplay.*

---

## 🚀 Getting Started

To play ScoreFour, download the project files and unzip them into your preferred directory. The following Java files are included:

- **TextInterface.java**
- **Board.java**
- **BoardDisplay.java**
- **BeadColour.java**
- **Peg.java**
- **PlayerType.java**
- **AIBranch.java**
- **AIPlayer.java**

### **Running the Game**
- To start the game, compile and run `TextInterface.java`.
- Follow the prompts to choose your gameplay mode and begin playing!

---

## 🤝 Contributing

We welcome contributions to the ScoreFour project! If you have ideas for new features or improvements, please feel free to submit a pull request or open an issue on GitHub.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

---

## 👨‍💻 About the Team

Team Hoodoo Jo is dedicated to creating engaging and strategic games that challenge players' minds. ScoreFour is a testament to our commitment to providing high-quality gameplay experiences.

---

*We hope you enjoy playing ScoreFour! If you have any feedback or run into issues, don't hesitate to reach out.*
