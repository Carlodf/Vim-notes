# Text editing language

Vim text editing language is a set of composable commands available in normal
mode. A command can be composed of three main components:

`[count (optional)] [operator] [motion | text object]`

## Operators
Most common operators

- `c`  change
- `d`  delete
- `y`  yank into register
- `~`  swap case
- `gu` make lower-case
- `gU` make upper-case
- `!`  filter through an external program
- `=`  filter through 'equalprg' or C-indenting if empty
- `gq` text formatting
- `>`  shift right
- `<`  shift left
- `zf` define a fold

Note: `g@` can be used in mappings to create custom operators. (for more info
`:help operatorfunc`)

`:help operator`
