# Official Moog Moog Werkstatt-Ø1 Arduino libraries

Moog Music's official Arduino libraries (both v1 and v2) for the Moog Werkstatt-Ø1. 
Uploaded for archival reasons. 
Archived from https://archive.org/details/moog_werkstatt

## Original Moog Readme (as of v2, converted to Markdown with fixed links):

This is a library for the Moog Werkstatt-01
  ----> [http://www.moogmusic.com/products/werkstatt/werkstatt-01-moogfest-2014-kit](https://web.archive.org/web/20141219103658/http://www.moogmusic.com/products/werkstatt/werkstatt-01-moogfest-2014-kit)

Written by Chris David Howe for Moog Music Inc. 

MIT license, all text above must be included in any redistribution

Download and rename the uncompressed folder moog_werkstatt. Check that the moog_werkstatt folder contains werkstatt.cpp and werkstatt.h.

Place the moog_werkstatt library folder your <arduinosketchfolder>/libraries/ folder. You may need to create the libraries subfolder if its your first library. Restart the IDE.

This library is currently under development now in version 1.0 

### CLASSES/FUNCTIONS

* interface name(int input pin)
    * interface.toggle(int maximum)
    * interface.momentary(int minimum, int maximum)
    * interface.potentiometer(int minimum, int maximum)

* arpeggiator name(int output PWM pin)
    * arpeggiator.play(int BPM, int notes[], int note_values[])

* lfo name(int output PWM pin, int input analog pin)
    * lfo.rate(notes[], note_values[])

* noise name(int output digital pin)
    * noise.generate(int noise color) 


