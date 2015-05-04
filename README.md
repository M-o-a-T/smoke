# Fire Detector

## Gira

The "Gira" board is intended to plug into a "Gira Dual" smoke detector.
This device (30€) has a thermometer as well as a smoke chamber, a
serial interface that's actually useful, and the ability to run on 12V
external as well as 9V battery power.

It runs on 3.3V; the 1wire bus (5V) is connected via a level shifter.

Code will be in https://github.com/M-o-a-T/owslave

## Funk

The "Funk" board is a small (and currently untested) board that connects
a cheap smoke detector to RF. There's no code for it.

## Programming

The programming interface is a standard 6-pin plug, except that it's
used via a 3x2 pogo plug. If you need to attach a 6-pin header, soldering
that to the top of the pads is fairly easy. You should add some
two-component glue after soldering so that you won't pull the pads off when
you unplug.

