# xborder
Active window border replacement for window managers.

## xborder:
![image](https://user-images.githubusercontent.com/82973108/160370439-8b7a5feb-c186-4954-a029-b718b59fd957.png)
## i3:
![image](https://user-images.githubusercontent.com/82973108/160370578-3ea7e3e9-723a-4054-b7b0-2b0110d809c0.png)

## Fun desktop stress toy
![fun](https://user-images.githubusercontent.com/82973108/160370871-31f4dd1a-c508-4a82-a980-4724186ee8f0.gif)

## Install
Install `python3-gi` dependency:
```
sudo apt install python3-gi
```

With [`pipx`](https://pypa.github.io/pipx/):
```sh
pipx install git+https://github.com/coloursofnoise/xborder --system-site-packages
```

With support for a window manager:
```sh
pipx install "xborder[{window_manager}] @ git+https://github.com/coloursofnoise/xborder" --system-site-packages
```

Replace `{window_manager}` with any of the following supported window managers:
* i3
<!--* all (equivalent of [i3,...])-->

## Usage
```sh
xborder [wm]
```

### Config
Config is on like 17-23 of the xborder file. 
