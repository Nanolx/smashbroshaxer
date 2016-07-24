smashbroshaxer
================

simple script that aids in executing smashbroshax under Linux.

Requirements:
================
* Linux (x86/x86_64)
* Gtk+ 3
* sudo
* xterm

Usage (interactive mode):
================
* run script
* select wifi device
* select game version
* click 'hax my smash'
* enter your password in terminal
* in game go to Smash > Group
* ... profit?

Usage (non-interactive mode):
================
* smashbroshaxer wifi-interface pcap-file
* enter your password in terminal
* in game go to Smash > Group
* ... profit?

ChangeLog:
================

3.0 (20160724):
* switch to channel 6 (should do stuff faster)
* reset wifi interface after work is done (brings back interwebs)
* display short info strings in terminal windows
* use xterm instead of x-terminal-emulator
  * some terminals like Konsole need extra arguments (--nofork)
  * to properly work as desired, thus enforce xterm so that I
  * don't have fiddle around with that stuff
* add new payloads:
  * US 1.0.1
  * EU-JAP 1.0.1
  * KOR 1.0.8
  * KOR 1.1.0

2.0 (20160724):
* internal improvements
* string changes
* non-interactive mode
* improved layout

1.0 (20160724):
* initial release
