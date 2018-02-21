# Pig-Latin
An application that counts the number of vowels in a string
## Specs
  1.  The program recognizes a single vowels:
     *Input:"o"
    *Output:1

  2.  The program recognizes a single vowel regardless of case:
    2a. Input:"O"
    2b. Output:1

  3.  The program recognizes a single vowel in a multiple-character word:
    *Input:"cat"
    *Output:1

  4. The program recognizes a single vowel in a single word:
    *Input:"cater"
    *Output:2

  5.The program recognizes a single vowel in a multiple-word sentence:
    *Input:"cats catered the event"
    *Output:7

  6.The program recognizes a single vowel in a multiple-word sentence regardless of capitalization:
    *Input:"CATS CATERED THE EVENT"
    *Output:7

  7.The program recognizes a single vowel in a multiple-word sentence regardless of inconsistent capitalization:
    *Input:"CaTS CATERed ThE EveNT"
    *Output:7  

  8.The program ignores non-alphabetical characters,since they cannot be vowels.
    *Input:4%
    *Output:0
