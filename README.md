JDLIB
=====

Open source build scripts and important code snippets

Some important build scripts to build open source c libs in to iOS platform specialy with arm64 support.

LIBIDN Build SCript
===================

original build script was found in xmppframework project and later i modified the script to work with iOS7 SDK and arm64 arcitecture.

IPMORTANT : all credits should go to original creator.

build-libidn.sh

this script can build iOS fat static lib for libidn, you can enable or disable architecures in line number 37, ARCHS="i386 x86_64 armv7 armv7s arm64"

this build script is working with iOS7 sdk and iPhone 5S's arm64 architecture.

OPENSSL build script
====================
Added openssl build script originally found at https://github.com/x2on/OpenSSL-for-iPhone (all credits should go to him) and removed i386 and i386_64, this library only builds for devices not for any simulators, if simulator support is compulsory use original script to build.
