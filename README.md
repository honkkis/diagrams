# Overview

# Installation

```bash
npm install -g diagrams
```

# Usage

## Railroad Diagrams

  1. Run the following command from your terminal

          diagrams railroad inputTextFile example.svg

  2. If your inputTextFile's content was this:
```bash
Diagram(
  Optional('+', 'skip'),
    Choice(0,
      NonTerminal('name-start char'),
      NonTerminal('escape')),
      ZeroOrMore(
        Choice(0,
          NonTerminal('name char'),
          NonTerminal('escape'))))
```
  3. ...then your ```example.svg``` should look like this:
  ![Alt text](http://francoislaberge.com/diagrams/docs/example.svg)
  <img src="http://francoislaberge.com/diagrams/docs/example.svg">

# Tips & Tricks
## Embedding SVGs into Github Markdown