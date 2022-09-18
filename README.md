menuconfig
===========

This is a standalone version of the mconf tool from the linux kernel.

Licence
=======
The code is distributed under the GPLv2.0.





building
==========

    mkdir build
    cd build
    cmake ..
    make

setup enviroment
==========
KCONFIG_CONFIG                      Specify configuration file name
KCONFIG_OVERWRITECONFIG             enable/disable overwrite config file   default:disable

testing
==========

    cd build
    ./mconf ../test/rootconf




