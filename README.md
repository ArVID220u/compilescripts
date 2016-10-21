# compilescripts

A collection of scripts simple compilation, in various languages. Calling one of the scripts will compile the specified file, in the script's language.

A list of all the scripts, and thus all the supported languages, can be found in the `docs.md` file. All scripts are located in the `bin` folder.

## Setup

To be able to use the commands everywhere, we need to symlink them into the `/usr/local/bin` folder. Either symlink them file by file, or use this command to link them all at once:

    ln -s ~/path/to/compilescripts/bin/* /usr/local/bin

Whenever new languages are added, run the above command again, to make their scripts universally available. There is no need in calling it, though, upon an edit in an existing file (thanks to symlinks).

## Usage

The commands can be used anywhere by referencing them by their names (after setup). In other words, use `cpl` or `txpl` just as you would use `ls` or `cd`.

Detailed documentation for all commands and their respective options, can be found in the `docs.md` file. However, there is a general structure:

    langpl file

## Contributions

Contributions, either in the form of extended templates, or in the form of new scripts for other languages, are highly apppreciated. The preferred method for contributions is pull requests.
