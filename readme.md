Install yt-dlp locally:
### make sure yt-dlp install
```sh
    yt-dlp --version
```
### if no version return , follow the step
```sh
    sudo rm /usr/lib/python3.*/EXTERNALLY-MANAGED
```
```sh
    sudo pip install --user yt-dlp
```
```sh
    sudo chmod +x /usr/local/bin/yt-dlp
```

## if don't install use,alter native way
 ### aler naive
```sh
    python3 -m venv .venv
```
```sh
    source .venv/bin/activate
```


```sh
    nano ~/.bashrc
```
```sh
    export PATH="$HOME/.local/bin:$PATH"
```
```sh
    source ~/.bashrc
```
```sh
    yt-dlp --version
```

### For Linux (Ubuntu/Debian-based systems)

#### Install FFmpeg:
```sh
    sudo apt install ffmpeg
```
### Verify FFmpeg installation:
```sh
    ffmpeg -version
```
##### If FFmpeg is installed successfully, you'll see the version details printed to the terminal.

### For macOS:
```sh
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
### Install FFmpeg via Homebrew:

```sh
    brew install ffmpeg
```
### For Windows:

####  Download FFmpeg:
        Go to the FFmpeg official website and download the Windows build.

#####  Extract the downloaded ZIP file:
        Extract the files to a folder (e.g., C:\ffmpeg).

#####  Add FFmpeg to your PATH:
        Open System Properties > Advanced > Environment Variables.
        Under "System variables," find the Path variable, and click "Edit."
        Add the path to the bin folder inside the FFmpeg folder (e.g., C:\ffmpeg\bin).


