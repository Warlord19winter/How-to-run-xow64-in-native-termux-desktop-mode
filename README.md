# How-to-run-xow64-in-native-termux-desktop-mode

ok the first thing to do is to install the required pkg you whould need

pkg install install wget -y

then you can run this command to get the files for xow64(wine)

cd $HOME && rm -rf ~/xow64 && wget https://github.com/ar37-rs/xow64-wine/raw/refs/heads/main/xow64 && chmod +x ~/xow64

next is the install command for xow64

~/xow64 install -y

and wait for xow64(wine) to install

run this command if you want to configure xow64

~/xow64 r winecfg

move your games/programs to termux in a folder

go to the folder that the .exe of you game/program is located in termux

to run programs you have to run this command

make sure to keep this symbol in the command ~/xow64 r (the_programs_name).exe
