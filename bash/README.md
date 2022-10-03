# bash
Simply rename to .bashrc and drop into your home folder if using as-is. 
pinkbashrc.sh tries to automatically detect root (might not work if your distro does wierd things with root's UID) and change the color to warn you. Also attempts to detect your package manager and alias update appropriately. 
I normally keep the "-i" aliases on a separate bashrc file for root accounts, but I've not found this as annoying in Linux so I haven't bothered with my pinkbashrc yet. Could probably just move thos into the if statement if you wanted to do that, though. 