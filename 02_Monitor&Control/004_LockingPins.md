#### Locking Pins Screen

##### Locking Pins Screen -- Main View

This screen displays the elevation axis locking pins and enables their control.

![Locking pins screen - main view](../Resources/media/image27.png)

*Figure 2‑20. Locking pins screen - main view.*

<table class="table">
<thead>
<tr class="header">
<th><p>ITEM</p></th>
<th><p>DESCRIPTION</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1</p></td>
<td><p>Displays the status of the locking pins:</p>
<ul>
<li><p>“Free”, in green. Movement of the elevation is permitted in this position.</p></li>
<li><p>“Test”, in orange. Fine balancing of the elevation is performed in this position.</p></li>
</ul>
<table class="table">
<tbody>
<tr class="odd">
<td>⚠️</td>
<td><p>This position (test) poses a risk to the telescope, as the permitted movements are less than 0.2 deg.</p></td>
</tr>
</tbody>
</table>
<ul>
<li><p>“Lock”, in red, does not allow the elevation movement.</p></li>
</ul>
<p>Displays the status and position (in mm) of the locking pins. In addition, the box next to “run/alarm”
lights up in the color corresponding to the status of the pin.</p></td>
</tr>
<tr class="even">
<td><p>2</p></td>
<td><p>Softkey “ON”: Only turns on the pin if it is in “Idle” and no interlock is active.</p>
<p>Softkey “OFF”: Turns off the pin.</p>
<p>Softkey “RESET ALARM”: Resets the system from its current alarm state or resets the
interlock if one exists.</p></td>
</tr>
<tr class="odd">
<td><p>3</p></td>
<td><p>Softkey “BOTH”: Selects both pins.</p>
<p>Softkey “X-”: Selects the pin located in the “X-” bracket.</p>
<p>Softkey “X+”: Selects the pin located in the “X+” bracket.</p>
<p>Softkey “FREE”: Moves the previously selected pin to the released position.</p>
<p>Softkey “TEST”: Moves the previously selected pin to the test position.</p>
<p>Softkey “LOCK”: Moves the previously selected pin to the lock position.</p>
<p>Softkey “STOP”: Stops the movement of the previously selected pin.</p>
<p>Softkeys “+” or “-”: Makes a movement at a constant speed in a positive or negative direction
respectively. This sets the percentage of the default speed defined in the settings with the
vertical slider.</p></td>
</tr>
<tr class="even">
<td><p>4</p></td>
<td><p>Displays the status and allows access to the screen [“Balancing General View”](./024_BalancingGeneralView.md)</p></td>
</tr>
<tr class="odd">
<td><p>5</p></td>
<td><p>Displays the status and position (in deg) of “Elevation”.</p>
<p>Accesses the screen <a href="./002_ElevationGeneralView.html">Elevation General View</a></p></td>
</tr>
<tr class="even">
<td><p>6</p></td>
<td><p>The blue softkey navigates between the active interlocks, if there is more than one.</p>
<p>When an interlock is active, the top box is displayed in red. If no interlocks are active, the
box will be green and the blue softkey cannot be pressed.</p></td>
</tr>
</tbody>
</table>

###### Locking Pins move sequence

The locking pins have 3 positions:

- **Free**: the locking pins are completely retracted, allowing a complete and free movement of the Elevation axis.
- **Lock**: the locking pins are completely inserted, restricting the Elevation axis movement. This restriction is both
  mechanical and electrical, as the signal from the limit switch is wired to the TMA IS disabling the Elevation axis.
- **Test**: the locking pins are at an intermediate position, at this position the elevation axis has a few degrees
  of free motion before hitting the locking pins. This position in meant just for balancing purposes, to limit the
  motion range allowed for elevation during the process.

As there are just 3 possible positions for the locking pins, for motion there are just 3 buttons named accordingly, to
move the pins to the corresponding positions. The position in mm for each pin is stored as a setting and can be adjusted
by an maintenance user in the EUI settings.

Additionally, maintenance users may see the jog buttons for adjusting these positions, other users will just see the
*FREE*, *TEST* and *LOCK* buttons for moving the pins.

##### Locking Pins Screen -- Current Move

This screen shows a graph of the movement of the locking pins in real time.

![Locking pins screen - current move](../Resources/media/image28.png)

*Figure 2‑21. Locking pins screen - current move.*

<table class="table">
<thead>
<tr class="header">
<th><p>ITEM</p></th>
<th><p>DESCRIPTION</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1</p></td>
<td><p>Displays a graph of the movement of the locking pins in real time.</p>
<p>Softkey “FREEZE GRAPH”: Freezes the graph.</p>
<p>Softkey “UPDATE GRAPH”: Allows the graph to be updated after being frozen.</p></td>
</tr>
</tbody>
</table>

##### Locking Pins Screen -- Move History

This screen displays and loads the last five movements of the locking pins, with number 1 being the last.

![Locking pins screen - move history](../Resources/media/image29.png)

*Figure 2‑22. Locking pins screen - move history.*

<table class="table">
<thead>
<tr class="header">
<th><p>ITEM</p></th>
<th><p>DESCRIPTION</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1</p></td>
<td><p>Softkey “LOAD”: Loads the last five movements.</p>
<p>Once the desired movement has been selected, it allows it to be displayed on the graph.</p></td>
</tr>
</tbody>
</table>
