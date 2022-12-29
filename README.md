# uxn autokalimba (AZERTY)

*A fork of [Lynn](https://github.com/lynn)'s project. Modified so I could use it with my keyboard layout.*

A version of the [autokalimba](https://github.com/lynn/harp) for the [uxn](https://100r.co/site/uxn.html) / Varvara computer.

It's a small chordal instrument you can play on your keyboard:

![image](https://user-images.githubusercontent.com/16232127/177855203-3114ea3b-2073-4656-88b0-bf3ef0d605f6.png)

## Assembly

```sh
uxnasm harp.tal harp.rom && uxnemu harp.rom
```

## Controls

* <kbd>AZER</kbd> <kbd>QSDF</kbd> <kbd>WXCV</kbd> — Play bass note
* <kbd>YUIOP</kbd> <kbd>HJKLM</kbd> <kbd>N,;:/!</kbd> — Play chord
* <kbd>Space</kbd> — Play the fifth scale degree in the bass
