# Quote Guessing Game

This project is a Python-based Quote Guessing Game, which was developed using Jupyter Notebook. The game scrapes quotes from the website [Quotes to Scrape](http://quotes.toscrape.com/) and allows users to guess the author of a randomly selected quote. If the user is unable to guess correctly, hints are provided to help them.

## Table of Contents

1. [Features](#features)
2. [Technologies Used](#technologies-used)
3. [Setup Instructions](#setup-instructions)
4. [How to Play](#how-to-play)
5. [Acknowledgements](#acknowledgements)

## Features

- Scrapes quotes from a public website.
- Randomly selects a quote for the user to guess the author.
- Provides up to four guesses with hints after each incorrect attempt.
- Displays the correct answer if the user fails to guess correctly within the allowed attempts.

## Technologies Used

- **Python**: Core programming language used for the game logic.
- **Jupyter Notebook**: Used for developing and running the code.
- **Libraries**:
  - `requests`: For making HTTP requests to fetch web pages.
  - `BeautifulSoup` (from `bs4`): For parsing and extracting data from HTML.
  - `time`: For pausing the execution to avoid overloading the server.
  - `random`: For selecting a random quote from the list.

## Setup Instructions

1. **Clone the Repository**: Clone this project to your local machine using:
   ```bash
   git clone https://github.com/sid1018/quote-guessing-game.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd quote-guessing-game
   ```

3. **Install Required Libraries**: Make sure you have Python installed, and then install the required libraries using:
   ```bash
   pip install -r requirements.txt
   ```
   > Note: The `requirements.txt` file should contain the necessary libraries: `requests`, `beautifulsoup4`.

4. **Run the Game**: Open the Jupyter Notebook and run the cells to start the game.

## How to Play

1. Run the Jupyter Notebook. The game will start automatically.
2. A random quote will be displayed.
3. You have four attempts to guess the author of the quote.
4. If your guess is incorrect, a hint will be provided:
   - After the first incorrect guess, you'll be given the author's birth date and place.
   - After the second incorrect guess, the first letter of the author's first name will be revealed.
   - After the third incorrect guess, the first letter of the author's last name will be revealed.
5. If all guesses are used up, the game will reveal the correct answer.

## Acknowledgements

- [Quotes to Scrape](http://quotes.toscrape.com/) for providing the quotes used in this game.
- Inspiration from online coding communities and tutorials for web scraping and game development in Python.

## License

This project is open source and available under the [MIT License](LICENSE).

