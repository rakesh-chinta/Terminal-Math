# mdlt - Metadelta CLI
**A command-line utility for quick math.**  
### What is it?
Mdlt is a lightweight command line tool that lets you perform arithmetic and symbolic math operations right from the terminal.

### Why this?
Well, nobody wants to boot Python, import SymPy, and type extraneous commands just to find a derivative. And, finding a decent website for math is quite a pain. *Mdlt just makes it too easy to do math!*

### How do I get started?
To install mdlt, simply run:
```
npm i -g mdlt
```
 Now you can begin implementing Metadelta's powerful functionality right from the terminal!

### Okay and how do I use it?
Commands are formatted as such:
```
mdlt [operation] [expression]
```
Which means that you'd like metadelta to perform the given operation on the following expression.  
An example of this is:
```
mdlt derive x^2
```
which returns: `2 x`.
*Note:* for more reliable processing, wrap the expression in double quotes.  
For more commands, Mdlt's documentation can be found [here](https://github.com/aunyks/mdlt/blob/master/DOCS.md).
