# rclonemount
Mounts selected drives from your rclone config.

The script reads the names of remotes listed in rclone.conf.
It then outputs the list of unmounted remotes in a multiple selection list. User selects the remotes to mount and hits "Mount".
If all remotes are already mounted, a dialog box says so.

Unmounting should be done from OS.

Download the script and run chmod -x for it
This script has been tested on a Mac.
Testing on linux/ script for linux will follow shortly.

Tip: to make things cleaner, on a Mac, you can create an app in Automator and choose "run shell script" option. Then drag and drop this script into the automator app. This won't produce terminal window and will look much cleaner.
