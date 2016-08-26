# NumbersToWordsBundle

This is one improved edition of https://github.com/massil31/NumbersToWordsBundle

Hopefully compatible with Symfony 2 and 3

Installation:

## 1 First install pear module: 

    pear install Numbers_Words

If there are some trubles about the version you can use: pear install channel://pear.php.net/Numbers_Words-0.18.1

## 2 install the bundle:
    composer require celvin/numbers-to-words-bundle
    
### 2.1 To specify the branch
    composer require celvin/numbers-to-words-bundle dev-master

## 3 Add this to app/AppKernel.php
    new celvin\celvinNumbersToWordsBundle(),

## 4 Add use to your controller:
    use celvin\NumbersToWordsBundle\celvinNumbersToWordsBundle;

## 5 Try it
    $numbers_words = new Words();
    $word = $numbers_words->toWords("12378" /**Number**/, 'es'/**locale**/);
