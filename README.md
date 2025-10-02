# SUPER chip-8 emulator
SUPER chip-8 emulator in rust with backwards compatibility
## REQUIREMENTS
just sdl2
### Windows
you can find binaries here: https://github.com/libsdl-org/SDL/releases
### Arch
```bash
sudo pacman -S sdl2
```
### Ubuntu
```bash
sudo apt update
sudo apt install libsdl2-dev
```
### Fedora
```bash
sudo dnf install SDL2-devel
```
## CLONE
```bash
git clone https://github.com/sl4Jd/SUPER_chip-8_emulator.git
```
```bash
cd SUPER_chip-8_emulator
```
```bash
git submodule update --init --recursive 
```
## BUILD AND RUN
```bash
cargo run "path/to/rom"
```
Example
```bash
cargo run "schip_roms/Matches.ch8"
```
