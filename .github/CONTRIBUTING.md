# Contributing to Hangman Game

Thank you for your interest in contributing! This project was developed as a university assignment, but any improvements, bug fixes, or new ideas are more than welcome to make this classic game even more engaging.

## How to Contribute

1. **Fork** the repository.
2. Create your branch: `git checkout -b feature/new-functionality`.
3. Make your changes and commit them: `git commit -m "Add new functionality"`.
4. Push your branch: `git push origin feature/new-functionality`.
5. Open a **Pull Request**.

## Ideas for Contribution

- **New Word Categories:** Expand `resource/palabras.py` with themed categories (e.g., Programming, Countries, Animals).
- **Visual Improvements:** Add animations for the pirate/hangman, better fonts for the hidden word, or custom background themes.
- **Difficulty Settings:** Implement levels that change the number of allowed attempts or the length of the words.
- **Code Refactoring:** Refactor the current structured logic into an Object-Oriented (OOP) design or clean up the `inter_gráfica.py` for better performance.
- **Language Support:** Add the ability to switch between English and Spanish word lists.

## Development Tips

- **Resource Management:** If you add new words, make sure to keep the format in `resource/palabras.py` consistent to avoid import errors.
- **Input Logic:** Test how the game handles non-alphabetical characters or repeated guesses (the game should ideally notify the user without penalizing a life).
- **Gamelib Rendering:** Since the game relies on `gamelib`, ensure any new graphical elements don't block the main thread.

Thank you for your collaboration! 🎉
