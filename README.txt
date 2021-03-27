This is a morse telegraph keyer inspired by Anthony Good K3NG's work on the Arduino.

Basically, I decided that the Arduino is too limited a platform to make for a good user experience.  Yes, you can do quite a bit with an LCD and buttons, but I wanted to take it to the next level, and that meant a more advanced system.

So, I've devised a system of two parts, an arduino-based "dongle" that actually keys the radios and reads the paddles, and a host computer running an application that handles all of the user interface, advanced configuration, memories, and so forth.  These two parts communicate using a text-based protocol that is both simple and extensible.
