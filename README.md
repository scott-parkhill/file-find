# File Find
File Find program for simplifying common find command searches. Made because VS Code has garbage explorer search.

## Install

Just add the directory containing the program to your path to use it.

Example: `ff` lives in `~/scripts`

Then add `PATH="$PATH:~/scripts"` in your `.bashrc` file.

Run `source .bashrc`

Use it by typing `ff`.

## Required Modifications

If you look at the part for directory exclusions, you'll see I have excluded `obj/*` when `WebModules` is in the search path somewhere. Modify this as necessary.

You'll also notice that I use the `kate` editor. Change this to your preferred text editor.

Lastly, you'll have to make sure that `code --help` returns something for you in the terminal to make sure you've properly configured vs code to work in the terminal.
