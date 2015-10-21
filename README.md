# HPE Helion Stackato scaling demo

## Purpose

Displays IP and PID of the current instance of the app, useful for demonstrating multiple running instances.

## Usage

### via HPE Helion Stackato

    $ stackato push -n

Then open http://scaling.stackato.local in a browser.

### Without HPE Helion Stackato

It is possible to run the app without HPE Helion Stackato, if necessary.

  1. carton install
  2. carton exec perl app.pl daemon

Then open http://127.0.0.1:3000/ in a browser.


