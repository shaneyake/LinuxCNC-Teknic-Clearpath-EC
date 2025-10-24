# LinuxCNC-Teknic-Clearpath-EC
LinuxCNC configuration for Teknic Clearpath-EC motors<br>
I am using the LinuxCNC 2.9.4<br>
rpi-4-debian-bookworm-6.12.11-arm64-ext4-2025-01-27-0404.img.xz as the base for my setup.<br>

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
