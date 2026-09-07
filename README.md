# Kingdoms & Caravans 0.2.1

## Early Windows friend playtest

Download the current Windows build:

[Download KingdomsAndCaravans-windows.zip](https://github.com/RoyGSlade/KingdomsAndCaravans/releases/download/v0.2.1/KingdomsAndCaravans-windows.zip)

More project context: [Project page](https://donavencrenshaw.com/kingdoms-caravans/)

This is an early, unfinished, unsigned Windows x64 prototype. Expect rough edges, balance changes, missing polish, and bugs. The download is shared for friendly playtesting, not as a finished commercial release.

## Play

1. Extract the entire ZIP into a folder.
2. Run `KingdomsAndCaravans.exe`.
3. If Windows shows an unsigned-app warning, review it carefully before choosing whether to continue.

Godot, Blender, Python, and an internet connection are not needed to play.

## Your first city

- Place a farm near the granary. Available citizens become teamsters and carry reserved planks to the site before construction.
- Place a woodcutter near trees and a sawmill between it and the storehouse. Logs move to the sawmill, become planks, and then move to storage.
- Keep a farm staffed. Everyone eats, including soldiers and people in training.
- Build a house and keep a food reserve to attract civilians.
- Build a barracks and recruit carefully so the city still has workers.
- Defend the castle. Six raiders arrive from the north at 3:30, then twelve from the west at 7:30. Losing the castle ends the match.

## Controls

WASD pans the camera. Q/E rotates it. R resets the camera. The mouse wheel zooms. Left click selects; left drag selects soldiers. Right click moves selected soldiers or attacks an enemy. H holds position. Esc cancels placement or pauses. F5 saves. F9 opens load confirmation. Click the minimap to move the camera.

## Saves and updating

Version 0.2 uses `kingdom-city-v2.json`, with a `.bak` backup. Version 0.1 saves cannot load in 0.2, but the older build remains playable with its original save format.

Open the menu and choose **Check for updates**, then **Download update** when a newer version is offered. The update downloads into a separate folder so the existing install and version 0.2 save remain available. Choose **Restart with update** when ready; the current kingdom is saved before switching. The update check and download use GitHub and require an internet connection.

Your existing shortcut opens an activated newer version automatically. To deliberately run an older build, launch it with `-- --skip-update-forward`.

## Feedback

Optional feedback is welcome through the [playtest issue form](https://github.com/RoyGSlade/KingdomsAndCaravans/issues/new?template=playtest.yml). Useful reports include what you tried, what happened, what you expected, and whether the first wave made you want to continue.

![Early Growing City playtest](screenshot.png)

This repository hosts player information and release downloads. It does not publish the game source under an open-source license. Bundled Godot notices are included in the ZIP.
