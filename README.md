# C++ VSCode Project Template

## Setup

### Ubuntu/WSL

```
sudo apt update
sudo apt install build-essential git cmake ninja
```

### macOS

```
brew update
brew install build-essential git cmake ninja
```

### Windows (MSYS2)

Install git from any vendor

Add MSYS `bin` directories to PATH:
* `C:\msys64\usr\bin`
* `C:\msys64\mingw64\bin`

```
pacman -Syuu
pacman -S mingw-w64-x86_64-toolchain mingw-w64-x86_64-cmake mingw-w64-x86_64-ninja
```

### General
```
python -m .venv venv
source .venv/bin/activate	# Linux / macOS
.\.venv\Scripts\activate	# Windows PowerShell
python -m pip install pre-commit
pre-commit install
```

## Run/Debug

* Select lauch target `debug-helloworld` and run it.
