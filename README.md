
A simple FM receiver
-------------------

![fm receiver](/fmreceiver.png?raw=true)

-------------------------------------------------------------------------

In spite of the foreseen move from analog to digital radio, there
are still lots of FM stations in the FM broadcast band.

The FM receiver software is an experimental receiver, with quite some settings.
A simpler version, just to listen to radio, is in the WFM-RPI repository.


The program shows 2 spectra, one is the spectrum of the incoming signal,
the other is the spectrum of the decoded signal.


-------------------------------------------------------------------------

The FM receiver will operate with the SDRplay, DABsticks, the AIRspy and
the HACKrf devices.

For creating an executable: install the required libraries use qmake.

Note that the software is made for Qt5 and qwt6. Unfortunately, some
linux distributions do not support qwt in cooperation with Qt5.

Note that in the current version, the keypad on the GUI disappeared,
it is replaced by a button that can be pressed to activate a separate
keypad.

Note further that this version now supports a maintained programlist,
a list maintained between invocations of the program.

Finally, I was experimenting with a scanning function, one that stops
whenever the S/N ration is above a certain level. Still lots to be done.

This version is not supported, but works pretty well.


