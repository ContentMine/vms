![ContentMine logo](https://github.com/ContentMine/assets/blob/master/png/Content_mine(small).png)

# The ContentMine virtual machine

## What is it, and why do you use it?

A virtual machine is a simulated operating system 'within' your operating system (think Inception(TM) for operating systems). In our case it is a Linux-based [Debian-distribution](https://www.debian.org/). The user interface may appear quite different on the first view, we provide information how to navigate and use it [here](using_contentmine_vm.md).

We use virtual machines (VMs) in order to carry out hands-on exercises using the ContentMine software. This allows all attendees to run the software without having to modify their own systems. The ContentMine tool chain requires external software and third party tools, the setup of which is not trivial on some operating systems and takes time and effort (e.g. node.js, the right java version, latex2html,...). We therefore offer the virtual machine as a pre-configured environment, which can be guaranteed to work. This allows to directly start with content mining.

Before the workshop, all attendees should do the following (instructions below):

1. Download and install the VirtualBox
2. Download the ContentMine virtual machine image

## 1. Getting VirtualBox

Please download the VirtualBox platform installer for your operating system from the [VirtualBox website](https://www.virtualbox.org/wiki/Downloads).

Run the installer and follow the on-screen instructions.

## 2. Getting the ContentMine VM image

Requirements:
* 64-bit architecture (unless otherwise stated)
* 3 GB RAM
* Adequate hard drive space for the VM (at least 5 GB)

Please download the `direct link` for the virtual image corresponding to the relevant workshop from the list [here](README.md). This should be a `.ova` file. Note, this is a large file ~1.2GB, please be patient while it downloads. Depending on your connection that can take between 10 and 60 minutes.

When the file has downloaded, double-clicking it should open VirtualBox and offer to import the virtual machine. Please follow the on-screen instructions to complete the import.

When this is done, you're ready to start exploring the VM!

  **Troubleshooting**  

  If you have any problems getting VirtualBox, or downloading and importing the virtual image, don't worry. We wil set aside time during workshops to make sure everyone has access to the software.  
  The most common error is an incomplete image, please check whether the download has been succesfully completed.  