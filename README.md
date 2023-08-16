# Persian Spell Checker

This repository contains a Persian spell checker implemented in Python using the Parsivar library. The spell checker aims to correct misspelled Persian words and improve the accuracy of text by suggesting corrections for words with possible typos.

## How to Use

Follow these steps to use the Persian spell checker:

1. **Input Your Massive Data**: Modify the `input_datas(text)` function to provide your massive input text as a string. This function transforms the input text into a dictionary format for further correction.

2. **Create the Dictionary**: The `input_datas` function automatically converts the massive input text into a dictionary based on the initial characters of words. This dictionary helps improve the efficiency of finding corrections for misspelled words.

3. **Input Your Query**: To correct a specific sentence, call the `spell_checker(text)` function and provide the sentence as input. The function uses the created dictionary to suggest corrections for misspelled words and returns the corrected version of the sentence.

4. **View Corrections**: The corrected sentence will be displayed as output, showing the suggested corrections for misspelled words.

```python
# Example Usage

massive_input_text = "Your massive input text goes here."
dictionary = input_datas(massive_input_text)

query = "این یک تست است که اشتباه‌های املایی را تصحیح می‌کند."
corrected_query = spell_checker(query, dictionary)
print(corrected_query)
