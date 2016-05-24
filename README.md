#cbh

This program is a simple cliboard-handler.
Depanding on what is in your clipboard (`xclip -o`), it prompts you with a menu
of specific actions.

# How to install :

put `cbh` into your `$PATH`
put `cbh.rc` in `~/.config/`

# How to use :
* Read add your settings to `cbh.rc`
* Assign a binding to `$YOUR_TERM_EMULATOR -e "/path/to/cbh"`
* Select some text with your mouse
* Press the binding

The following input: `8.8.8.8` should open a menu with 2 available options:
* ping4
* nmap4
