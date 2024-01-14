# Build instructions
Here you will find instructions on how to properly configure your preferred Linux-based OS distribution (or Distro for short) to compile OpenBangla Keyboard.
The next subchapters document how to manually compile OpenBangla Keyboard from source, alongside an automated buildscript called make-pkgs.

## Build requirements of OpenBangla Keyboard

- GNU GCC, G++ compiler or Clang
- Rust 1.34.0 or later
- GNU Make or Ninja and Meson
- CMake
- Qt 5.5 or later
- iBus development library
- fcitx development library
- Zstandard compression library (zstd)