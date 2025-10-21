# Compiler Lab Programs

Compiler Lab inte Kurchu Programs 😃
 

## Project Structure

```
.
├── calculator/
│   ├── calc.l          # Lex file for calculator lexer
│   └── calc.y          # Yacc file for calculator parser
├── lexicalAnalyzer/
│   ├── lexicalAnalyzerC/
│   │   ├── Analyzer.c  # Manual lexical analyzer in C
│   │   └── input.txt   # Sample input for lexical analyzer
│   └── lexicalAnalyzerLex/
│       ├── Analyzer.l  # Lexical analyzer using Flex
│       └── input.txt   # Sample input for lexical analyzer
├── RecursiveDecentParser/
│   └── parser.c        # Recursive descent parser implementation
├── ShiftReduceParser/
│   └── parser.c        # Shift-reduce parser implementation
└── SampleLexPrograms/
    ├── evenOrOdd/
    │   └── evenOrOdd.l # Lex program to check even/odd numbers
    ├── FlamesGame/
    │   └── FlamesGame.l # Lex program for FLAMES game
    ├── InGeneral/
    │   └── InGeneral.l # Template Lex program for custom functions
    ├── Palindrome/
    │   └── palindrome.l # Lex program to check palindromes
    └── PrimeNumber/
        └── prime.l     # Lex program to check prime numbers
```

## Notes

- Oru karyam ondu maximum ee programs run cheythu nokkane Errors okke eppozha vandiyum vilichu varunnathu ennu parayan pattathilla
- Ee programs run cheyyumbol enthenkilum Sambhavichal athinte utharavathi ithu cheytha njan alla ennu ariyichu kollunnu😁

## How to run
### Program having both LEX and YACC programs
```
bison -d fileName.y  ## or yacc -d fileName.y
flex fileName.l        
gcc lex.yy.c y.tab.c -o calcn ## YACC inte program run cheyyumbol y.tab.c generate aakunundengil ee command use cheyyaam allengil (fileName.tab.c) ennu use cheyyane
./calc
```

### Program with only LEX file
```
lex fileName.l
gcc lex.yy.c
./a.out
```
### Program with only C Code
Prathyekichu parayandallo 😎
Engaanum Maranittundengil ithaane
```
gcc fileName.c
./a.out
```
## Contributing

Feel free to add more examples or improve existing implementations.
