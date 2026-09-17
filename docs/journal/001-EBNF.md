# 001 - Formal Grammars

Date: 2026-09-17

## Question

How can I formally define the syntax and grammars of Milner?

## Investigation

Studied how BNF can formally display syntactical grammars, and how EBNF is an improved variant that is more efficient. Studied what a terminal is compared to a non terminal, how they are represented in standard synyax, the concept of moving from the standard, the concept of the grammar itself defining precedence, examples of EBNF for preexisting languages (like HTML)

## Decisions

Milner will use EBNF to define its grammar

## Further Question

What convention of EBNF will Milner use?
Should the Parser be defined in EBNF?
How does the compiler actually read the EBNF file?
