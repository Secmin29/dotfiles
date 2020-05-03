# Dotfiles

A collection of my dotfiles, and more will be added in time.

## Installing

My dotfiles are managed using [chezmoi](https://github.com/twpayne/chezmoi), rather than GNU Stow or another method. To get started with them, install Chezmoi through your distrobution's repositories, or via Github.

Once installed, run the command `chezmoi init https://github.com/Secmin29/dotfiles.git`, and chezmoi will clone the repository into it's managed directory. Run `chezmoi apply` to apply the new dotfiles.