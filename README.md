# minishell :shell:
**Codam [42 Network] group project**: the objective of this project is to **recode your own shell** using **Bash** as a reference.

__Project requirements__

The following features should work like in Bash:
- **Show a prompt** when waiting for a new command
- **Search and launch the right executable** based on the PATH variable or by using a relative or absolute path e.g `/bin/echo hello`, `ls -la`, `./minishell`.
- **built-in functions**:
  - `echo` with option `-n`
  - `cd` with only a relative or absolute path
  - `pwd` without any options
  - `export` without any options
  - `unset` without any options
  - `env` without any options and any arguments
  - `exit` without any options
 - `;` should **separate commands**
 - `'` and `"` should work like in bash except for multiline commands
 - **Redirections** `<` `>` and `>>`, except for file descriptor aggregation
 - **Pipes** `|`
 - **Environment variables** (`$` followed by characters)
 - `$?`, to find the return value of the last executed command
 - `ctrl-c`, `ctrl-d` and `ctrl-\` signal handling

__Skills__

- Imperative programming
- Unix
- Rigor

__Credits__

This project is a collaborative effort with [Swaan Miller](https://github.com/subsp4ce).

__Subject__

[Read the full subject]()

## Instructions :clipboard:

### Clone repo

`git clone https://github.com/nvanwinden/minishell.git`

### Make

Run `make` in the project's root folder to create the `minishell` executable.

### Run

`./minishell`

## In action :surfing_man:

<img width="872" alt="minishell-screenshot" src="https://user-images.githubusercontent.com/58479085/205021340-8e49892c-32cc-4c50-a8bd-a54c8f800fcc.png">
