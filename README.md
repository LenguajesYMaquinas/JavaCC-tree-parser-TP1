# JavaCC parser

## About this

This program is a parser for a tree structure defined with the sytax described in the [statement](/statement.pdf) file.

## Technologies

- Java
- JavaCC

## Respository files

  The important files are:

- [statement.pdf](/statement.pdf): this document describes the program syntax to review and the objective of this project.
- [Parser.jj](/Parser.jj): this is the  main file and contains the parser code.
- [input.txt](/input.txt): this file  contains a valid program and was used to check the correct functionality of the parser.

  The other files are created in the execution of the program and if the [Parser.jj](/Parser.jj) file change, the others change too.

## Context

This [document](/documentation/statement.pdf) contains the context of the problem, requirments and functionality for each file and function.

## Objectives

This project aims to apply the following functionalities:

- Develop a parser that recognizes tree descriptions binaries using JavaCC.

## How does it work?

Once you execute the application, the tokens are displayed by the console and at the end a message which says if the input program is valid.

## Execution

<ol>
<li>Opend the command prompt</li>
<li>Type: javacc Parser.jj</li>
<li>Type: javac *.java</li>
<li>Type: java Parser < input.txt</li>
</ol>
