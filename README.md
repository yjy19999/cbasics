Worked Excercises from _The C Programming Language_, by Brian W. Kernignham and Dennis M. Ritchie
=======

This repository contains solutions to the examples presented in the classic book
[_The C Programming Language_](https://en.wikipedia.org/wiki/The_C_Programming_Language), by [Brian W. Kerningham](https://en.wikipedia.org/wiki/Brian_Kernighan) and [Dennis M. Ritchie](https://en.wikipedia.org/wiki/Dennis_Ritchie).  In many cases they
have been written to utilize [C99](https://en.wikipedia.org/wiki/C99) features. Solutions for any given chapter attempt to only use featured introduced up to that point in
the book.

Kernighan and Ritchie The C Programming Language Code Examples

### Chapter 1 - "A Tutorial Introduction"

* 1-01 - helloworld.c:         Hello World
* 1-02 - escapechars.c:        All escape characters
* 1-03 - ftoc.c:               Fahrenheit-Celsius
* 1-04 - ctof.c:               Celsius-Fahrenheit
* 1-05 - ftoc-reverse.c:       Fahrenheit-Celsius in Reverse
* 1-06 - eofvalue.c:           Determine the value of EOF returned by getchar() from stdin
* 1-07 - printeof.c:           Print the value of EOF directly
* 1-08 - countchar.c:          Count blanks, tabs, and new lines from stdin
* 1-09 - singleblank.c:        Replace one or more blanks with a single blank
* 1-10 - showhiddens.c:        Replaces tabs, backspaces, and backslashes by their escape characters
* 1-11 - countwords.c:         Counts the number of words
* 1-12 - wordperline.c:        Outputs its input one word per time
* 1-13 - wordhistohori.c:      Horizontally-oriented histogram of the number of words
*      - wordhistovert.c:      Vertically-oriented histogram of the number of words
* 1-14 - charhistohori.c:      Horizontally-oriented histogram of the number of characters
*      - charhistovert.c:      Vertically-oriented histogram of the number of characters
* 1-15 - ftoc-func.c:          Fahrenheit-Celsius Table (using a function)
* 1-16 - longestline.c:        Print arbitrarily long lines
* 1-17 - longlines.c:          Prints lines longer than 80 characters
* 1-18 - cleantrailsnblanks.c: Cleans out trailing blanks and tabs. Eliminates blank lines.
* 1-19 - reverse.c:            Reverses all input one line at a time
* 1-20 - detab.c:              Replace tabs with blank spaces
* 1-21 - entab.c:              Replaces converts spaces to tabs according to tab stops
* 1-22 - fold.c:               Folds long lines to a specified width
* 1-23 - nocomment.c:          Removes all comments from a C program
* 1-24 - minilint.c:           Performs rudementary syntax checks on a C program

### Chapter 2 - "Types, Operators, and Expressions"

* 2-01 - typelimits.c:         Prints the ranges of each of the numeric types
* 2-02 - equivloop.c:          For-loop equivalent to longestline without using logical operators
* 2-03 - htoi.c:               Implements htoi() hexadecimal to integer converter
* 2-04 - squeeze.c:            Implements squeze() which removes multiple chars from a string
* 2-05 - any.c:                Implements any() which returns the position of a search char
* 2-06 - setbits.c:            Implements setbits() which sets bits based upon a pattern
* 2-07 - invert.c:             Implements invert() which inverts the bits starting at a position
* 2-08 - rightrot.c:           Implements rightrot() which returns the value of a rotated integer
* 2-09 - fastbitcount.c:       Implements a faster bitcount() using a two's complement property
* 2-10 - lower.c:              Implements a lower() using a trinary conditional

### Chapter 3 - "Control Flow"

* 3-01 - binsearch.c:          Implements a binary search with only one test inside the main loop
* 3-02 - escape.c:             Tools to handle escape characters (bi-directionally)
* 3-03 - expand.c:             Expands regex style string ranges (e.g. 'a-z')
* 3-04 - itoa.c:               Version of itoa() that handles the largest negative integer
* 3-05 - itob.c:               Implements itob() that converst a number to a string of a particular base
* 3-06 - itoaw.c:              Implements itoaw() that cconvers number to string of a minimum width

### Chapter 4 - "Functions and Program Structure"

* 4-01 - strrindex.c:          Returns the position of the rightmost occurance of text in a string
* 4-02 - atof.c:               Implements atof() string to double converter with scientific notation support
* 4-03 - rpncalc4-03/*.c:      RPN Calculator supporting modulus and negative number support
* 4-04 - rpncalc4-04/*.c:      RPN Calculator (rpncalc2) extended to include stack inspection and manipulation
* 4-05 - rpncalc4-05/*.c:      RPN Calculator (rpncalc3) extended to support math functions
* 4-06 - rpncalc4-06/*.c:      RPN Calculator (rpncalc4) extended to support variables
* 4-07 - ungets.c:             Implements ungets() that returns a whole string to the input buffer
* 4-08 - singlegetch.c:        Implements getch() and ungetch() that support just a single char buffer
* 4-09 - ungetseof.c:          Implements getch(), ungetch(), and ungets() in a maner supporting EOF
* 4-10 - rpncalc4-10/*.c:      RPN Calculator (rpncalc5) based upon whole line handling
* 4-11 - rpncalc4-11/*.c:      RPN calculator (rpncalc6) that uses 'static' to negate needing ungetch()
* 4-12 - itoarecursive.c:      A recursive implementation of itoa()
* 4-13 - reverserecursive.c:   A recursive implementation of reverse()
* 4-14 - swapmacro.c:          A version of reverse() that uses a macro for swaping two values

### Chapter 5 - "Pointers and Arrays"

* 5-01 - getint.c:             Implements getint() that returns an integer (w/limit checks)
* 5-02 - getfloat.c:           Implements getfloat() that returns a floating point
* 5-03 - strcat.c:             Implements pointer version of strcat()
* 5-04 - strend.c:             Implements strend() that returns true if one string is at the end of another
* 5-05 - strnfunc/             Implements library versions of library functions:
  * strncpy.c:                   strncpy()
  * strncat.c:                   strncat()
  * strncmp.c:                   strncmp()
* 5-06 - pointers/             Implements a pointer version of:
  * anyp.c:					     anyp()
  * atofp.c:                     atof()
  * cleantrailsnblanksp.c:       cleantrailsnblanks()
  * escapep.c:                   escape()
  * expandp.c:                   expand()
  * htoip.c:                     htoi()
  * itoawp.c:                    itoaw()
  * itobp.c:                     itob()
  * longestlinep.c:              longestline()
  * reversep.c:                  reverse()
  * reverserecursivep.c:         reverserecursive()
  * squeezep.c:                  squeeze()
* 5-07                         Supports array of pointer exercise (plus qsort and rudimentary 'alloc()' tests
  * readline.c                   First version of readline that uses alloc() (c.f. section 5.6)
  * readline2.c                  Alternate version for exercise 5-07. Compare timings with 'readline.c'

##Extras

* makebigline.c: Outputs a 3001 character text line
* rpncalc/*.c:   Unadulterted (pre-exercise) RPN Calculator (rpncalc0)
* saveasascii.c: Strips input of everything except regular values
* size.c:        Counts the number of characters in the input
* testupcase.c:  Tests a technique to convert uppercase ASCII letters to lowercase

##Test Files

The following test data files are provided to support manually testing the exercises. Specifically, the ones that draw from standard input can be manually tested with these.

* bigline.txt       - One really big single line of text (3001 chars)
* bignegative.txt   - A big (out of range) negative integer
* comment.txt       - A C program containing test scenarios for 'nocomment.c'
* empty.txt         - One empty line (just a '\n')
* extraspecials.txt - Contains embedded backspace, tabs, and backslashes
* huckfinn.txt      - Project Gutenberg copy of Adventures of Huckleberry Finn by Mark Twain
* float.txt         - A floater
* floatexp.txt      - A float with exponent.
* integer.txt       - An integer
* largestnegint.txt - Largest negative integer (per typelimits.c)
* largestposint.txt - Largest positive integer (per typelimits.c)
* linttest.txt      - Test file for 'minilint.c'
* names.txt         - Twenty (20) random names
* negativeint.txt   - A negative integer (with some whitespace)
* notanum.txt       - Not a number
* oneline.txt       - One line of text but with no terminating newline ('\n')
* test1.txt         - Increasing number of characters per line with variations at the end
* zero.txt          - A totally empty file (no data)
* extraspecials.txt - Contains extra spaces, backslashes, tabs, and backspace characters

##Style

See *STYLE.md* for notes on overall style and approach to the code I'm presenting.

##License

These solutions are copyright under the terms of the GNU GENERAL PUBLIC LICENSE v3 (see LICENSE) with the following exceptions:

* The code used to implement the 'strlen()' function in selected exercises, including but possibly not limited to: itoa.c, itoaw.c, and itob.c are highly based upon the P.J. Plauger's wonderful work "The Standard C Library".  As such, per the terms outlined in the preface of this work (p. xii), I include the following verbiage:  "Portions of this work are derived from The Standard C Library, copyright (c) 1992 by P.J. Plauger, published by Prentice-Hall, and are used with permission."

* In addition, some of the solutions presented draw from Tondo and Gimpel's most helpful "The C Answer Book." In several cases, I worked out my own solutions then found better optimizations and cleaner ways of handling things based upon Tondo and Gimpel's work. This work is a bit dated and even in the places where their solutions were drawn from the code presented here has been updated closer to the c99 standard. In addition, many suggestions driven by the 'splint' linter have been incorporated causing further shift away from "The C Answer Book." THe Tondo and Gimple book I drew from has a copyright of 1989. I have not researched if it has been renewed or expired.

* Finally, by definition, the code presented here draws from, and directly answers the excercises presented within, Kernighan's and Ritchie's fundamental "The C Programing Language, 2nd Edition." This foundational work from 1988 (2nd edition) and 1978 (1st edition) remains to this day one of the best guides to the C language.
