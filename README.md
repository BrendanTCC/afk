# afk

*an afk sign generator made in bash.*

## prerequisites:

- qrencode

- pandoc (plus plugin `context` -- i found that on ubuntu (18.04 at least) it's available as package `context`)



## instructions:

make sure prerequisites are installed, then drop the script into your PATH (i personally have it in `/bin/afk`).

From there, just run `afk` (or `./afk` if you didn't bother to throw the script into your PATH but happen to be in the same dir as it),

fill out the name, pronoun, reason, tracking link (if you made one), and phone number, then let the script do the rest.


If you gave the (NEW!) `-p` commandline option, please ensure you've added your printer as a destination so it can print.

*thanks to [James Tomasino](https://github.com/jamestomasino) for the assist on the -p option :)*
