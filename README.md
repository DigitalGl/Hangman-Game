# Hangman Game

A classic word-guessing game built with HTML, CSS, and JavaScript. Test your vocabulary skills by guessing the hidden word letter by letter before the hangman is fully drawn! The game features a clean interface, dynamic keyboard input, and a variety of words with hints.

## Live Demo  
Check out the live version here: [Hangman Game](https://digitalgl.github.io/Hangman-Game/)

## Features
- Guess a word by selecting letters from an on-screen keyboard.
- Displays a hint for each word to aid guessing.
- Tracks incorrect guesses with a hangman illustration (up to 6 mistakes).
- Responsive design with a modal for game-over scenarios (win or lose).
- Includes a diverse list of 60+ words with hints.

## How It Works
The game randomly selects a word from a predefined list (`word-list.js`). Players guess letters using a virtual keyboard. Correct letters fill in the word, while incorrect guesses advance the hangman drawing. The game ends when the word is fully guessed (victory) or the hangman is completed (loss), showing a modal with the result.

## Project Structure
```
Hangman-Game/
├── index.html          # Main HTML file with the game structure
├── style.css           # Custom styles for layout and visuals
├── scripts/            # Folder containing JavaScript files
│   ├── script.js       # Game logic and interactivity
│   └── word-list.js    # List of words and hints
└── README.md           # Project documentation
```

*Note:* Image assets (e.g., `images/hangman-0.svg`, `victory.gif`, `lost.gif`) are referenced but not provided here. Ensure they are included in an `images/` folder for full functionality.

## How to Run Locally
1. **Clone the repository:**
   ```bash
   git clone https://github.com/username/Hangman-Game.git
   ```
   *(Replace `username` with your GitHub username once hosted.)*

2. **Navigate to the project folder:**
   ```bash
   cd Hangman-Game
   ```

3. **Ensure image assets are present:**
   Place hangman images (`hangman-0.svg` to `hangman-6.svg`) and GIFs (`victory.gif`, `lost.gif`) in an `images/` folder in the root directory.

4. **Open `index.html` in a browser:**
   - Double-click `index.html`, or
   - Use a local server (e.g., Live Server in VS Code) for optimal performance:
     ```bash
     live-server
     ```

## Deployment on GitHub Pages
To deploy on GitHub Pages:
1. Push the project to a GitHub repository.
2. Ensure all files (including the `images/` folder) are in the root of the main branch.
3. Go to **Settings > Pages** in your repository.
4. Set the source to the **main** branch.
5. Access the deployed site at: `https://username.github.io/Hangman-Game/`.

## Dependencies
- **Open Sans Font** - Loaded via Google Fonts for typography.

## Customization
- **Add Words:** Edit `word-list.js` to include new words and hints.
- **Change Images:** Replace hangman SVGs or GIFs in the `images/` folder to customize visuals.
- **Adjust Difficulty:** Modify `maxGuesses` in `script.js` (default is 6).

## Contributing
Feel free to fork this repository and submit pull requests with enhancements! Ideas for new features, better styling, or additional word lists are welcome.

## License
This project is open-source and available under the **MIT License**.
