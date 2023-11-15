# liblxi-vala
Vala bindings for liblxi

## Requirements
Make sure you have liblxi (and the corresponding developement pacakge) installed.

## Installation
To use the vala bindings, include the liblxi.vapi file in your project.
See `meson.build` for an example how to do it using meson.

## Running the test examples
In order to build the examples, two more dependencies are required `glib` and `libtirpc`.
Next it should be possible to build and run the test executable (`builddir/liblxi_test`).

_Note:_ It may be required to change the settings (ip, port, command, etc.) to get it to work. 
_Note:_ mDNS functionality has not been tested.