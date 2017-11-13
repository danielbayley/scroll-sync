# scroll-sync Atom editor package

Synchronize scrolling of two editor panes by content.
--

See project at [GitHub](https://github.com/georgebrindeiro/scroll-sync).

![Animated GIF](https://github.com/georgebrindeiro/scroll-sync/blob/master/scroll.gif?raw=true)

(If the image above is not animated then click on it).

# Usage
- Open two files in separate panes so they are both visible.
- A new icon (Up Down Double Arrow) will appear in the status bar.
- If the icon isn't filled, that means scroll-sync is off: ⇕
- If the icon is filled, that means scroll-sync is on: ⬍
- Clicking the icon toggles scroll-sync on/off.
- The keyboard shortcut `Ctrl-Alt-S` *also* toggles scroll-sync on/off.
- Scroll either editor pane and the other editor pane will scroll to match.
- When sections of the files don't match, the editor pane you are directly controlling will scroll through the entire file as normal.  The other pane will stop or jump ahead as needed to keep the content aligned.
- You may switch between the files to change which is the "master" and which is the "slave".

# License
Copyright Mark Hahn by MIT license.
