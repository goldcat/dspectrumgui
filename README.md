# DSpectrumGUI

The goal of this app is to make it trivial to demodulate common RF signals, and provide a digital worksheet for your reverse engineering efforts.

![DSpectrumGUI Screenshot](https://raw.githubusercontent.com/tresacton/dspectrumgui/master/public/screenshot.png)

# Installation 
Step by step instructions for Kali Linux (Debian based OS) are available in the wiki: <https://github.com/tresacton/dspectrumgui/wiki/Installing-DSpectrumGUI> 


# Features
* Ability to create devices
* Wraps Inspectrum and uses its "Extract Symbols" feature to help convert pulses into raw binary
* Automatic analysis of the binary to determine the modulation and encoding types (see Supported modulation types)
* Some error detection and verbose comments where the app believes it knows which modulation type would be valid if the capture wasn't aligned correctly in Inspectrum
* Reverse Engineering Worksheet to help you visualise the packet structure and comment on sections of the signal
* Binary Generation for RFCat transmission (currently only supports PWM 77/25, support is currently being added for other modulation types)

# Usage
The wiki will be updated as I have time. In the interim, there's a high-level PDF guide I developed for a workshop which demonstrates the basic use of this application. It's available here: <https://github.com/tresacton/dspectrumgui/raw/master/public/DSpectrumGUI%20%E2%80%93%20Reverse%20Engineering%20Guide.pdf>




