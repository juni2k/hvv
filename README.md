# hvv

Navigate the seedy underworld of Hamburg in a truly dystopian way!

**2022:** HVV changed things on their end and this script is now
considered broken. However, I don't have any incentive to fix it
since I don't live there anymore. Feel free to fix things and make
a pull request.

## What is this?

This is a command-line application for interfacing with the [routing
service of Hamburger Verkehrsverbund][hvv-web]. It tends to be less
clunky and frustrating than the official website when you are in a rush.

[hvv-web]: https://geofox.hvv.de

## Perks

- **Fast:** optimized for speed and perceived responsiveness!
- **Friendly:** unspecified command-line arguments trigger an
  interactive mode!
- **Flexible:** written in (mostly) readable and sane Perl!

## Installation

`hvv` depends on `Mojolicious` and `IO::Socket::SSL`, external Perl
modules.  They are likely available in your distro's repository.

Other than that, just drop `hvv` in your path and you are good to go!

## Misc

- The oldest supported version of perl is v5.18. If something does not
  work under v5.18 (or newer), please let me know.
- I'd like to thank [knoellle][knoellle] for inspiration and helping me
  understand some API quirks, and [Bendodroid][bendodroid] for
  discovering lots of bugs and breaking things as often as possible.

[knoellle]: https://github.com/knoellle
[bendodroid]: https://github.com/Bendodroid

## License

```
MIT License

Copyright (c) 2019 Martin Frederic 

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
