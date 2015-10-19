# Parallels For Mac

## Basic Config Settings

* Allocate at least 128 GB HDD.
* On my 16GB MBP I find 8GB RAM is good if using the Mac as a build server for Xamarin, otherwise 12GB is the way to go.
* Change the keyboard input to _United States (Apple) - Parallels_ to get the keyboard mapping correct (for AUS MBP).
* Turn _Smooth Scrolling_ OFF if using a _Magic Mouse_ - this results in a much better scrolling experience.
* Turn _Retina Support_ OFF if using an external monitor. Always forget this one and wonder why my swanky monitor looks so bad ...
* Disable sharing of the _Home Folders_ ... at the very least disable sharing of the following:
   * Desktop
   * Documents
   
   Prevents weird issues when creating a new VM, which picks up old configuration files, especially so for PowerShell profile.

