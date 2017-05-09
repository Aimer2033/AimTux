# AimTux
Cheat For CS:GO on Linux
# Instruction

# Load the dependencies you need to compile:

# Ubuntu-Based / Debian:
sudo apt-get install cmake g++ gdb git libsdl2-dev zlib1g-dev 

# Arch:
sudo pacman -S base-devel cmake gdb git sdl2 

# Fedora:
sudo dnf install cmake gcc-c++ gdb git libstdc++-static mesa-libGL-devel SDL2-devel zlib-devel 


# Gentoo:
sudo emerge cmake dev-vcs/git gdb libsdl2 mesa 

# Arch Linux (Manjaro, Antegros):
After downloading AimTux using the command below and navigating to the folder with it: 
cd pkg 
makepkg -si 
cd .. 



# Download AimTux:
git clone --recursive https://github.com/AimTuxOfficial/AimTux  
cd AimTux 


# Generate makefile
cmake . 

# Compiling with make

Note: The figure `4` in the command below determines the number of threads that will be compiled (more is better, but do not do more than 10, since the computer can hang tightly).
make -j 4 


# Inject cheat


First, make sure that CSGO is running (NOT through Wine), no matter whether you are in the game or in the main menu.
Open the folder where AimTux was compiled, if you have not already done so
cd AimTux 

Now you can inject the cheat into the game using the script 'load'
./load 
