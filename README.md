# mouse-remapper
This is just a simple mouse remapper written in C++, because i wanted to use something called
X-Mouse Button Control (oficial site: https://www.xmousebuttoncontrol.com/),
but i was using linux, and X-Mouse Button Control is only for Windows,
so i wrote a mouse button remapper to use in linux.

# the dependencies
For linux, if you use a Debian-based distro,
run
$ sudo apt-get install libx11-dev libxi-dev . 
If you use Arch, or an Arch-based distro, run
$ sudo pacman -S libx11 libxtst

# absolutely extremely important note
mouse-remapper ONLY SUPPORTS 
# x11,
it doesnt support wayland due to restrictions

# how do i use the mouse remapper aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
Go to the releases tab, in the assets for the latest release, just download
the apropriate ZIP file for linux, or Windows. Extract the ZIP, and run the EXE (for windows), or the
executable file (for linux).
