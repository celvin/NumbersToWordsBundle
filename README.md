# NumbersToWordsBundle

This is one improved edition of https://github.com/massil31/NumbersToWordsBundle

Hopefully compatible with Symfony 2 and 3

Installation:

## 1 First install pear module: 

    pear install Numbers_Words

If there are some trubles about the version you can use: pear install channel://pear.php.net/Numbers_Words-0.18.1

## 2 install the bundle:
    composer require celvin/numbers-to-words-bundle

## 3 Add this to app/AppKernel.php
    new celvin\celvinNumbersToWordsBundle(),
