NSString-Brainfuck
==================

An NSString category that can generate and parse brainfuck code.

Usage
------------------

* Add NSString+Brainfuck.h and .m into your project.

* To parse brainfuck code, simply call `-parseBrainfuckCode`.

`[someBrainfuckCode parseBrainfuck];`

* To generate brainfuck code from an existing string, call `-brainfuckCode`.

`[@"someString" brainfuckCode]`;
