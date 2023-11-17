# Mouse-Auto-Clicker

This Python script uses the pynput library to create a simple auto-clicker. The auto-clicker can be toggled on and off using a specified key (TOGGLE_KEY). Leveraging the pynput library, the script runs a continuous background thread that simulates a left mouse button click when the clicking flag is set to True. The clicking functionality can be easily toggled on and off using a designated key, defined as TOGGLE_KEY. This simple yet versatile tool provides users with the ability to automate repetitive clicking tasks in various applications or games. The script's parameters, such as the toggle key and clicking interval, can be easily customized to suit individual preferences. It is important to use this tool responsibly and in compliance with the terms of service of the targeted applications.

## Requirements
 - Python 3.x
 - pynput library (pip install pynput)
   
## How it works
The script utilizes threading to run a continuous loop in the background that clicks the left mouse button at regular intervals when the clicking flag is set to True. The clicking flag is toggled by pressing the designated toggle key (TOGGLE_KEY).

## Usage
Install the required dependencies:

```sh
pip install pynput
```

```sh
python auto_clicker.py
```

Press the toggle key (t by default) to start/stop the auto-clicking.

## Configuration
You can customize the script by modifying the following variables:

 - TOGGLE_KEY: The key to toggle the auto-clicking.
 - clicking_interval: The interval between each click (in seconds). You can adjust this in the clicker function.
