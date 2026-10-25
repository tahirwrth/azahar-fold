# Azahar Fold

An unofficial fork of [Azahar](https://github.com/azahar-emu/azahar), a free and
open-source Nintendo 3DS emulator, adding cover-screen shoulder button controls for
foldable Android phones.

*This fork is not affiliated with or endorsed by the Azahar project or Nintendo.
Please do not report problems with this fork to the Azahar developers.*

## What this fork adds

On supported Android foldables (developed and tested on the Samsung Galaxy Z Fold 6), the
L and R shoulder buttons can be placed on the cover screen while the game and the
rest of the controls stay on the main inner screen.

- Cover-screen touch zones for L and R, toggled from the in-game menu
- The option only appears on devices that report rear-display support, and only
  while the phone is open

Everything else behaves like upstream Azahar.

### Known limitations

- Tested on one device so far. Other foldables may behave differently. This is an experimental feature.
- Existing secondary display functionality has not been tested, and may have issues.

## Building

This is an Android-focused fork. Build it the same way as upstream, using
[Azahar's build instructions](https://github.com/azahar-emu/azahar/wiki/Building-From-Source).
The relevant changes are on the `dev` branch.

## Reporting issues

Open an issue on this repository. Include your device, Android version, the
graphics API you used (OpenGL or Vulkan), and a logcat if the app crashed.

## Minimum requirements

Same as upstream Azahar:

​```
Operating System: Android 10.0+ (64-bit)
CPU: Snapdragon 835 SoC or better
GPU: OpenGL ES 3.2 or Vulkan 1.1 support
Memory: 2GB of RAM. 4GB is recommended
​```

Cover-screen controls additionally need a foldable that supports presenting
content on its rear display.

## License and modifications

This project is a modified version of Azahar and is licensed under the
GNU General Public License v3 or later. See `LICENSE.txt`.

Modified by tahirwrth, October 2026. See the commit history for the full list of
changes. Original code is copyright the Citra Emulator Project and Azahar Emulator
Project and their contributors.

## Credits

Azahar is the continuation of Citra and is developed by its community of
contributors: https://github.com/azahar-emu/azahar
