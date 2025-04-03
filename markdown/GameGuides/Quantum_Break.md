![Quantum Break](\Images\Quantum_Break.png "Shot by barkar-b"){.shadowed .autosize}

## Summary

Feature | Supported
--|--
Vanilla Photo Mode | No
Hotsampling | Yes (With tools)
DSR | Yes (With tools)
Custom Aspect Ratios | No
Reshade | Yes (DX11)
Ansel | No
Graphics API | DirectX 11
 
## Tools

* [Camera tools by Hattiwatti](https://mega.nz/#!0No22IYR!37V0-YwTXNfpWoPg-OnSXiSmQ5n3l50OvyR3kksDb8c) Password for the zip: `CinematicTools`  
**Features**: Free Camera, FOV Control, Timestop, HUD toggle, DOF override (cutscenes), Filmgrain toggle, Movement Blur toggle

@alert Important 
In order to hotsample you just have to open the tool.
For custom aspect ratios you will need to set the AR while you are in freecam mode.
@end

## Usage

1. Extract files where ever you want
2. Start the game
3. Launch the tools
4. A console window should appear with some text confirming everything's OK

## Controls

- **INSERT** - Toggle camera
- **DELETE** - Toggle timestop
- **HOME** - Toggle HUD
- **END** - Toggle tools UI
- **WASD** - Camera movement
- **Mouse** - Camera orientation
- **PageUp** - Increase FoV
- **PageDown** - Decrease FoV

## Hotsampling specific info

To hotsample correctly you have to make sure have in SRWE the ForceExitSizeMove checkbox checked to hotsample correctly. 
Additionally to use custom aspect ratios, be sure to follow these steps in the right order:

- Enable the free camara
- Set aspect ratio
- Check the override custom AR checkbox
- Use SRWE to resize the resolution
- Uncheck the override AR checkbox to fix the broken lighting. This last step is particularly important since it breaks the games lights when it is enabled.

## Useful Links

* [PC Gaming Wiki](https://pcgamingwiki.com/wiki/Quantum_Break)