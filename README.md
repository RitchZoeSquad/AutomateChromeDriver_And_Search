# AutomateChromeDriver_And_Search

A Selenium-based Python script for automated Google searches.

## What it does
This script automates the process of opening a Chrome browser and performing Google searches based on user input. It provides a simple command-line interface (CLI) loop that allows users to perform multiple searches sequentially without manually opening the browser.

## Stack
| Component | Detail |
|---|---|
| Language | Python |
| Key libraries | selenium |
| Port / endpoint | Google Search (https://www.google.com/search) |

## Quick Start
```bash
# Install dependencies
pip install selenium

# Run the script
python main.py
```
Note: Ensure you have Google Chrome installed and a compatible `chromedriver` available in your path or project directory.

## Environment Variables (if any)
| Variable | Default | Description |
|---|---|---|
| None | | |

## API / Usage (if applicable)
Run the script and follow the interactive prompts:
1. Enter the search string or URL when prompted.
2. The script will open Chrome, perform the search, and then close the browser.
3. Choose 'y' or 'n' to perform another search or exit.
