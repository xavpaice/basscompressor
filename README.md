basscompressor
==============

bass guitar compressor pedal circuit
This is a schematic pulled without remorse from the excellent
work on http://tagboardeffects.blogspot.co.nz/2012/03/really-cheap-compressor.html

I've modified it minimally in order to get it linked into the
signal chain of a Jfet based preamp circuit based on 
http://www.albertkreuzer.com/preamp.htm.

The sound is OK but it distorts with anything above a modest input
and if I don't pull the gain down a bit with an additional resistor
in parallel with the LDR there's miles of fuzz.

The bass response isn't great either - still trying to work that out.

Issues; if I integrate this into the jfet preamp, I end up
losing tone stack with signal 100% wet.  Need to put in
effects loop 1 and 2 - loop 1 no tone, loop 2 post loop
1 and post tone

need to fix input impedance much lower than current
design as signal quite hot and distorting (a lot).

why is bass response so poor? (I want it for bass after all)

Maybe consider switching power to +- 15V from
jfet preamp.
