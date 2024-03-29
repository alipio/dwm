# Alipio's build of dwm

## FAQ

> What are the bindings?

This is suckless, the source code is the documentation! Check out [config.h](config.h).

## Patches and features

- [Clickable statusbar](https://dwm.suckless.org/patches/statuscmd/) with my build of [dwmblocks](https://github.com/alipio/dwmblocks).
- Reads [xresources](https://dwm.suckless.org/patches/xresources/) colors/variables (i.e. works with `pywal`, etc.).
- scratchpad: Accessible with <kbd>mod+-</kbd>.
- New layouts: bstack, fibonacci, deck, centered master and more.
- True fullscreen (<kbd>mod+f</kbd>) and prevents focus shifting.
- Windows can be made sticky (<kbd>mod+s</kbd>).
- [hide vacant tags](https://dwm.suckless.org/patches/hide_vacant_tags/) hides tags with no windows.
- [stacker](https://dwm.suckless.org/patches/stacker/): Move windows up the stack manually (<kbd>mod-k/j</kbd>).
- [shiftview](https://dwm.suckless.org/patches/nextprev/): Cycle through tags (<kbd>mod+g/;</kbd>).
- [vanitygaps](https://dwm.suckless.org/patches/vanitygaps/): Gaps allowed across all layouts.
- [swallow patch](https://dwm.suckless.org/patches/swallow/): if a program run from a terminal would make it inoperable, it temporarily takes its place to save space.

## Installation for newbs

```bash
git clone https://github.com/alipio/dwm.git
cd dwm
sudo make install
```
