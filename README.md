# GBDK

```console
$ export GBDKDIR=`pwd`/build/ppc-unknown-linux2.2/gbdk/
$ make
$ cd build/ppc-unknown-linux2.2/gbdk/examples/gb
$ make
```

Patched GBDK 2.96a for the latest compilers.

Original site:

  * http://sourceforge.net/projects/gbdk

If using Mac OS X, a patch should be applied.

    $ patch -p0 < macosx.patch

Before building, execute the following from the root folder:

    mkdir -p sdcc/bin
