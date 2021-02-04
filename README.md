# mymc
Reviving a PS2 Memory Card Image Utility from 2004 by Ross Ridge.

# Description

A tool for working with and manipulating PS2 memory card image files, written in Python 2 using WxPython to allow for a GUI mode.

# Features

- Open, View, Edit & Delete Save Files
- Import & Export save files from and to .psu, .max file formats
- macOS Dark Mode support
- Includes GUI mode for ease of use

# Changes

Hey there, CC here! Here's a list of the changes I made whilst reviving this project:

- Updated GUI framework from an ancient version of wxPython from 2004 to the latest
- Enabled Dark Mode for macOS via py2app

I didn't want to simply grab the source and update it slightly. I figure It might come in handy to those in the PS2 scene.

# Requirements

Python 2.6/2.7, latest version of WxPython (Phoenix), py2app

# Building/Running

# macOS (For Dark Mode Support)
    python setup.py py2app
    cd ./dist
    open -a mymc.app
# Linux & macOS (Without Dark Mode Support)
    python ./mymc.py
