# scratch-nosystemd-patch
this is a patch for scratch downloaded using pacman to make sound work on distros that dont use systemd

installation:
paste this in the terminal:
``sudo pacman -S scratch;git clone https://github.com/Rusomati/scratch-nosystemd-patch;cd scratch-nosystemd-patch;chmod 777 install.sh;sudo ./install.sh;rm -rf ../scratch-nosystemd-patch/``

if the script didnt work go to the cloned directory then write 
``cp so.vm-sound-ALSA /usr/lib/squeak/$VERSION``
to know the version press tab once or double tab and the options will be shown
i dont know how to use shell scripts thats why it may break but i dont think that this will happen
