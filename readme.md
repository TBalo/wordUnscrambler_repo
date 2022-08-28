# WORD UNSCRAMBLER


## DESCRIPTION

This is a wordUnscrambler console application written with c# on the .net core framework.
It enables you confirm if a word has matches amongst a set of given words in a file.

The file contains a specified list of words. A word provided by the user is entered from the interface to confirm if the word has a match of words found in the file then the program returns the list of matched words.

## WHAT YOU WOULD LEARN

```C#
1) You would see how methods, classes are defined and instantiated.
2) How to read the contents of a file and fetch it
3) How to use foreach conditional statement, arrays etc.
```

## USAGE

You will receive a prompt stating below —
Enter scrambled word(s) manually or as a File: F-file/M - manual

From the CLI, type M or F to enter the words manually or as a File and press enter
For a manual selection, you will receive below prompt
Enter word(s) manually (separated by commas if multiple)
Enter the words 
For a sample word entered e.g more, the program would return below

MATCH FOUND FOR more: rome

MATCH FOUND FOR more: more

For a file selection, input the text file path - here its defined as wordlist.txt. It is in the bin/debug directory of the project. 
Ensure the file has the words to be compared stored in it. 
Proceed to unscramble as done manually above.


## CREDITS

Credit goes to Avetis Ghukasyan, Senior Full Stack Web Developer. His course on Udemy, an extensive hours of C# training on building applications has been helpful. Please see video link below

[UDEMY COURSE] (https://www.udemy.com/course/learn-csharp-by-building-applications/learn/lecture/)
