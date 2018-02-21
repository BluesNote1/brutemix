# brutemix

Reads all words from file (seperated by new lines) \
and generates mixed 2-words/3-words dictionary.

## Instructions
USAGE:

  Reads all words from file (seperated by new lines)
  and generates all possible 2-words/3-word combinations to stdout

SYNTAX:

  brutemix [-2 | -3] wordsfile.txt

## Example

File with dog, cat, horse words and -2 option invoked will generate:

dogdog\
dogcat\
doghorse\
catdog\
catcat\
cathorse\
horsedog\
horsecat\
horsehorse
