Using Slackbuilds (https://slackbuilds.org)
===========================================

Unzip the slackbuild tar file
Copy the source archive into the slackbuild directory
chmod +x .slackbuild script
run .slackbuild script
cd /tmp
installpkg .tgz file


Do the following to get FVWM theme working on slackware 15.0:
1)  Install imlib2 via slackbuild
2)  Install hsetroot via slackbuild
3)  Download FVWM theme files from github
4)  Extract them
5)  $ tar xvf myFvwm.tar.xz 
6)  $ cp /path/to/myFvwm to ~/
7)  $ mv ~myFvwm .fvwm
8)  $ ln -s .fvwm/path/to/wanted/config .fvwm2rc
9)  $ vim .fvwm2rc
10) Change the co-ords of the toolbox, clock, desktop switcher and bottom bar based on available resolution
11) Change button links to installed applications, especially make console point to xterm
12) $ startx
13) Make any further updates required
14) Enjoy 