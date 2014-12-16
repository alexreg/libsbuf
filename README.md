libsbuf
=======

*libsbuf* is an implementation of the [FreeBSD][FreeBSD] **safe string composition functions** for OS X.

The source code is based on the [source][FreeBSD source] of [FreeBSD 11][FreeBSD release].

Building
--------

To build the library, simply run `./build` from the root directory of the project. This produces output in the `lib/` and `man/` directories (and intermediary output in `obj/`).

Installing
----------

To install the library, first build it, then run `./install` as superuser from the root directory of the project. This will install the library under the default prefix directory `/usr/local`.

A custom prefix directory can be specified by setting the `INSTALL_PREFIX` environment variable before installing.

Usage
-----

The manual page for the API is `sbuf(3)`.

[FreeBSD]: https://www.freebsd.org/
[FreeBSD release]: https://www.freebsd.org/relnotes/CURRENT/relnotes/article.html
[FreeBSD source]: https://svnweb.freebsd.org/base/head/
[FreeBSD manual sbuf]: https://www.freebsd.org/cgi/man.cgi?query=sbuf&manpath=FreeBSD+11-current
