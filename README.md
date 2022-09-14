# Description
This is a simple python script to quickly lookup word's definition on the internet in a popup window.

# Prerequisites
This application works only on linux, specifically on X11 as `pywebview` has some issue with wayland.

You need to have `xclip`

```
sudo apt install xclip
```

and the following python libraries

```
pip3 install pyautogui pynpt pywebview
```

# Setup
Make this script executable using `chmod +x search`. Then create a
global shortcut to run this script whenever your defined key combination
is pressed.

# Preview
![demo](https://user-images.githubusercontent.com/54985621/190110891-5cfce075-9940-41c8-b602-efe7e9f3cc4a.png)

You can close the popup by pressing `Esc` key.
