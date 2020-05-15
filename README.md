# ECE-470-Crabapple

In the provided video and scene, we display the complete structure of the lock-
picking robot. The robot operates through communication between the UR10 arm,
prismatic motor at the tip of the arm, and proxmity sensor at set heights on top
of each pin of the lock. When the arm moves to the desired pin positions, it
sends a signal to the prismatic motor, which starts to extend. The pin will be
pushed upwards, and when the proximity sensor detects the pin, it mean that the
pin is pushed to optimal key height. The sensor outputs a signal to the arm, the
prismatic motor, and the lock. The lock slightly rotates (5 degrees), signalling
the lock loosening. The prismatic motor stops its extension and returns to the 
zero position. The arm then moves to the next pin position and repeats its picking
operation.