# Speller
A Spell checker using C.

<h1>How it works:</h1>

It takes a file with text (say an essay or a pragraph) as its input. It produces the misspelled words and well as the number of misspelled words as output.

<h1>Efficiency:</h1>
Many of you might be thinking that those many iterations can slow down the program. Actually, we can get the efficiency to constant time, using the magical concept of hash tables. Everytime a dictionary file is loaded, we can make a special hash for each word (basically an array indice). Each array will have corresponding linked lists. As we're separating the words into different 'buckets', the number of iterations becomes considerably less. If we take an average, we can get the efficiency of the program as:

<h3>Θ(1)</h3>
    ( OR )
Theta(1)

<h1>Usage:</h1>
Some test files have already been given and all test cases have been passed.
All of these files have been give.

The large dictionary contains upto 144,000 words.

<code>./speller texts/lalaland.txt</code> <br>
<code>./speller dictionaries/large text</code><br>
<code>./speller dictionaries/small text</code><br>

<B>Expected output:</B><br><br>
 MISSPELLED WORDS
  
[...]<br>
AHHHHHHHHHHHHHHHHHHHHHHHHHHHT<br>
[...]<br>
Shangri<br>
[...]<br>
fianc<br>
[...]<br>
Sebastian's<br>
[...]<br>

WORDS MISSPELLED: <number> <br>
WORDS IN DICTIONARY: <number> <br>
WORDS IN TEXT: <number><br>
TIME IN load: <number><br>
TIME IN check: <number> <br>
TIME IN size: <number><br>
TIME IN unload: <number><br>
TIME IN TOTAL: <number><br>

<br><br>
This was a part of the cs50 computer science course.

Made with &hearts; by Chetan Kar.
