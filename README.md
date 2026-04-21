# Ubuntu Match Puzzle Game

This project is designed to create a Match puzzle game suitable for Ubuntu.

## Project Structure

```
ubuntu-match-puzzle/
├── src/                    # Source code files
│   ├── main.py            # Entry point of the game
│   ├── game.py            # Game logic
│   └── utils.py           # Utility functions
├── assets/                 # Game assets
│   ├── images/            # Game images
│   ├── sounds/            # Game sound effects
│   └── fonts/             # Game fonts
├── config/                # Configuration files
│   ├── config.json        # Game configuration settings
│   └── levels.json        # Game levels configuration
├── tests/                 # Unit tests
│   ├── test_game.py       # Tests for game logic
│   └── test_utils.py      # Tests for utility functions
├── .gitignore             # Git ignore file
├── README.md              # Project overview
└── requirements.txt       # Python dependencies
```

## Requirements
- Python 3.8+
- Pygame

## Installation
1. Clone the repository.
2. Navigate into the project folder.
3. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

## Usage
Run the game by executing:
```bash
python src/main.py
```

## License
This project is licensed under the MIT License.