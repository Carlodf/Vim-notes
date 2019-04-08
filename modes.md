# Modes

- **Normal mode** *This is the main mode for text editing. The editor starts in
normal mode (unless 'insertmode' option is set).* `Esc`

- **Visual mode** *Movements are used to define text selection area.* `v`, `V`

- **Insert mode** *Typed text is inserted into the buffer.*
    - `i` Insert to the left of the cursor.
    - `I` Insert to the beginning of the line.
    - `a` Insert to the right of the cursor.
    - `A` Insert to the end of the line.
    - `o` Insert to the line below.
    - `O` Insert to the line above.

- **Command mode** *Use to issue Vim commands.*
    - `:` Followed by a command.
    - `/` Followed by a search pattern, searches forward.
    - `?` Followed by a search pattern, searches backward.

`:help vim-modes`
