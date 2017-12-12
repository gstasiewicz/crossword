# crossword

An interactive d3-based crossword puzzle.

crossword.html creates a fully interactive square crossword puzzle from a csv file.

demo - https://gstasiewicz.github.io/crossword/crossword.html

Functionality includes text input, navigation with arrow keys, tab and shift-tab, and delete/backspace

CSV file should be formatted as follows:
  - first line: "dir,key,clue"
  - subsequent lines indicate one of three things:
    1) a clue where the dir is either "across" or "down, the key is the clue number, and the clue is the text of the clue including html tags
    2) "size,,[puzzle width]"
    3) "letters,,[a string of characters where spaces are the black squares]"
