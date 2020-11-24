# afk

*an afk sign generator made in bash.*

## prerequisites:

- qrencode

- pandoc (plus plugin `wkhtmltopdf` -- i found that on ubuntu (18.04 at least) it's available as package `wkhtmltopdf`)



## instructions:

make sure prerequisites are installed, then drop the script into your PATH (i personally have it in `/bin/afk`).

`make install` to install; `make yeet` to, uhhh, uninstall.

if you're too damn lazy to just use your package manager to install the deps, and you happen to be on Ubuntu (or debian? can't confirm), just run the setup script.

fill out the name, pronoun, reason, return time, tracking link (if you made one), and phone number, then let the script do the rest.


If you gave the (NEW!) `-p` commandline option, please ensure you've added your printer as a destination so it can print.

*thanks to [James Tomasino](https://github.com/jamestomasino) for the assist on the -p option :)*
