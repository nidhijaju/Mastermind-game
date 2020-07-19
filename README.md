# Mastermind Game

C++ implementation of creator and solver for Master Mind. Used Max Parts and Knuth's algorithms.

To compile, enter on command line: g++ mastermind.cpp -o mastermind

To run, enter on command line: ./mastermind

The program will first ask for length of sequence and number of possible values. Please enter two numbers respectively, e.g. 4 6.

It will then try different attempts of numbers, with length 4 for example, and determine number of black pegs and white pegs.

Note: Black pegs = correct number at correct position. White pegs = correct number at wrong position.

The aim of the program is to minimise the number of attempts needed by using the information from black/white pegs (using Max Parts and Knuth's).

It runs 50 tests and displays average time per test at the end to measure performance factors.