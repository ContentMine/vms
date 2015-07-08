![ContentMine logo](https://github.com/ContentMine/assets/blob/master/png/Content_mine(small).png)


# Working in the ContentMine virtual machine

[1. Starting](# 1. Starting)

[1. Usage](# 2. Usage)

[2. Basic Commands](# 3. Basic Commands)

## 1. Starting

After installing the vm ([see here](installation_instructions.md)), you can start the machine from the VirtualBox interface. Choose the image called ContentMine-VM and click the "Start" button.

![Start the vm](images/starting_vm.png)

After a few seconds you land on the desktop.

![CM vm desktop](images/desktop.png)

You can shut down the vm by right click and then "Exit", and "Power off".

## 2. Usage

Everything starts with a right click from here. If you want to visually navigate through the folders on the machine, right-click on the desktop and select "File Manager". There is also a browser included, which can be opened with right-click and "Web Browser".
The ContentMine pipeline is controlled from the **command line interface**, which can be opened with right-click and "Terminal". This opens a text-based interface, from where we can navigate folders, look into files, and interact with the ContentMine software.

![Terminal](images/terminal.png)

You can maximize it to fullscreen by double clicking on the title bar.

### Copy & Paste

The settings of the vm allows to share the clipboard with the host machine. That means you can copy a url from the host machine's browser and paste it into the vm's browser, and vice versa. That works also with e.g. longer text and between text editors.

If you want to paste something into the command line, this is possible with right-click+"Paste", or ```Ctrl+Shift+V```. If you want to copy something out of the command line, e.g. an error message, highlight the message with the cursor, and then either right-click+"Copy" or use ```Ctrl+Shift+C```.

### File import/export between the host system and the vm

If you want to transfer files between the host system and the vm, you have to set up a shared folder. This has to be done in the VirtualBox before starting the vm. Go to "Settings-Shared Folders"


### Troubleshooting

If you run into issues with your keyboard layout, open a terminal window and set the layout to your locale, e.g. uk/us/de
```
setxkmap us
```


## 3. Basic commands

In general: autocompletion with 'tab' may save you a lot of typing.

**ls**: **l**i**s**ts files and directories, takes the current working directory as root. You can also look into the content of nested directories by simply extending the path ```ls dir/nested_dir/nested_dir2```.

![ls](images/ls.png)

**cd**: **c**hange **d**irectory, moves the working directory location to the target location. You can move laterally between folders on the same level with ```cd ../new_location```. You can also move up in the directory hierarchy with ```cd ..```. If you want to navigate to an absolute path, you have to start with a slash "/", ```cd /home/workshop/workshop/absolute_path```.

![cd](images/cd.png)

**mkdir**: **m**a**k**e **dir**ectory: creates a new directory

![mkdir](images/mkdir.png)

**mv**: **m**o**v**es files and directories from the first location to the second. You can move them further down into already existing directories, but also up with ```mv dir ../higher_dir```, and into the current directory with ```mv lower_dir ./new_lower_dir```.

mv is also used to rename files or folders, e.g. ```mv old_filename.txt new_filename.txt```.

![mv](images/mv.png)

**cp**: **c**o**p**ies files from the first location to the second. If you want to copy a folder, you have to use ```cp -r source_dir target_dir``` where ```-r``` stands for recursive.

![cp](images/cp.png)

**rm**: **r**e**m**oves the specified file. If you want to remove a directory, use ```rm -r dir``` but make sure you want this.

![rm](images/rm.png)