## Dependencies
Install with `pip install -r requirements.txt`

## Goal
The script will generate output csv file that will include furigana readings in format compatible with Anki flashcards. It will also fetch kanji meanings and vocabulary types from Jisho website.

This script goal is to make flashcard creation easier.

## Usage

#### Input file
Input file should be in **csv** format. Last two column are optional. *Vocab* and *Vocab-English* are required.

|Vocab|Vocab-English|Expression|Expression-English|
|-|-|-|-|
|運動|cwiczenia, trening|毎日運動したのに、全然痩せなかった。|Mimo że ćwiczyłem codziennie, wcale nie schudłem. |

`python main.py input_file_csv` - this should generate output file "input_file_example-output.csv"