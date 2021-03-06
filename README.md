[xdm-unexicon-theme -- read me first file.  2019-09-08]: #

xdm-unexicon-theme
===============

Package xdm-unexicon-theme-1.4 was released under GPLv3 license 2019-09-08.

This is an XDM theme for unexicon.  The source for xdm-unexicon-theme
is hosted at (https://github.com/bbidulock/xdm-unexicon-theme).  What it includes
is all of the components necessary for the theme.


Release
-------

This is the `xdm-unexicon-theme-1.4` package, released 2019-09-08.  This
release, and the latest version, can be obtained from [GitHub][1], using
a command such as:

    $> git clone https://github.com/bbidulock/xdm-unexicon-theme.git

Please see the [NEWS][3] file for release notes and history of user
visible changes for the current version, and the [ChangeLog][4] file for
a more detailed history of implementation changes.  The [TODO][5] file
lists features not yet implemented and other outstanding items.

Please see the [INSTALL][7] file for installation instructions.

When working from `git(1)`, please use this file.  An abbreviated
installation procedure that works for most applications appears below.

This release is published under GPLv3.  Please see the license in the
file [COPYING][9].


Quick Start
-----------

The quickest and easiest way to get `xdm-unexicon-theme` up and running is to run
the following commands:

    $> git clone https://github.com/bbidulock/xdm-unexicon-theme.git
    $> cd xdm-unexicon-theme
    $> ./autogen.sh
    $> ./configure
    $> make
    $> make DESTDIR="$pkgdir" install

This will configure, compile and install `xdm-unexicon-theme` the quickest.  For
those who like to spend the extra 15 seconds reading `./configure
--help`, some compile time options can be turned on and off before the
build.

For general information on GNU's `./configure`, see the file
[INSTALL][7].


Running
-------

Read the manual page after installation:


Issues
------

Report issues on GitHub [here][2].



[1]: https://github.com/bbidulock/xdm-unexicon-theme
[2]: https://github.com/bbidulock/xdm-unexicon-theme/issues
[3]: https://github.com/bbidulock/xdm-unexicon-theme/blob/1.4/NEWS
[4]: https://github.com/bbidulock/xdm-unexicon-theme/blob/1.4/ChangeLog
[5]: https://github.com/bbidulock/xdm-unexicon-theme/blob/1.4/TODO
[6]: https://github.com/bbidulock/xdm-unexicon-theme/blob/1.4/COMPLIANCE
[7]: https://github.com/bbidulock/xdm-unexicon-theme/blob/1.4/INSTALL
[8]: https://github.com/bbidulock/xdm-unexicon-theme/blob/1.4/LICENSE
[9]: https://github.com/bbidulock/xdm-unexicon-theme/blob/1.4/COPYING

[ vim: set ft=markdown sw=4 tw=72 nocin nosi fo+=tcqlorn spell: ]: #
