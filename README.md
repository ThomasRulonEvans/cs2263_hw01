# HW 01

Enter either a plain expression into the command line to be evaluated or provide a file with one expression per line to be evaluated.

## Description
Program to make evaluations of provided arguments.

## Getting Started
Run the program with no args to get to an open terminal where you can type mathematic expressions.
Type any expression without parentheses and the program will return the evaluation of the expression.

Run the program with --args="-b file" and the program will return evaluations line by line of the text document.
Run the program with --args="-h" and the program will return a context menu of other arguments you can pass.

### Dependencies

 // Apache Commons CLI
 implementation 'commons-cli:commons-cli:1.4'

## Help

-h, --help -> which prints the help/usage message (see below)
-b <file>, --batch <file> -> which processes the provided file rather than standard input
-o <file>, --output <file> -> sends the output to the provided file and standard output

## Authors

Thomas Evans
-EvanThom@isu.edu

## Version History

* 1.1.0
-Implementaion of parsing inputs given at the command line to return a mathmatic evaluation.
* 1.0.0 
-basic implementation of command line options and parsing.

## License

## Acknowledgments

Inspiration, code snippets, etc.

