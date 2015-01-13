clump-examples
==============

The [clump](https://github.com/castedo/clump) project itself has an example
clump.yaml file. This repository has additional examples in use.

Example varbjars
----------------

[varbjars/](varbjars/) is an example of a simple clump packaging of two Java
jar files.

Notable clump features exhibited:
* urls to remote single source files which get automatically tarball'ed for
  Debian
* embedded inline install cmake code with variable use


Example ibgateway
-----------------

[ibgateway/](ibgateway/) is an example of a clump packaging where a 3rd party
jar file is uncompressed providing two jar files which then get packaged. In
addition from /var/ directories are created for working space for the packaged
3rd party application.

Notable clump features exhibited:
* setting of user and group ownership for installed directory and contents
* embedded inline cmake install code extracting a source jar and installing its
  contents

Example boost
-------------
[boost/](boost/) is an example packaging static libraries and header files for
certain boost libraries in C++11.
