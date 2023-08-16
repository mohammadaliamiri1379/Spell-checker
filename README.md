# Persian Spell Checker

This repository contains a Persian spell checker implemented in Python using the Parsivar library. The spell checker aims to correct misspelled Persian words and improve the accuracy of text by suggesting corrections for words with possible typos.

## How to Use

Follow these steps to use the Persian spell checker:

1. **Input Your Text**: Modify the `input_datas(text)` function to provide your input text as a string. This function will organize the text into a dictionary format for further correction.

2. **Create the Dictionary**: The code automatically converts the input text into a dictionary based on the initial characters of words. This dictionary helps improve the efficiency of finding corrections for misspelled words.

3. **Run the Spell Checker**: Use the `spell_checker(text)` function to perform spell checking on the input text. The function uses the created dictionary to suggest corrections for misspelled words and returns the corrected version of the text.

4. **View Corrections**: The corrected text will be displayed as output, showing the suggested corrections for misspelled words.

```python
# Example Usage

input_text = "این یک تست است که اشتباه‌های املایی را تصحیح می‌کند."
corrected_text = spell_checker(input_text)
print(corrected_text)
