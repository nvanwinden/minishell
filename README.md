# minishell
**Codam [42 Network] project**: write a simple shell.

**Project requirements**
- **Show a prompt** when waiting for a new command
- **Search and launch the right executable** based on the PATH variable or by using relative or absolute path e.g `/bin/echo hello`, `ls -la`, `./minishell`.
- Implement the following built-in functions:
  - `echo` with option `-n`
  - `cd` with only a relative or absolute path
  - `pwd` without any options
  - `export` without any options
  - `unset` without any options
  - `env` without any options and any arguments
  - `exit` without any options
 - `;` should separate commands like in bash
 - `'` and `"` should work like in bash except for multiline commands
 - Redirections `<` `>` and `>>` should work like in bash except for file descriptor aggregation
 - Pipes `|` should work like in bash
 - Environment variables (`$` followed by characters) should work like in bash
 - `$?` should work like in bash
 - `ctrl-c`, `ctrl-d` and `ctrl-\` should have the same result as in bash 
