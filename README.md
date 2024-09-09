# simple_shell_environment_macOS

# These are the two most common config files you'll interact with when customizing your sehll environment

## ``.profile``
- Executes only once during login in a traditional unix/linux system
- In a terminal emulator (like iTerm2) this will be executed once after the emulator is started

## ``.bashrc``
- Executes every time a new shell is created
- This is executed everytime a new tab or window is opened.

## Both of these are examples of "dotfiles" in a *nix system
- Dotfiles are any file/directory with a ``.`` as the first character in the title string
- Filenames preceded by a dot are not visible by default but can be seen by running either of the following commands in the shell
- ``ls -a``
- ``ls -al``

# Preferred terminal emulator for MacOS: iterm2
## Download the newest version at the link below and copy it into your applications folder 
- https://iterm2.com/downloads.html
## You'll also find a copy of my current iterm2 config that I use that should include my custom hotkey setup.
