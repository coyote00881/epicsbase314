# epicsbase314

EPICS 3.14.12.6 listo para compilación cruzada para raspberry pi3
Archivos modificados:

1.- base-3.14.12.6/configure/CONFIG_SITE
CROSS_COMPILER_TARGET_ARCHS=linux-arm
CROSS_COMPILER_HOST_ARCHS=linux-x86
SHARED_LIBRARIES=NO
STATIC_BUILD=YES

2.- base-3.14.12.6/configure/os/CONFIG_SITE.linux-x86.linux-arm
GNU_DIR = ~/Documents/buildroot-2016.11/output/host/usr
GNU_TARGET = arm-buildroot-linux-gnueabihf
