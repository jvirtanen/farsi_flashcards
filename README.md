Farsi Flashcards
================

Farsi Flashcards is a Python application for generating Persian flashcards
for Helsinki Adult Education Centre.


Requirements
------------

Farsi Flashcards requires [Tika][].

On OS X, you can install Tika with [Homebrew][]:

    brew install tika

  [Tika]:     http://tika.apache.org/
  [Homebrew]: http://brew.sh/


Usage
-----

First, run Tika:

    tika --text vocabulary.docx > vocabulary.txt

Then, run Farsi Flashcards:

    bin/farsi_flashcards vocabulary.txt > vocabulary.tsv

The output is in a tabular text format that can be imported to [Anki][], for
example. There are three columns: the first contains the Persian phrase, the
second the Latin transliteration, and the third the Finnish translation.

  [Anki]: http://ankisrs.net/


License
-------

Farsi Flashcards is released under the MIT License. See `LICENSE` for details.
