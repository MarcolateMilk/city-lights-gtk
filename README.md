# City Lights GTK+ 3 Theme

GTK+ 3 theme inspired by the City Lights theme for Atom.

I use Atom together with the City Lights theme since years, because the color palette is really nice and soothing for the eyes. However, I couldn't find a GTK theme that works nicely with this theme, so I made my own!

## Notes

* This theme works with GTK+ 3 ONLY
* This theme was made for i3, I don't plan on testing/supporting other window managers or desktop environments
* You can find my icon theme [here](https://github.com/MarcolateMilk/city-lights-icons)

## Installation

### Requirements

* GTK+ 3
* git

### Linux

To install open your terminal and type:

```sh
mkdir -p ~/.themes/City-Lights && cd ~/.themes/City-Lights
git clone https://github.com/MarcolateMilk/city-lights-gtk .
```

Then edit your `~/.config/gtk-3.0/settings.ini` like so:

```ini
[Settings]
gtk-theme-name = City-Lights
gtk-application-prefer-dark-theme = true
```

If you are using a tiling window manager like i3, I recommend disabling window decorations too:

```ini
gtk-decoration-layout = menu
```

## Credits

* [Yummygum](https://github.com/Yummygum) for their awesome [Atom theme](https://github.com/Yummygum/city-lights-ui-atom)
* [EliverLara](https://github.com/EliverLara) for providing me with a starting point in form of their [Juno GTK theme](https://github.com/EliverLara/Juno)
