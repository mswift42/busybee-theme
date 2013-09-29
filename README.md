busybee-theme
=============

port of vim's busybee theme.

![Screenshot](https://github.com/mswift42/busybee-theme/raw/master/Screenshot.png)

Install via Melpa Package Manager.

Installation Instructions
-------------------------

add the following lines to your init.el (only if you have not done so already):

    (setq package-archives '(("gnu" . "http://elpa.gnu.org/packages/")
                             ("marmalade" . "http://marmalade-repo.org/packages/")
                             ("melpa" . "http://melpa.milkbox.net/packages/")))

    (package-initialize)



This will add the gnu, marmalade and melpa repos to your emacs setup.

To install the theme

**M-x package-install** busybee-theme


To use the busybee theme when starting emacs, add this to your init.el:

    (load-theme 'busybee)


Credits
-------

This is a port of the [vim theme]((http://www.vim.org/scripts/script.php?script_id=2549) by Patrick Anderson.





