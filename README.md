# PiDOS

The goal of this project is to make a basic lightweight OS for the Raspberry Pi similar to MSDOS with all the basic hardware functionality present + multitasking.

## Functionality Goals / Device Drivers
* Bultin WIFI
* USB Flash Drive
* SDCARD
* Keyboard
* Mouse
* Serial console support via TX/RX lines
* (N)(P)Curses Clone + panels
* HDMI
* exFat
* Text Editor
* Port TCC (https://bellard.org/tcc/) & NASM (https://www.nasm.us/) to become self compiling
* More GPU support
* MultiTasking
* Port or code from scratch basic userland utils like vi
* TCP/IP Stack for IPv4 and IPv6
* Ethernet Stack
* USB External Hard Drive support
* pdksh for first program / shell + for start scripting and services in general
* Python 3.x
* Lua
* RasperryPi libs for python
* JAVA! (and associated RasperryPi Libs)
* Native support for SkipJack NSA Encryption Algorithm because reasons
* No User/groups logins, as this adds too much complexity that is not desired for intended applications.
* Signed executable security protection + warnings

## License
 
Copyright (C) 2021 William Welna (wwelna@occultusterra.com)
  
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
