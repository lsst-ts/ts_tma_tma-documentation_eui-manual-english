#### Main Axis General View Screen

##### Main Axis General View Screen -- Current Move

This screen allows the azimuth and elevation axes to be commanded at the same time.

> ℹ️ The screen does not allow new operations until both axes complete the previously requested operation.

![Main axis general view screen - current move](../Resources/media/image019.png)

*Figure 2‑12. Main axis general view screen - current move.*

<table>
<colgroup>
<col style="width: 13%" />
<col style="width: 86%" />
</colgroup>
<thead>
<tr class="header">
<th>ITEM</th>
<th>DESCRIPTION</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>1</td>
<td><p>Accesses the screen <a href="./002_ElevationGeneralView.md">Elevation General View</a></p>
<p>Displays the “Elevation” status, position (in deg) and the setpoint (in deg).</p>
<p>Displays the status of each motor by coloured boxes:</p>
<ul>
<li><p>Red: Means that the axis has a fault.</p></li>
<li><p>Green: Means that the axis is on.</p></li>
<li><p>Grey: Means that the axis is not on.</p></li>
</ul>
<p>The orange triangle with the text "not homed" means that the axis reference has not been made.</p></td>
</tr>
<tr class="even">
<td>2</td>
<td><p>Accesses the screen <a href="./005_AzimuthGeneralView.md">Azimuth General View</a></p>
<p>Displays the “Azimuth” status, position (in deg) and setpoint (in deg).</p>
<p>Displays the status of each motor by coloured boxes:</p>
<ul>
<li><p>Red: Means that the axis has a fault.</p></li>
<li><p>Green: Means that the axis is on.</p></li>
<li><p>Grey: Means that the axis is not on.</p></li>
</ul>
<p>The orange triangle with the text "not homed" means that the axis reference has not been made.</p></td>
</tr>
<tr class="odd">
<td>3</td>
<td><p>Softkey “ON”: Switches on both axes, provided that they are in “Idle” and no interlock is
active. The active interlocks are shown in item 12 of this same table.</p>
<p>Softkey “OFF”: Turns off both axes.</p>
<p>Softkey “RESET ALARM”: Resets the alarm status for both axes or resets the interlocks if there are
any.</p></td>
</tr>
<tr class="even">
<td>4</td>
<td><p>Softkey “HOME”: Runs a search for the axis reference.</p>
<p>Softkey “STOP”: Stops the movement of the axes. This options is permitted provided that a movement
is being executed, without having to wait for it to finish. This is the only operation that is permitted when there movement
operation in progress.</p></td>
</tr>
<tr class="odd">
<td>5</td>
<td><p>Displays the azimuth and elevation graph is real time.</p>
<p>Softkey “FREEZE GRAPH”: Freezes the graph.</p>
<p>Softkey “UPDATE GRAPH”: Allows the graph to be updated after being frozen.</p></td>
</tr>
<tr class="even">
<td>6</td>
<td><p>Defines the position (in deg), speed (in deg/s), acceleration (in
deg/s<sup>2</sup>) and jerk (in deg/s<sup>3</sup>) specifications for elevation or azimuth, to make a movement.</p>
<p>Softkey “MOVE”: Used to move the axes according to the previously entered specifications.</p>
<p>Softkey “STOP”: Stop the movement of the axes.</p></td>
</tr>
<tr class="odd">
<td>7</td>
<td><p>Softkey “LOAD”: accesses the fixed trajectory files selection window, [see](#tracking-screen).</p>
<p>Softkey “EXECUTE”: When selected, executes a file.</p>
<p>Softkey “STOP”: Stop the movement of the axes.</p></td>
</tr>
<tr class="even">
<td>8</td>
<td><p>Accesses the screen <a href="./004_LockingPins.md">Locking Pins General View</a></p>
<p>Displays the status of the locking pins and turns on the LED with the corresponding colour:</p>
<ul>
<li><p>“FREE”: Means that the locking pins are free and lights up in green.</p></li>
<li><p>“TEST”: Means that the pins are being tested, and lights up orange.</p></li>
<li><p>“LOCK”: Means that the pins are locked, and lights up red.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td>9</td>
<td>Displays the status and accesses the screen <a href="./008_OSSGeneralView.md">OSS General View</a></td>
</tr>
<tr class="even">
<td>10</td>
<td>Displays the status and accesses the screen <a href="./018_PowerSupply.md">Power Supply General View</a></td>
</tr>
<tr class="odd">
<td>11</td>
<td><p>Accesses the screen <a href="./006_AzimuthCableWrap.md">Azimuth Cable Wrap</a></p>
<p>Displays the status and position (in deg) of the “Azimuth Cable Wrap (ACW)”.</p></td>
</tr>
<tr class="even">
<td>12</td>
<td><p>The blue softkey navigates between the active interlocks, if there is more than one.</p>
<p>When an interlock is active, the top box is displayed in red. If no interlocks are active, the
box will be green and the blue softkey cannot be pressed.</p></td>
</tr>
</tbody>
</table>

##### Main Axis General View Screen -- Current Move XY

This screen allows the azimuth and elevation axes to be commanded at the same time, represented on the X and Y axes.

![Main axis general view screen - current move XY](../Resources/media/image20.png)

*Figure 2‑13. Main axis general view screen - current move XY.*

<table>
<colgroup>
<col style="width: 13%" />
<col style="width: 86%" />
</colgroup>
<thead>
<tr class="header">
<th>ITEM</th>
<th>DESCRIPTION</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>1</td>
<td><p>Shows the azimuth and elevation graph, representing the X and Y axes in real time.</p>
<p>Softkey “FREEZE GRAPH”: Freezes the graph.</p>
<p>Softkey “UPDATE GRAPH”: Allows the graph to be updated after being frozen.</p></td>
</tr>
</tbody>
</table>

##### Main Axis General View Screen -- Move History

This screen displays and loads the last five azimuth and elevation movements, with number 1 being the last.

![Main axis general view screen - move history](../Resources/media/image21.png)

*Figure 2‑14. Main axis general view screen - move history.*

<table>
<colgroup>
<col style="width: 13%" />
<col style="width: 86%" />
</colgroup>
<thead>
<tr class="header">
<th>ITEM</th>
<th>DESCRIPTION</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>1</td>
<td><p>Softkey “LOAD”: Loads the last five movements.</p>
<p>Once the desired movement has been selected, it allows it to be displayed on the graph.</p></td>
</tr>
</tbody>
</table>

###### Tracking Screen

This screen is displayed as a “Popup” by clicking on the "LOAD" button on the "Main Axis General View" screen, allowing a file with a fixed path to be selected. This selected path will be executed by pressing the "EXECUTE" button of the "Main Axis General View” screen.

![Tracking screen](../Resources/media/image22.png)

*Figure 2‑15. Tracking screen.*

<table>
<colgroup>
<col style="width: 13%" />
<col style="width: 86%" />
</colgroup>
<thead>
<tr class="header">
<th>ITEM</th>
<th>DESCRIPTION</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>1</td>
<td>Selects the directory of the paths to be loaded.</td>
</tr>
<tr class="even">
<td>2</td>
<td>Displays and allows the selection of the filename to be plotted in item 3 of this table.</td>
</tr>
<tr class="odd">
<td>3</td>
<td>Displays the graph of the selected file.</td>
</tr>
<tr class="even">
<td>4</td>
<td><p>Softkey “LOAD”: Loads the previously selected file.</p>
<p>Softkey “CANCEL”: Cancels the action and returns to the previous screen.</p></td>
</tr>
</tbody>
</table>
