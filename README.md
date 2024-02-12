# Text Analysis - Personal Project

## Goal

The goal of this project is to explore different ways to analyze text with JavaScript

## Requirements

### Vowel Numbers - count the number of vowels in an input

1. Create a list of valid vowels (a, e, i, o, u)
2. Take in input from the user
3. Count the number of vowels in the user input
4. Return the number of vowels

### Word Numbers - count the number of words in an input

1. Take in input from the user
2. Count the number of spaces in the user input as way to indicate words
3. Return the number of words (i.e. spaces)

### Character Numbers - count the number of characters in an input

1. Take in input from the user
2. Count the total number of characters in user input, including spaces and punctuation
3. Return the total number of characters

### Spell Checker - identify misspelled words in an input

## Testing

Create Unit Tests for each file

### Vowel Numbers Test Cases:

1. Input with all vowels: To ensure the program accurately counts each type of vowel.
2. Input with no vowels: To check the program correctly returns zero when there are no vowels.
3. Mixed input (vowels and consonants): To verify the program can correctly identify and count only the vowels among other characters.
4. Case sensitivity: To ensure the program counts both uppercase and lowercase vowels.
5. Empty input: To see how the program handles an empty string.

### Word Numbers Test Cases:

1. Single word input: To verify that the program returns 1 when there's only one word.
2. Multiple words input: To check the program counts words correctly in a sentence.
3. Input with multiple spaces: Since words might be separated by more than one space, it's good to test that scenario.
4. Empty input: To determine how the program handles an empty string.
5. Input with punctuation: To see if punctuation affects the word count.

### Character Numbers Test Cases:

1. Letters only input: Verify the program counts all characters accurately when just using letters
2. Input with spaces: Ensure spaces are included in character count.
3. Input with punctiation: Ensure punctuation marks are counted as characters
4. Input with special characters: Ensure special characters (e.g. @, $, #) are counted as characters
5. Numbers input: Check numbers are included in total character count.
6. Empty input: Test that program returns 0 when getting an empty string.
7. Single letter input: Check that program returns 1 when there is one single character
8. Input of just spaces: Check that program counts all spaces when just using spaces

### Spell Checker Test Cases:

1. Single correctly spelled word: Vertify "No Errors" given with one single correctly spelled word
2. Multiple correctly spelled words: Vertify "No Errors" given with multiple single correctly spelled word
3. Incorrectly spelled word: Vertify list with error given with one single incorrectly spelled word
4. Correctly and incorrectly spelled words combined: Confirm that with mixed correct and incorrect words, list of errors given
5. Words spelled correctly and incorrectly with special characters: Confirm that with mixed correct and incorrect words, list of errors given ignoring special characters
6. Empty string: Verify that "Empty String" returned when no string is passed
7. Numbers: Confirm that with mixed correct and incorrect words, list of errors given ignoring numbers

## How to Run

### To run Vowel Numbers:

### To run Word Numbers:

### To run Character Numbers:

### To run Spell Checker:

### To run all unit tests:
