# Spoken English To Written English Converter



A reusable library that can convert a paragraph of spoken english to written english. For example, "two dollars" can be converted to $2. Abbreviations spoken as "C M" or "Triple A" can be written as "CM" and "AAA" respectively.


# Installation Procedure:
open command prompt then enter the following commands:

> pip install PyAudio

> pip install SpokenToWrittenConvert


link for more info on Library deployed:

[Click here](https://pypi.org/project/SpokenToWrittenConvert/)


# Importing the Library onto Python:
Open Python and then import the library using the following commands: 
```python
>>> from SpokenToWrittenConvert import conversion
```

# Usage :

## For input as `VOICE` :
```python
>>> conversion.convertor()
```
## For input as `TYPED` :
```python
>>> conversion.convertor(0)
```
Note: Input zero into the arguments if you want to enter the spoken english model in typed form instead of the speaking.


# Requirements of helpful Libraries:
ipython>=6

nbformat>=4

nbconvert>=5

requests>=2

SpeechRecognition>=3

# Output:
For Input as `Typed`:
```python
>>> from SpokenToWrittenConvert import conversion
>>> conversion.convertor(0)
[Enter The Spoken English]:triple a two dollars C M hello world

[OUT]:The input Spoken English Paragraph:

 " triple a two dollars C M hello world"

Converted Written English Paragraph:

 " aaa $2 CM hello world"
```
For input as `Voice`:
```python
>>> from SpokenToWrittenConvert import conversion
>>> conversion.convertor()
[Speak Anything]:
[You Said]: triple a

[OUT]:The input Spoken English Paragraph:

 " triple a"

Converted Written English Paragraph:

 " aaa"
```

# Reusability:

This library can be continuously matured as you discover more and more conversion rules.

- The library can be easily modified to be made better by adding more rules to the class `get_rules()` inside the conversion.py 

- Also added class named `check_front_last()` inside conversion.py that can be used to make changes for improving the punctuations.

# Finetuning for increasing the reliabilty of library:
- Auto Correction of sentences.
- All the proper nouns which are famous with their Abbreviations
- Changing the number spelled as words into digits.
- Expansion of conversion to all the currencies across the globe.


Many more rules can be added by following the steps that are mentioned under reusability header to mature code to be functional with a greater reliability.

# Licencse:
Copyright 2020 MOHIT CHVK

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.