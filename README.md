Lawnchair
--------

A simple application launcher.

## Screenshot

![screenshot](screenshot.png)

## Potential Use Cases

* Some open-source desktop environments limit the application launcher to the primary display; pin Lawnchair to a multi-screen dock (or assign it a shortcut key) and it launches on the current display.
* An alternative launcher for tiling window managers.

## Build
Configure instructions are available in [CONFIGURE.md](CONFIGURE.md).

```
$ meson --prefix=/usr build
$ cd build
$ sudo ninja install
```

### Build Dependencies

Arch

```
$ sudo pacman -S gtk3 vala meson ninja libgee
```

Ubuntu

```
$ sudo apt install libgtk-3-dev libgee-0.8-dev valac meson ninja-build
```

Fedora

```
$ sudo dnf install gtk3-devel vala meson ninja-build libgee-devel
```

