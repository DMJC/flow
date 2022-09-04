# flow
Flow a GNUstep desktop environment

Flow is designed to be an apple-like desktop environment. With a focus on providing useful mac-os like functionality on Linux. The plan is to build on GNUstep and implement a working desktop environment. Where possible, keeping to the Cocoa API.

Design Philospohy:
The desktop UI will be based around the NSMacintoshMenuStyle and the eToileMenuServer code with plans to integrate more deeply with the Window Manager.

Plans:
Update System Preferences.app to include plugins for:
- Xrandr
- Pipewire
- Network-Manager

Fork/Build a more mac-like Finder.app using GWorkspace.

Web Browser:
- Wrap either firefox or chrome browser engines into a GNUstep window so that they play nicely with the environment.

Future/Would like to do:
Implement a Window Manager to control non-gnustep applications and provide a more mac-like experience.
