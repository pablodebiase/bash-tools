# bash-tools:

## vis

### Usage
    vis name-pattern

### Description
This script will automatically search for all files with the file name pattern (case insensitive) within the local working directory and will output a scrollable list with up and down arrow keys. With ENTER you select which one to open in vim. With triple ESC you exit.

### Installation
Place the script in a folder and add that folder to PATH env.

    mkdir $HOME/bin
    cp vis $HOME/bin
    echo 'export PATH=$PATH:$HOME/bin' >> $HOME/.bashrc

