# Deskocohort for macOS (test builds)

Little creatures that live on your desktop: they wander around, fetch drawings
and notes, rest, and say goodbye if you click them too much. A green alien in
the menu bar opens its eyes when you hover it.

These are **early test builds**. Things will be rough; that's what your
feedback is for.

## Install

1. Open **[Releases](../../releases)** and download **Deskocohort-macOS.zip**
   from the newest one.
2. Unzip it and drag **Deskocohort** into **Applications**.
3. First launch: **right-click** Deskocohort → **Open** → **Open**.
   (It isn't signed with a paid Apple developer account, so a normal
   double-click is blocked the first time.)
   - If macOS says the app is **damaged**, open Terminal and run
     `xattr -dr com.apple.quarantine /Applications/Deskocohort.app`, then try again.
4. Name your first creature. The green alien appears in the menu bar.

Needs an Apple Silicon Mac (M1 or newer) and macOS 13 or newer.

## Use

- **Click** the menu-bar alien: control panel (spawn creatures, sizes, themes).
- **Right-click** it: clear the desktop, freeze everyone, send feedback, quit.
- **Grab** a creature with the mouse and throw it.

## Feedback

Right-click the menu-bar alien → **Send feedback…** (fills in your macOS and app
version), or open an issue **[here](../../issues/new/choose)**. Screenshots and
"it looked like X, I expected Y" help most.

## Uninstall

Quit from the menu-bar alien, then drag Deskocohort from Applications to the Bin.
Settings live in `~/.config/deskocohort`.
