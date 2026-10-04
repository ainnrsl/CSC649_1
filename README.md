# CSC649 Setup Activity

## What the program does
This program asks the user to enter a sentence, then displays the word
count and the character count (including spaces). If the input is empty,
it shows the message "You did not enter a sentence."

## How to run
1. Open the project in PyCharm (Python 3.12, .venv).
2. Open main.py and click Run 'main'.
3. Type a sentence when prompted and press Enter.

## Test results
| Test | Input | Output |
|---|---|---|
| Normal sentence | i love phyton | Word count: 3, Character count: 13 |
| Empty input | (just press Enter) | You did not enter a sentence. |
| Extra spaces | "  hello    world  " | Word count: 2, Character count: 18 |

## Limitation
The character count includes leading, trailing and repeated spaces, so
it may not match what the user considers the "real" length of the sentence.