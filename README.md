# **VMWare Workstation Kernal Update Script**

This script was designed to run on Arch linux and pulls the github files from https://github.com/mkubecek/vmware-host-modules.git and updates the installed version of VMWare Workstation to operate on a newer installed Kernel, this is a common error with the nature of the rolling release which Arch linux impliments.

I designed this script to make the process quicker, it pulls down the git repository, changes directory, runs the relevant commands using the currently installed version and removes the downloaded files once completed.

You will need to run this as root, however the script will check for this prior to running the main body of the script.

The main credit for this is to mkubecek who created the neccesary scripts to update VMWare, this just streamlines the process.

