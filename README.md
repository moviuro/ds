# ds

This program does something.

Actually, it uses its argument as input text. A good idea is to use the contents
of your clipboard (`xclip -o`).
`ds(1)` prompts you with a menu of specific actions, depending on that argument.

# How to install :

put `ds` into your `$PATH`
put `ds.rc` in `~/.config/`

# How to use :
* Read and add your settings to `ds.rc`
* Assign a binding to `$YOUR_TERM_EMULATOR -e /path/to/ds "$(xclip -o)"`
* Select some text with your mouse
* Press the binding

The following input: `8.8.8.8` should open a menu with 2 available options:
* ping4
* nmap4
