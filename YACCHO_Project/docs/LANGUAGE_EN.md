# YACCHO English Syntax Specification

## Policy

YACCHO aims to support English syntax as a first-class language option.

## Planned Requirements

- English keywords
- English identifiers
- English error messages
- English comments
- Unicode support
- Mixed Japanese and English source files

## Shared Internal Representation

Japanese and English syntax should be translated into the same AST and IR.
The language should not have separate runtime behavior based on syntax language.

## Implementation Status

English syntax support has not yet been verified.
Do not treat planned syntax as implemented.

## Future Work

- Define English keyword mappings.
- Define grammar and operator precedence.
- Add lexer and parser tests.
- Add mixed-language tests.
- Document compatibility rules.
