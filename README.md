# repetier-inkscape

Based on the excellent work of: https://github.com/palmerr23/repetier-inkscape

Couple of modifications:
* added enabling of laser at the start of a path
* added disabling of laser while moving between paths
* added option in idx for specifying laser port/command(on/off)
* This is used in print mode, not laser mode.  The laser is run via PWM from the extruder fan
