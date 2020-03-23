# X10Automation
Automate your house with X10 switches, an XM10FL and a Raspberry Pi

This suite allows you to describe a series of actions you wish to follow when various triggers happen.
The triggers include dawn & dusk, X10 messages received from PIRs and X10 commands intercepted from X10 Maxi-controllers and X10 Switches.

Rules are written in a special rule language in a file 'smart.txt'.
The rules are compiled (by a compiler written in C#) to a 'smart file'.
The C++ runtime reads the 'smart file' and then runs the rules via the XM10FL device.

This progam has been running on PCs since the mid-90s and migrated to a Raspbery Pi about 5 years ago.
Whilst this is old technology, I am looking into using modern Philips Hue lights.

You are welcome to use this code (and contribute) without any guarantees.
