# HW 01

Enter either a plain expression into the command line to be evaluated or provide a file with one expression per line to be evaluated.

## Description
Program to make evaluations of provided arguments.

## Getting Started
Type any expression without perentheis and the program will return the evaluation of the expression.

Pass the program a file using --args="-b file" and the program will return evaluations line by line of the text document.

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
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [dbader](https://github.com/dbader/readme-template)
* [zenorocha](https://gist.github.com/zenorocha/4526327)
* [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)
