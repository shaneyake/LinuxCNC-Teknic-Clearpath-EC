# LinuxCNC-Teknic-Clearpath-EC
LinuxCNC configuration for Teknic Clearpath-EC motors

Currently I am testing the motors and do not have a CNC machine built.
<br>
CPM-ECHP-3441H-ELSB for X and Y<br>
CPM-ECSK-3411H-RLNB with Gearbox for Z<br>
<br>
Ethercat:<br>
Motor 0 is X axis<br>
Motor 1 is Y axis<br>
Motor 2 is Z axis<br>

<p>
  <h3>Things to change for your machine:</h3>
  Pleae change the VELOCITY's in the minimal_xyz.ini to match your machine, mine are crazy.<br>
  Please set Max Travel limits<br>
  Please set your homing, (Currently Disabled)<br>
</p>

<p>
  <h3>Things TODO:</h3>
  Distributed Clock Sync (DC-Sync) is not working<br>
  More to come to the list<br>
</p>
