# clone-command
Clone command using the DD function within a terminal window

This simple program allows a user to create a bit for bit copy of any storage volume onto another drive.  Current use case for myself is for creating duplicate USBs
which have a bitlocker encryption on them. 

As of 19/07/22 the user has to input the device name (as sdf / sdb etc) they wish to copy to and from. I want to simplifiy this for the end user to some how list and number all disks with useful information for a non-tech user to understand what drive is what. The user should then be able to decide that they want to copy from disk 2 to disk 3 by inputting the number only.

Long term goals:

I would like this to be able to create a hash of all the files and folders within the given directory and automatically save this where the user wants. I have experimented with this and managed to get hashes to save, but it only provided one hash of the whole drive instead of the user inputted location (a folder inside of the 
drive that is being targetted).

Ability for this to run on a bootable USB stick to complete a DD image of the desired drive. Could be either a live desktop environement or boot into a terminal.
Could copy to the same drive which the bootable environment is on, or another externally connected USB or SSD.
