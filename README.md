# keynavish

Control the mouse with the keyboard, on Windows.

This is a rewrite of [keynav](https://github.com/jordansissel/keynav)
for Windows.

## Compiling

The project can be compiled with Visual Studio +
[VisualD](https://rainers.github.io/visuald/) with the supplied solution
file.

## Configuration

TODO

## Compatibility with keynav

keynavish aims to support everything keynav does, so you can simply copy
over your keynavrc without having to make any changes.

Any behaviour that differs or any feature that isn't implemented
is a bug.

Currently only basic functionality is implemented. More specifically,
`grid`, `cell-select`, `grid-nav`, `loadconfig`, `record`, `playback`,
`history-back`, and config file loading aren't implemented yet.

## Known issues

* Not DPI aware
* Most likely doesn't work with multiple displays

Pull requests or issues with more information are very welcome.

## License

keynavish is licensed under the [GNU GPLv2](/LICENSE).