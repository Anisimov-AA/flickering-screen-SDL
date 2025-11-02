A real-time TV static effect using C and SDL2 for direct pixel manipulation

<div align="center">
  <img src="img/tv.jpg" alt="Flickering Screen" width="600"/>
</div>

## Setup

**Requirements:** C compiler (GCC), SDL2

1. Install SDL2 (Ubuntu)
```bash
sudo apt update && sudo apt install libsdl2-dev
```

2. compile
```bash
gcc tv.c -o tv -lSDL2
```

3. run
```bash
./tv
```

## Usage

- Launch → window opens with animated static
- Close window or press ESC to exit
- Each frame generates new random pixel values (classic TV noise effect)
