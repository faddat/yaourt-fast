# yaourt-fast
I love yaourt and without it frankly arch doesn't reach half its potential.  This repo is here to limit the painful time when you have arch, but no yaourt!  It's only a readme, that's all you need:

 * make a new user - useradd username -m
 * set the user's password - passwd username
 * pacman -Syy
 * pacman -Syu
 * pacman -S git base-devel sudo yajl
 * su username
 * git clone https://aur.archlinux.org/yaourt.git
 * git clone https://aur.archlinux.org/package-query.git
 * cd package-query
 * makepkg -si
 * cd ../yaourt
 * makepkg -si

 

There, now you can stop panicking, you have yaourt back!
