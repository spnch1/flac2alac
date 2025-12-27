# flac2alac

Converts \*.FLAC files to \*.M4A (ALAC).

## Installation:
```bash
git clone https://github.com/spnch1/flac2alac.git
cd flac2alac
chmod +x flac2alac
sudo cp flac2alac /usr/local/bin
```

## Usage:
```bash
# Convert current directory
flac2alac

# Recursive scan (converts the entire directory with subdirectories)
flac2alac -r <directory>

# Nuclear option (strips art if a file causes ffmpeg to crash)
flac2alac --no-art
```

## Requirements
* ``ffmpeg`` (``brew install ffmpeg``)
* macOS / Linux (... why'd you be using it on Linux?)

<sub>blah blah blah, got tired of Music.app not supporting my beloved FLACs, so i wrote this wrapper around ffmpeg</sub>
