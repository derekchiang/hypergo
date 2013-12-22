# hypergo

`hypergo` is a Go client for [HyperDex](https://github.com/rescrv/HyperDex).  This is part of my research project.

## Installation

First of all, [install HyperDex](http://hyperdex.org/doc/latest/InstallingHyperDex/#chap:installation).  This is necessary because hypergo relies on HyperDex's official C client.

If installing via a package manager, you would want to also install the HyperDex dev packages. An example based on Debian would be, `apt-get install hyperdex libhyperdex-client-dev libhyperdex-admin-dev libhyperdex-dev`

Then, `go get github.com/derekchiang/hypergo`

## Status

Usable.

## Credit

Thanks to tiborvass for contributing some of the original code via [hyperclient](https://github.com/tiborvass/hyperclient).

## License

Please refer to the [license for HyperDex](https://github.com/rescrv/HyperDex/blob/master/LICENSE).
