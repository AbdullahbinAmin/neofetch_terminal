# Abdullah Neofetch Terminal

These commands were last tested on September 2024 on Ubuntu 22.04 LTS.

## Prerequisites

```bash
# Update your software repositories.
sudo apt-get update
sudo apt-get upgrade

# Install Git.
sudo apt-get install -y git

# Install Vim.
sudo apt-get install -y vim
```

## Installation

### Powerline

First, we will install the Powerline

```bash
./install_powerline.sh
```

### Oh My ZSH Shell

Now, we will install the he shell that I use is "ZSH", with the OhMyZSH upgrade on top of that. To install all of that stuff, you can run the helper script (and may need to restart after).

```bash
./install_terminal.sh
```

After this, the terminal should look a bit different, but we need to do the next step to have the entire theme.

### Profile (plugins, theme, font and color)

The last command is to create a terminal profile that will set the colors and also set the font to be the Powerline one we installed earlier (required for the theme to display correctly).

```bash
./install_profile.sh
```

If it looks funky after this command, then you might need to wait until the theme is updated with a Powerline font (the next step), and may need to also restart your machine.


### Install Neofetch

Now we will install the neofetch that will show you the OS Information.

```bash
sudo apt-get install neofetch
```
