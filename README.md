# Pig Latin Unit Tests

## Installation
Clone into a directory of you choice.

`git clone https://github.com/bnelo12/Pig-Latin-Unit-Tester.git`

Set the correct paths relative to the test file to your source files and to MARS.

```
export PATH_MARS=/PATH/TO/Mars.java  
export PATH_CONVERT_PIG_LATIN_C=/PATH/TO/convert_pig_latin.c  
export PATH_CONVERT_PIG_LATIN_S=/PATH/TO/convert_pig_latin.s  
```

## Use
Simply run:

`./test_convert_pig_latin`

## Tests
This will test your C code and MIPS to a series of inputs as follows:

```
check "Testing test test!" "Enter input: output: Estingtay esttay esttay!"
check "...!!!..." "Enter input: output: ...!!!..."
check ".. HELLO .. allo .. a .." "Enter input: output: .. ELLOHAY .. alloay .. aay .."
check "A..capital..Letter" "Enter input: output: AAY..apitalcay..Etterlay"
check "THESE-WORDS Have-hyphens..and..-Punctu-ation" "Enter input: output: ESE-WORDSTHAY Ave-hyphenshay..anday..-Unctu-ationpay"
check "Hello-" "Enter input: output: Ellohay-"
check "COMPOUND-WORDS" "Enter input: output: OMPOUND-WORDSCAY"
check "simple" "Enter input: output: implesay"
check "" "Enter input: output:"
check "ths hs n vwls" "Enter input: output: thsay hsay nay vwlsay"
check "A" "Enter input: output: AAY"
check "a" "Enter input: output: aay"
```

If a test fails the diff between the expected outputs and the program outputs is displayed.

Please report any errors.
