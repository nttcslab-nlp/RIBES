# RIBES: Rank-based Intuitive Bilingual Evaluation Score

## What's RIBES?

RIBES is an automatic evaluation metric for machine translation, developed in NTT Communication Science Labs.
This website distributes its implementation in Python.  
The program is distributed based on GNU General Public License (ver.2)．
You have to confirm the agreement with the license terms before download.


## How to Use

```bash
$ python RIBES.py -r REFERENCE_TRANSLATION EVALUATING_TRANSLATION
```
Also you can see other options by the following:
```
$ python RIBES.py -h
```

## File Format

* Reference and evaluating files are plain text files, not SGML or XML.
* Reference and evaluating files must have the same number of lines.
* Each line must be tokenized including punctuations (The program does not change tokenization).


## References

* PDF http://www.aclweb.org/anthology/D/D10/D10-1092.pdf
* bib http://www.aclweb.org/anthology/D/D10/D10-1092.bib

    Hideki Isozaki, Tsutomu Hirao, Kevin Duh, Katsuhito Sudoh, Hajime Tsukada  
    Automatic Evaluation of Translation Quality for Distant Language Pairs  
    Conference on Empirical Methods on Natural Language Processing (EMNLP), Oct. 2010.  


## Versions

* Latest version 1.03.1 (2014/9/8) -- fixed a compatibility problem of Python 2's split / introduced a new option -z/--emptryref to allow blank lines in references  
* Version 1.03 (2014/8/13) -- supports Python 2.6 or later / only supports utf-8 / fixed the multibyte white space issue (Thanks to Graham Neubig)   
* Version 1.02.4 (2013/12/18) -- fixed a problem in word alignment  
* Version 1.02.3 (2012/2/23)  
* Version 1.01 (2011/8/10)  

Requires Python 2.6 or later (Python 3.0 is not supported. RIBES-1.02.4 or earlier only works with Python 3.1 or later)  

## Original download website

* http://www.kecl.ntt.co.jp/icl/lirg/ribes/index.html

## Contact

(the name of our evaluation measure, lowercased)@lab.ntt.co.jp
