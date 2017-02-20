# racetree
Arduino software + related backing racetree and remote control unit.

/SpaceTreeRemoteControl files are for the remote control unit that talks to the race tree via a 2.4Ghz radio.

/SpaceTreeSignalBoard files are forthe control unit that drives the pinewood race tree / space derby signal board.

Note dirs and filenames are named 'Space Tree' vs. 'Race Tree' because I started this project for use in my pack's space derby event and hadn't originally intended to use this for the pinewood derbies.  Likewise, the race tree controller is referred to as the 'Space Tree Signal Board'.  Despite the names, this project is 100% derby agnostic.  I use the same remote control unit and same race tree controller (signal board) for our space and pinewood derbies.  The race tree controller is the arduino+radio+sd+audio part that the actual race tree plugs into.  The tree itself is just a series of 5v RGB LEDs wired in series, set via signal to the control line.  I originally created a space-themed race tree for for our space derbies.  This unit is a box with horizontal bars that light up, hence the term "signal board".  I had a bunch of left over LEDs, so I made a second unit to look like a traditional race tree for our pinewood derbies, made largely out of my old erector set parts and cinnamon roll icing cups.  That is the race tree I included in my [Race Tree Instructable](http://www.instructables.com/id/Radio-Controlled-Race-Tree/ "Race Tree Instructable")  Both trees are identical in wiring, only differ in appearance.  Simply plug either device into the controller.

The remote unit has a three-position switch to change from three banks of space derby sounds to three banks of pinewood derby sounds.  The scouts love to switch between both sets regardless of event type (space or pinewood).  The third position is for a not-yet-implemented self destruct feature :-)
