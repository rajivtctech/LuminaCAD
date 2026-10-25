# LuminaCAD

**Design 3D-printable lamp shades and photo lithophanes on Windows and Linux.**

![LuminaCAD](docs/img/main-window.png)

LuminaCAD is a parametric lamp-shade designer:

- **Shapes:** round shades or flat-sided lanterns (3 to 8 faces) in six silhouettes.
- **Photo lithophanes:** photos pressed into the panels as relief, so they appear when the lamp is lit, with detail modes down to 0.3 mm for large shades.
- **Surface patterns:** ribs, pleats, scallops and origami facets, with an optional helical twist.
- **Socket ring:** a built-in fitter for E27, E14 or harp fittings.
- **Live preview:** a 3D view lit by a virtual bulb.
- **Your printers:** name your printers with their X, Y, Z build volume; LuminaCAD shows the bed and checks the fit.
- **Sharp on any screen:** a UI scale from 100 to 300 % that follows your display scaling automatically.
- **Design files:** save and reopen designs as single `.lcad` files with the photos inside.
- **Export:** a watertight binary STL, ready for PrusaSlicer, Bambu Studio, OrcaSlicer or Cura.

![Presets](docs/img/presets.png)

## Download

From [Releases](../../releases/latest):

**Windows 10 / 11:** `luminacad-1.5.0-windows-x64.zip`. Extract it anywhere and double-click `luminacad.exe`; there is no installer and no admin rights are needed. To open `.lcad` designs by double-clicking, click **?** → **Open .lcad files with LuminaCAD** once. If Windows says *"Windows protected your PC"*, click **More info**, then **Run anyway**.

**Linux:** `luminacad-1.5.0-linux-x86_64.tar.gz`. Needs glibc 2.35 or newer (Ubuntu 22.04+, Debian 12+, Fedora 36+, Mint 21+), on an X11 or Wayland desktop.

```
tar xzf luminacad-1.5.0-linux-x86_64.tar.gz
cd luminacad-1.5.0-linux-x86_64
./install.sh
```

The Linux installer adds LuminaCAD to your application menu under **Graphics**.

## Free and Pro

| | Free | Pro |
|---|---|---|
| Price | Free | Paid licence |
| Shade size | up to **150 mm** tall | as large as your printer (up to 2000 mm) |
| Every shape, pattern, lithophane, fitter and preset | ✓ | ✓ |

It is the same program on both systems, and a licence file works on either. To upgrade, load the Pro licence file you receive into the program you already have: **Licence** button, top right. No reinstall is needed and no internet connection is involved. Pro licences: **[tctech.co.in](https://tctech.co.in)**.

## Documentation

- **[User Guide](docs/USER_GUIDE.md)** ([PDF](docs/LuminaCAD_User_Guide.pdf)): from first start to expert reference, including print settings and troubleshooting.

## Safety

Use **LED bulbs only** (about 9 W or less) in printed shades, keep the bulb at least 25 mm from the wall, and use certified lamp fittings. PLA softens at 55–60 °C. See *Safety first* in the User Guide.

## About

LuminaCAD is a native C++ program with no third-party libraries. Its renderer, interface, font, image decoders and licence check are all its own.

Free to use under the [LuminaCAD End-User Licence](LICENSE.txt). The source code is not published. © 2026 T&C Technology.
