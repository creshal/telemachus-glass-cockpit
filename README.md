# "Glass Cockpit" for Telemachus

## Installation

Install and set up
[Telemachus](https://github.com/richardbunt/Telemachus/releases) normally.
If there are problems with Telemachus itself, it's Not My Problem™. Make sure
it works before proceeding.

If Telemachus works, drop everything into
`GameData/Telemachus/Plugins/PluginData/Telemachus/`. The files should be
recognized without restarting the game. Then, open `/telemachus/index.html` and
open the module you want (or open them directly). You can add/modify files while
Telemachus is running if you want to add/change stuff.

## Usage

<img src='http://i.imgur.com/3ox1IEC.png'/>
`readout.html` contains some basic, passive readouts of your vessel's stats.
You can add/remove fields by manipulating the HTML layout, the JS should
Just Work™ and recognize the fields. See the file's documentation for more info.

<img src='http://i.imgur.com/kZCTYjc.png'/>
`controls.html` has ship controls. Row 1 and 2 are basic KSP toggle buttons.

Row 3 has action groups 1, 2, 3 and 10. You'll probably want to change their
names and/or add more groups.

Rows 4 and 5 have Mechjeb SmartASS controls and thus only work with it installed
on the ship. (Telemachus cannot yet use 0.90's advanced SAS features.)

Row 6: Stage and abort do exactly what they're supposed to (probably.)
 "ERR?" lights up when there's problems with a command. This can happen
due to connection issues, the game being paused, Mechjeb/Telemachus
antenna/power missing, no ship being loaded etc. pp.

As with the readouts, new buttons can be easily added by fiddling with the HTML,
the JS code takes care of the rest. Documentation in the file.

<img src='http://i.imgur.com/o5FOWdd.png'/>

A navball (may also work as muffin). Uses a texture made by
[WhiteOwl](http://forum.kerbalspaceprogram.com/threads/69540-Making-high-contrast-nav-ball!?p=1096713&viewfull=1#post1096713),
as I'm probably not able to redistribute KSP's own. Also it looks decent.
The texture (`navball.png`) can be replaced by any you can find in the linked
thread, or any you made yourself. The readouts are hardcoded and the whole thing
is rather messy, but it should otherwise work.

