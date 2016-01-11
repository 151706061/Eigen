MIRTK ThirdParty/Eigen
======================

This Git submodule repository contains the Eigen header files required to build
the MIRTK Numerics module. The files were copied from the [Eigen 3.2.7 source
distribution package](http://bitbucket.org/eigen/eigen/get/3.2.7.tar.gz).

These files can be used instead of an available system Eigen installation
after initializing the corresponding MIRTK Git submodule. When the
submodule is not initialized, a separate Eigen installation is required.

```bash
cd $MIRTK_SOURCE_DIR
git submodule update --init -- ThirdParty/Eigen
```

License
-------

The Eigen files are redistributed under the terms of the Mozilla Public License v. 2.0.
See [COPYING.MPL2](COPYING.MPL2) file.

Some of the included third-party files are covered by the BSD license.
See [COPYING.BSD](COYPING.BSD) file.
