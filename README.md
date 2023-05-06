# AI-Auto-Correct-Tool
Auto Correct Tool
This is an implementation of an Auto Correct Tool that suggests the most likely correct spelling for a given misspelled word based on a pre-defined dictionary.

Getting Started
Prerequisites
Python 3.x
NLTK (Natural Language Toolkit) Library
Installation
Clone the repo

  git clone https://github.com/<username>/auto-correct-tool.git
  
Install required libraries
  pip install -r requirements.txt

Usage
To use the Auto Correct Tool, simply run the auto_correct.py file and enter the misspelled word when prompted:
python auto_correct.py
Enter a misspelled word: speling
Did you mean 'spelling'?

You can also import the auto_correct function from auto_correct.py into your own Python code to use it programmatically:
	from auto_correct import auto_correct
	corrected_word = auto_correct("paris")
	print(corrected_word)  # Output: "Paris"

License
This project is licensed under the MIT License - see the LICENSE file for details.

