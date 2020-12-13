# Spoken-english-to-written-english-converter



A reusable library that can convert a paragraph of spoken english to written english. For example, "two dollars" should be converted to $2. Abbreviations spoken as "C M" or "Triple A" should be written as "CM" and "AAA" respectively.


# Installation:
open command prompt and:

> pip install PyAudio

> pip install SpokenToWrittenConvert


link for more info on Library deployed:

[Click here](https://pypi.org/project/SpokenToWrittenConvert/)


# Importing

```cmd
> from SpokenToWrittenConvert import conversion
```

# Usage :

## For input as `VOICE`:

>conversion.convertor()

## For input as `Typed`:

>conversion.convertor(0)

Note: Input zero into the arguments if you want to enter the spoken english model in typed form instead of the speaking.

# Reusability:


This library can be continuously matured as you discover more and more conversion rules.

- The library can be easily modified to be made better by adding more rules to the class `get_rules()` inside the conversion.py 

- Added a class `check_front_last()` inside conversion.py that can be made used make changes for improving the punctuations.

# Licencse:
Copyright 2020 MOHIT CHVK

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.