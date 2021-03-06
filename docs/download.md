---
layout: page
title: 'Download'
permalink: /download
---

Recommended: [Java 8u152] installed. Minimum: Java 8u40 installed.

[Click here to download CircuitSim!]

Changes
-------

Version 1.7.4 changelog:
- Fix several bugs with wire creation when dragging components
- Give an option to send an error report upon unexpected errors
- Minor bug fixes


Version 1.7.3 changelog:
- Fix blue wire issues with Tunnels and subcircuits
- Highlight wires when clicking on them
- Ctrl+scroll now zooms in/out
- Right clicking when placing components or dragging wires cancels the action
- Fix bug with intersecting wires being auto-joined on drag
- Improved error handling


Version 1.7.2 changelog:
- Add Probe component, which lets you observe values on wires without resorting to output pins
- Improve behavior multi-component selection when holding down control by disabling drag-less wire creation when control is held down
- Copy doesn't do anything when nothing is selected instead of emptying the clipboard
- Other minor bugs fixed


Version 1.7.1 changelog:
- Squashed tunnel bugs: now short-circuits should propagate properly across them and tunnels should work properly
- Added comparison type to Comparator: now you can do both 2's complement and unsigned comparison
- Draw magnifying glass to subcircuit components when hovering over them to indicate ability to view internal state
- Officially making a file format change supporting library paths
- Other minor bugs fixed


Version 1.7.0 changelog:
- Big thanks to Cem Gokmen for helping with the Mac issues and Austin Adams for gradle-ifying the repo!
- Now supporting both Java 8 and 9 - thanks to Austin Adams for figuring out how to create a multi-release Jar.
- Huge rendering performance improvements, especially for Mac
- Fixed keyboard shortcut issue on Mac
- Use system menu bar on Mac instead of the in-app bar
- Added an update checker that notifies you when there is a new version
- Fixed a bug with subcircuits where it pushed values through output pins, causing seemingly un-explainable short circuits.
- Improved behavior of tab selection when moving them or deleting them, especially with undo/redo
- Many minor bug fixes and improvements


Version 1.6.2 changelog:
- Fixed exceptions being thrown when using Tunnels
- Now you don't have hit enter to update a text or value property, someone complained that it was annoying. The component is automatically updated when you unfocus from the text input.
- Multi-bit wires with a floating bit (X) now show up as dark blue instead of black
- Button now has directions


Version 1.6.1 changelog:
- Improved behavior when dragging components to also delete wires whenever they overlap existing ones
- Huge performance increases with subcircuits and tunnels. Bad designs will still be very slow to run the autograder in.
- Now showing Help dialog on first run.


Version 1.6.0 changelog:
- Added creation of new wires when dragging components. This allows maintaining existing connections when dragging components to new locations.
- Hold CTRL before beginning the drag to disable this.
- Fixed file load issue where an error was thrown if the folder doesn't exist anymore.
- Fixed issues with dragging + keyboard shortcuts
- Fixed an undo bug when updating components

[Java 8u152]: http://java.sun.com/
[Click here to download CircuitSim!]: https://www.roiatalla.com/public/CircuitSim/
