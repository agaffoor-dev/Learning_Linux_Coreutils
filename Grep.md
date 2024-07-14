### GREP : Global Regular Expression Print

- Has the ability to search in text files
- `*` selects all the files in current working directory to search through
- `-v` selects lines that don't have the expression specified in the grep command
- `-i` allows for case insensitive searching of expressions
- `-c` counts the number of matches found
- `-r` allows for recursive searching within multiple directories
- `-n` adds line numbers in front of each context line that contains the expression
- The flags can also be combined like in `-civ`
```bash
grep -civ GNU gpl.txt
```