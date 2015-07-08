![ContentMine logo](https://github.com/ContentMine/assets/blob/master/png/Content_mine(small).png)

# Working in the ContentMine virtual machine

After installing the vm ([see here](installation_instructions.md)), you can start the machine from the VirtualBox interface. Choose the image called ContentMine-VM and click the "Start" button.

![Start the vm](images/starting_vm.png)

After a few seconds you land on the desktop.

## 1. Usage

Everything starts with a right click from here. If you want navigate through the folders on the machine, right-click on the desktop and select "File Manager". There is also a browser included, which can be opened with right-click and "Web Browser".
The ContentMine pipeline is controlled from the command line, which can be open with right-click and "Terminal". This opens a text-based interface, from where we can navigate folders, see into files, and interact with the ContentMine software.

![Terminal](images/terminal.png)

You can maximize it to fullscreen by double clicking on the title bar.


## 2. Basic commands

ls: **l**i**s**ts files and directories, takes the current working directory as root

cd: **c**hange **d**irectory, moves the working directory location to the target location

mv: **m**o**v**es files and directories from the first location to the second, e.g. files from a usb stick to the working directory

cp: **c**o**p**ies files from the first location to the second

rm: **r**e**m**oves the specified file. If you want to remove a directory, use rm -r but make sure you want this.
