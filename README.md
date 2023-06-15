# FL Studio Snap

This is the snap for [FL Studio 21](https://www.image-line.com/fl-studio/). It works on Ubuntu, Fedora, Debian, and other major Linux distributions.

This Windows application runs on Linux using the Wine compatibility layer. For that reason, it may not function as expected. If you encounter issues please report in the issue tracker of this repository.

*Published for <img src="http://anything.codes/slack-emoji-for-techies/emoji/tux.png" align="top" width="24" /> with :gift_heart:*

## Install

```shell
snap install --candidate flstudio
```

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

![FL Studio](screenshot.png?raw=true "FL Studio")

## Reusing this snap

You can use this snap as a reference for creating snaps of other Windows applications. See the [sommelier-core](https://github.com/snapcrafters/sommelier-core) repo for more information on how to snap a Windows application.

If you have any questions about creating snaps of Windows applications then [post in the Snapcraft forum](https://forum.snapcraft.io).

## License

This snap manifest is released under the GPLv2 license. FL Studio itself is a proprietary application by Image-Line.
