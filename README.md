# Unexpected String Concatenation with the + Operator in JavaScript

This repository demonstrates a common JavaScript error involving unexpected string concatenation when using the + operator.  In JavaScript, the + operator is overloaded; it performs addition for numbers and concatenation for strings.  If one operand is a string, the other operand will be implicitly converted to a string, resulting in concatenation instead of arithmetic addition. 

The `bug.js` file shows an example of this unexpected behavior. The `bugSolution.js` file offers a corrected approach using the Number() function to ensure that operands are treated as numbers.

## How to Reproduce

1. Clone this repository.
2. Navigate to the repository directory.
3. Run `node bug.js` to see the unexpected output. 
4. Run `node bugSolution.js` to see the corrected output.

## License

This project is licensed under the MIT License - see the LICENSE file for details.