# Syncing pyenv, poetry, quarto and vscode

Our goal is pyenv, python, poetry, vscode and quarto working seamlessly with python virtual environments from a command line.

Getting all these tools to work together, especially on windows is challenging and time consuming.  This site
gathers all the necessary commands into one place so that one can install everything all at once.

The [web site](https://vcu-ssg.github.io/ssg-quarto-python-setup) offers instructions for window, mac and PC.

This repo contains the source for the website at: <https://vcu-ssg.github.io/ssg-quarto-python-setup>

## TLDR

If you're sure that you have all the tools installed and you just want to make it all work, see:

* [final steps](https://vcu-ssg.github.io/ssg-quarto-python-setup/finalsteps.html) to get your profiles set, and
* [vscode](https://vcu-ssg.github.io/ssg-quarto-python-setup/vscode.html) to get your settings correct.

## Folders

*.src* - contains source code for the web site.  The website is creating using quarto.

*.docs* - contains the html for the quarto generated web site.  Edit the source and *quarto render* the site.

## Notes

Installing the individual tools goes pretty easy.  However, making them work together requires attention to ensuring that:

1. ALL the instructions for each of the tools be followed.
1. poetry is installed with the official installer and NOT *pip install poetry*.  This is especially important for windows installs.
1. appropriate code is added to the $PROFILE, .bashrc or .zshrc files.
1. appropriate VSCODE extensions are installed.
1. appropriate VSCODE setting in the extensions are set.

Easy peasy if you check all the boxes.  Pain in the rear if you don't.

