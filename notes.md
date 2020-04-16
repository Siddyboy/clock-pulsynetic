# Notes on Original Clock

Notes about original clock or as inherited from CJCK.

## Original Clock Details

Face is inscribed with 'EDWARD', 'GLASGOW' and 'PULSYNETIC'.

Mechanism and case are inscribed 'EG3'.

From fragments of the original label on the back of the case there is a handwritten '3R' where R is ohms, and a printed '0.22 A' crossed out and handwritten over '0.38 A'.

The hour hand is a friction push-fit. The minute hand is a tapered pin fit; I think this ensures that it is in the correct orientation relative to its drive gear which appears to be balanced.

Scribe mark in bezel is almost certainly TDC (12 O'clock) mark.

The three screws that attach the face to the case are specially filed. Metric?

## Existing retrofit electronics

Clock has been fitted with 2 off battery holders for C cells in series. When existing circuit is run the batteries are only enough to run for a few hours. A second attempt produced no response at all. Broken?

There are two push buttons:
- LH button produces instant pulse to advance clock one 'tick' (30 s i think)
- RH button doesn't appear to do anything - could be a pause button to allow 'time' to catch up?

Both buttons pull their relative connections on the main circuit board low assuming that they are push-to-make buttons.

Control circuit has one DIL IC = PIC16F84-04/P 0119H7A, a transistor 2N3053 90 08, and another transistor(?) CBC549 8.

There is some sort of crystal oscillator too.

Full circuit TBD.
