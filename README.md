# 🏴‍☠️ Hangman Game

Welcome to **Hangman**, a classic word-guessing game implemented in Python. Test your vocabulary and save the pirate by guessing the hidden word letter by letter before you run out of attempts!

# 📸 Demo
<div align="center">
    <img alt="Hangman Gameplay" src="img/hangman.jpg" width="250px">
    <img alt="Victory Screen" src="img/ganaste.jpg" width="250px">
    <img alt="Game Over Screen" src="img/perdiste.jpg" width="250px">
</div>

# 📍 Table of Contents
- [📝 Description](#-description)
  - [🧩 Key Features](#-key-features)
  - [🧱 Project Structure](#-project-structure)
  - [🛠️ Technologies](#️-technologies)
- [🚀 Getting Started](#-getting-started)
  - [📋 Prerequisites](#-prerequisites)
  - [⚙️ Installation](#️-installation)
- [💡 Usage](#-usage)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

# 📝 Description
This project focuses on **structured programming** and resource management. It implements the classic hangman mechanics where words are randomly selected from a data source, and the game state is updated dynamically based on user input.

## 🧩 Key Features
- **Dynamic Word Selection:** Words are randomly picked from a predefined list in `resource/palabras.py`.
- **Life System:** Visual representation of the hangman that updates with every incorrect guess.
- **Input Handling:** Real-time processing of keyboard inputs to reveal hidden letters.
- **Win/Loss States:** Custom screens for victory and defeat.

## 🧱 Project Structure
```text
Hangman/
├── graphics/    # UI rendering and Gamelib integration
├── img/         # Gameplay screenshots (Win/Loss/Game)
├── resource/    # Word database (palabras.py)
├── src/         # Core logic (ahoracado.py and letter handling)
├── main.py      # Entry point
└── LICENSE      # MIT License
```

## 🛠️ Technologies
* **Python 3.x**
* **Gamelib**: A lightweight thread-based rendering library for Python interfaces.

# 🚀 Getting Started
## 📋 Prerequisites
* Python 3.10 or higher installed on your system.

## ⚙️ Installation
1. Clone the repository:
   ```bash
   git clone git@github.com:SebaB29/HangmanGame.git
   cd hangman
   ```

# 💡 Usage
To start the game, simply run the main script:
```bash
python main.py
```

1. Once the game starts, a hidden word is represented by underscores.
2. Type a letter on your keyboard to make a guess.
3. If the letter is in the word, it will be revealed.
4. If not, the hangman drawing will progress.
5. Guess the whole word before the hangman is complete to win!

# 🤝 Contributing
1. Fork the project.
2. Create your Feature Branch (git checkout -b feature/AmazingFeature).
3. Commit your changes (git commit -m 'Add some AmazingFeature').
4. Push to the Branch (git push origin feature/AmazingFeature).
5. Open a Pull Request.

# 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
