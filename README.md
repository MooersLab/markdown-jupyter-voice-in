![Version](https://img.shields.io/static/v1?label=markdown-jupyter-voice-in&message=0.2.1&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

# Markdown snippets for Jupyter in Voice-In Plus

This is a collection of about 90 voice snippets to support writing in markdown cells of Jupyter notebooks using the Voice In Plus plug-in for Google Chrome and Microsoft Edge web browsers.
The voice triggers and associated text replacements are stored in the left and right columns of the *markdown.csv* file.
Read this file to learn tab triggers.

## Demo video
Demo includes using built-in `Voice In` commands to delete wrong words and start new lines.

Note that the imaginary *i*'s were capitalized in the rendered equation by mistake; they are in lowercase in the LaTeX code inserted by Voice In Plus.
The equation renders correctly in [latexit](https://pierre.chachatelier.fr/latexit).
MathJaX is the source of the error.


https://github.com/MooersLab/markdown-jupyter-voice-in/assets/15176203/b43a8a17-dbfa-4998-8f26-5b8dec5a6f0e




## Installation and use

1. Load the markdown.csv file by copying its contents and pasting these into the text area opened by double-clicking on the **bulk add** button on the configuration page for your Voice In Plus account.
2. Any existing voice commands with the same voice trigger (i.e., voice command in the left column) will be overwritten.
3. Convert an empty code cell into a markdown cell by entering `m`.
4. Activate the Voice-In plugin (I use the option-L key binding on my Mac).
6. Say the voice trigger to invoke the insertion of the corresponding code fragment.
7. Deactivate the Voice-In plugin (not always essential).
8. Hit Control-Enter to execute the markdown code block when ready to render it.


## Update Table
|Version        | Changes                                                                                                                                    | Date                 |
|:-------------:|:------------------------------------------------------------------------------------------------------------------------------------------:|:--------------------:|
| Version 0.1   |  Initiated  with 90 voice snippets. Added badges and update table                                                                          | 2024 April 14        |
| Version 0.2   |  Clarified the instructions in the README.md file.                                                                                         | 2024 April 20        | 
| Version 0.2.1 | Added demo video to README.md file.                                                                                                        | 2024 Apirl 25        |
 
## Funding
- NIH R01 CA242845
- NIH R01 AI088011
- NIH P30 CA225520 (PI: R. Mannel)
- NIH P20GM103640 and P30GM145423 (PI: A. West)

