...in process

# Shell scripting style guide

Community driven style guide for shell scripting. All contributions are welcome.

## Basic

#### What Shell to use?

Use **Bash** (Bourne Again Shell) as your primary Shell. Bash default shell of most of UNIX operation systems.
Run your script with ```sh myscript.sh``` or ```bash myscript.sh``` commands. Note that when you use such syntax you don't need to put shebang ```#!/bin/bash``` in top of your script.

#### File extensions

Allways use **.sh** extension for your scripts of withour any extension.

#### Formating

Use tabs for indentation, not whitespacing.

#### Validation

Also use linting for your code, for preventing some common mistakes. **ShellCheck** is best for it.

#### Variables

Give your variables accurate names, follow this syntax ```var="value"```.
Using variables like here ```$var```.
