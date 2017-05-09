# AimTux
Cheat For CS:GO on Linux
# Instruction
# Ubuntu-Based / Debian:
sudo apt-get install cmake g++ gdb git libsdl2-dev zlib1g-dev 

# Arch:
sudo pacman -S base-devel cmake gdb git sdl2 

# Fedora:
sudo dnf install cmake gcc-c++ gdb git libstdc++-static mesa-libGL-devel SDL2-devel zlib-devel 


# Gentoo:
sudo emerge cmake dev-vcs/git gdb libsdl2 mesa 

# Arch Linux (Manjaro, Antegros):
После загрузки AimTux с помощью команды ниже и перехода в папку с ним: 
cd pkg 
makepkg -si 
cd .. 



# Download AimTux:
git clone --recursive https://github.com/AimTuxOfficial/AimTux  
cd AimTux 


# Generate makefile
cmake . 

# Compiling with make

Замечание: Цифра `4` в команде ниже определяет количество потоков, с которыми будет происходит компиляция (больше - лучше, но не делайте больше 10, так как компьютер может намертво зависнуть).
make -j 4 


# Inject cheat


Во-первых, удостоверьтесь, что CSGO запущена (НЕ ЧЕРЕЗ Wine), без разницы - в игре вы или в главном меню. 
Откройте папку, где AimTux был скомпилирован, если вы ещё этого не сделали
cd AimTux 

Теперь вы можете инжектить чит в игру с помощью скрипта 'load'
./load 
