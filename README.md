# Dash to Dock Floating

## A Floating Dock for GNOME Shell

This extension is a fork of the popular [Dash to Dock](https://github.com/micheleg/dash-to-dock), enhanced with "floating" capabilities. It allows you to transform the dash into a floating dock with customizable margins and border radius, giving your desktop a modern, distinct look.

**Credit:** Heavily based on Dash to Dock by [micheleg](https://github.com/micheleg). Original floating concepts inspired by previous floating dock implementations.

### Features
All the power of Dash to Dock, plus:
-   **Floating Mode**: Detach the dock from the screen edge.
-   **Custom Margins**: Adjust the distance from the screen edge.
-   **Border Radius**: Customize the roundness of the dock corners and app highlights.
-   **Sync Highlight**: Option to sync app icon highlight radius with the dock border radius.

### Installation from Source

Clone this repository and install using `make`.

```bash
git clone https://github.com/ahmedhanbal/dash-to-dock-floating.git
cd dash-to-dock-floating
make install
```

After installation, reload GNOME Shell (`Alt+F2`, type `r`, `Enter` on X11, or re-login on Wayland) and enable the extension "Dash to Dock Floating" using the Extensions app.

### Configuration
Settings can be accessed via the GNOME Extensions app. 
-   **Floating Dock Tab**: Controls for margin, border radius, and icon highlight settings.

### License
Distributed under the GNU General Public License, version 2 or later. See COPYING for details.
