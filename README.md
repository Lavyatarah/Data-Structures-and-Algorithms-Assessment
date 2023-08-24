# Data Structures and Algorithms Assessment

This repository contains Python code solutions for the Data Structures and Algorithms assessment. The assessment covers various concepts including stacks, sequences (lists/tuples), and dictionaries.

## Instructions

1. Clone this repository to your local machine or create your own repository on GitHub to host the solutions.
2. For each section, there's a corresponding Python script containing the implementation of the required functions.
3. Push your code to your GitHub repository.
4. Make sure to maintain a clear and organized folder structure.

## Stacks

###  Balanced Parentheses Checker

File: `balanced_parentheses.py`

This code implements a function `is_balanced(expression)` that determines whether a given expression containing parentheses, curly braces, and square brackets is balanced. An expression is considered balanced if each opening bracket has a corresponding closing bracket in the correct order.

Sample Usage:
```python
expression1 = "([]{})"
expression2 = "([)]"
print(is_balanced(expression1))  # Output: True
print(is_balanced(expression2))  # Output: False
Sequences (Lists/Tuples) Removing Duplicates
File: remove_duplicates.py

This code showcases a function remove_duplicates(sequence) that takes a sequence (list or tuple) and returns a new sequence with duplicates removed while maintaining the original order of elements.

Sample Usage:
 input_sequence = [2, 3, 2, 4, 5, 3, 6, 7, 5]
result = remove_duplicates(input_sequence)
print(result)  # Output: [2, 3, 4, 5, 6, 7]
Dictionaries
 Word Frequency Counter
File: word_frequency.py

This code implements a function word_frequency(sentence) that takes a sentence and returns a dictionary containing the frequency of each word in the sentence. Punctuation is ignored, and words are conssentence = "This is a test sentence. This sentence is a test."
result = word_frequency(sentence)
print(result)

