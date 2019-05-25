bat-pkgsrc
==========

NetBSD pkgsrc script for script for `bat`.

You can find `bat` [here][1]

NOTE: This package is not yet available in the pkgsrc tree.

Installation
------------

Copy `textproc/bat` folder to `/usr/pkgsrc` directory.

NOTE: If your pkgsrc directory is different from above, copy to the respective
place.

Usage
-----

Once you have copied the folder, install it as you would do for any port.

`$ cd /usr/pkgsrc/textproc/bat`<br>
`$ make install clean`

For a list of dependencies for the build check [here][2]

NOTE: If you are using pkgsrc in a non NetBSD system, replace `make` with
`bmake` in the above example.

Credits
-------

* `bat` is developed and maintained by the [David Peter][3]
* Thanks to `@coypoop` and `leot@` for reviewing and suggesting fixes to the
  package.

License
-------

BSD 2-clause. See LICENSE.

[1]: https://github.com/sharkdp/bat
[2]: https://github.com/sharkdp/bat#installation
[3]: https://david-peter.de/
