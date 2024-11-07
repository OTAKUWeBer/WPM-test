# WPM-test

A simple speed typing test implemented in Python using the `curses` library. This application measures words per minute (WPM) as users type out randomly selected phrases. It's an interactive way to improve typing speed and accuracy!

## Features

- **WPM Calculation**: Displays real-time WPM updates as you type.
- **Error Highlighting**: Highlights mistakes in red for better feedback.
- **Random Text Loading**: Loads a random phrase from `words.txt` to keep each test unique.

## Requirements

To run this application, make sure you have the following requirements installed:

```plaintext
curses
```

The `curses` library is built into Python for Unix-based systems (Linux and macOS). For Windows, you can install `windows-curses` to enable `curses` functionality.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/OTAKUWeBer/WPM-test.git
   cd WPM-test
   ```

2. Install any dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the main file `wpm.py` to start the typing test.

   ```bash
   python wpm.py
   ```

2. Follow the on-screen instructions to begin the test and type the displayed text as quickly and accurately as possible.

3. Press `Esc` at any time to exit the test.

## File Structure

- **wpm.py**: Main file containing the logic for the WPM test.
- **words.txt**: List of phrases used in the test, providing random content for each run.