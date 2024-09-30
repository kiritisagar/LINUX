

In shell scripting, there are several types of scripts

# command to check shell:
echo $0
echo -p $$
echo $SHELL

# what is shell scripting?
 A shell script is just a text file with a series of commands
 Shell scripts are mostly used in Unix-based systems like Linux and macOS

normally shell script have .sh is the extension


# steps to write and run a shell script:

# step1: Open a Text Editor
   - Use any text editor like `nano`, `vim`, or `gedit` to create a script file.
   - extension should be .sh

   vi myscript.sh

# step 2: Write the Script
   - Start with the **shebang** (`#!`) to specify the shell (usually Bash).
   - The first line specifies the interpreter to use, like Bash.
   - Add your commands below it.

   #!/bin/bash
   echo "Hello, World!"

# step3: Save the File
   - Save the file with a `.sh` extension, like `myscript.sh`.

# step4: Make the Script Executable
   - Before running, give the script permission to be executed.

   chmod 777 myscript.sh
   

# step5: Run the Script
   - Run the script by typing `./` followed by the script name.

   ./myscript.sh


# Single-Line Comment
For single-line comments, start the line with #.

# Multi-Line Comment (Workaround)
: '
multi-line comments in shell scripts. &does nothing.
'

or

<<this
this
