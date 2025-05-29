# Better-CMD – Usage Documentation 🖥️

**Better-CMD** is an enhancement layer for the standard Microsoft Command Prompt (CMD), introducing a set of additional commands inspired by their UNIX counterparts. While these commands may share names with familiar UNIX tools, they are designed specifically for CMD and may differ slightly in behavior and implementation, optimized for the Windows environment.

## Available Commands 📋

- **`clear`** 🧹  
  Alias for `cls`. This command clears the terminal screen. Added for users familiar with UNIX-like environments.

- **`ls`** 📁  
  Displays a colorful, formatted list of directory contents. Offers a friendlier and more readable alternative to `dir`.

- **`touch <filename>`** 📄  
  Creates a new, empty file with the specified name.  
  If the file already exists, an error is raised and the operation is aborted to prevent accidental overwrites.  
  This behavior ensures safety and prevents unintentional data loss. 🔐

- **`pwd`** 📍  
  Prints the current working directory path.  
  This command serves as an alias for Windows' native `cd` command (without arguments), providing UNIX-like behavior to show the present directory.

- **`cat <file(s)>`** 📖  
  Concatenates and displays the content of one or more files to the terminal.  
  If a file does not exist or cannot be opened, a clear error message is displayed without stopping the entire operation.

- **`now`** ⏰  
  Displays the current local date and time in the format `YYYY-MM-DD HH:MM:SS`.  
  Useful for timestamping or quick time checks directly from the command line.
