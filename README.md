# switchSD-macOS
applescript application for fixes bit archive on SD  card for Nintendo Switch.

Info:
Mac OS users are having trouble reading an SD card on the Nintendo Switch. This is all because the archive file attribute of HOS (Nintendo Switch OS) and macOS are used for different purposes.
switchSD - applescript app that removes archive attributes for all files and folders on the Switch SD card.
It also takes into account the specificity of .nca folders and fixed them.
And lastly, it cleans up hidden unnecessary files for the Switch that macOS created when you worked with SD through the Finder.
In the new version, you can choose where you want to fix the attributes. On the entire map except the Nintendo folders on it (so as not to violate the attributes of the nca folders)
or you can fix the attributes of the Nintendo folders(if something is wrong with .nca attributes

How to use:
1. Perform all the actions you need with the files and folders on the switch SD card.

2. Select the name of the SD card from the list.

3. Select a direction to fix:
(a) Fix bit all files - will remove the archive bit for all files and folders on SD except Nintendo folders.
(b) Fix bit Nintendo folders - restore archive bit for all .nca on SD card.

4. Enter the administrator password.

5. (a) Fix bit all files - the process is pretty fast
5. (b) Fix bit Nintendo folders - This process is not fast and depends on the number of .nca on the SD card.


6. Wait for notification of the end of the processes.
Done - Insert the SD card into the Switch.

P.S.
You may need to allow applications not installed by Apple developers to be launched.
To do this, run the command in Terminal " sudo spctl --master-disable "
