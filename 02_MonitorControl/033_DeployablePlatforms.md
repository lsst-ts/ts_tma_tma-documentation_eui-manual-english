#### Deployable Platforms Screen

##### Deployable Platforms Screen -- Main View

This screen displays the deployable platforms and enables their control.

![General View](../Resources/media/image81.png)

*Figure 2‑65. Deployable platforms screen - main view.*

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
<td><p>Displays the status, the section 1 position (in mm) and the section 2 position (in mm) of each
platform.</p>
<p>The box next to “run/alarm” lights up in the colour corresponding to the status of each platform.</p>
<p>The green “retract” LEDs light up when the sections of the corresponding
platforms are retracted.</p>
<p>The green “extend” LEDs light up when the sections of the corresponding
platforms are extended.</p>
<p>The green “locked” LEDs light up when the corresponding extensions are
locked.</p>
<p>The green “inserted” LEDs light up when the corresponding extensions are
inserted.</p></td>
</tr>
<tr class="even">
<td><p>2</p></td>
<td><p>Softkey “BOTH”: Selects both platforms.</p>
<p>Softkeys “X-” and “X+”: Selects the corresponding platform.</p></td>
</tr>
<tr class="odd">
<td><p>3</p></td>
<td><p>Softkey “ON”: Only turns on the system if no interlocks are active.</p>
<p>Softkey “OFF”: Turns off the system.</p>
<p>Softkey “RESET ALARM”: Resets the system from its current alarm state or resets the
interlock if one exists.</p>
<p>Softkey “EXTEND”: Extends the previously selected platform.</p>
<p>Softkey “RETRACT”: Retracts the previously selected platform.</p>
<p>Softkey “STOP”: Stops the movement.</p></td>
</tr>
<tr class="even">
<td><p>4</p></td>
<td><p>Softkeys “+” or “-”: Makes a movement at a constant speed in a positive or negative direction
respectively. This sets the percentage of the default speed defined in the settings with the
vertical slider.</p></td>
</tr>
<tr class="odd">
<td><p>5</p></td>
<td><p>Softkeys “UNLOCK M2” and “UNLOCK M1M3”: Unlocks the extensions <strong>lateral locks</strong>strong> of the corresponding platforms. </br>
  M1M3 side extensions can only be extended if the “Mirror Cover” is retracted.</p>
  
<p>Softkeys “LOCK M2” and “LOCK M1M3”: Lock the extensions of the corresponding platforms.</p>
<table class="table">
<tbody>
<tr class="odd">
<td>ℹ️</td>
<td><p> Lateral locks (M2 and M1M3) are unlocked when the extensions are going to be extended. The extension itself is carried out and locked manually from the platform. Extensions are also retracted manually and lateral locks are locked once they are fully retracted.</p></td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><p>6</p></td>
<td><p>Accesses the screen <a href="./004_LockingPins.md">Locking Pins General View</a> </p>
<p>Displays the status of the locking pins and turns on the LED with the corresponding colour:</p>
<ul>
<li><p>“FREE”: Means that the locking pins are free and lights up in green.</p></li>
<li><p>“TEST”: Means that the pins are being tested, and lights up orange.</p></li>
<li><p>“LOCK”: Means that the pins are locked, and lights up red.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>7</p></td>
<td><p>Displays the status and position (in deg) of “Elevation”.</p>
<p>Accesses the screen <a href="./002_ElevationGeneralView.md">Elevation General View</a> </p></td>
</tr>
<tr class="even">
<td><p>8</p></td>
<td><p>The blue softkey navigates between the active interlocks, if there is more than one.</p>
<p>When an interlock is active, the top box is displayed in red. If no interlocks are active, the
box will be green and the blue softkey cannot be pressed.</p></td>
</tr>
</tbody>
</table>

##### Deployable Platforms Screen -- Current Move

This screen shows a graph of the movement of the deployable platforms in real time.

![Deployable platform current move](../Resources/media/image82.png)

*Figure 2‑66. Deployable platforms screen - current view.*

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
<td><p>Displays a graph of the movement of the deployable platforms in real time.</p>
<p>Softkey “FREEZE GRAPH”: Freezes the graph.</p>
<p>Softkey “UPDATE GRAPH”: Allows the graph to be updated after being frozen.</p></td>
</tr>
</tbody>
</table>

##### Deployable Platforms Screen -- Move History

This screen displays and loads the last five movements of the deployable platforms, with number 1 being the last.

![Move history](../Resources/media/image83.png)

*Figure 2‑67. Deployable platforms screen - move history.*

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

## Deploying the deployable platforms

There are two platforms: X- and X+, each have two sections and two extensions.
X+ grants access for camera work.

**Each section** extends independently. See figure 2-2 in the [Deployable platform technical specification](https://docushare.lsstcorp.org/docushare/dsweb/Get/Document-45404/092-308-I-M-00010-Ed001.pdf) document.

- Platform section 1: the lower section, which supports section 2 during extension and retraction.

- Platform section 2: the upper section of the platform.

The **deploy sequence** is:

- Extend platform section 1
- Extend platform section 2

The **retract sequence** is:

- Retract platform section 2
- Retract platform section 1

### Precondition to deploy DP

- TMA parked (drives off) and Elevation Locking pin inserted.

### Procedure

To deploy the Deployable Platforms (DP):

1. Go to Home > Monitor and Control > [Deployable Platform](./033_DeployablePlatforms.md)
2. Select `BOTH` or one of the platforms sections (`X-` or `X+`).
3. <code>RESET ALARM</code> if needed
4. Power `ON`
5. Press `EXTEND`
6. Power `OFF`, once they are fully deployed

## Retracting the deployable platforms

### Precondition to retract DP

- TMA parked (drives off) and Elevation Locking pin inserted.
- All extensions locking pins **inserted** and **locked**.

### Procedure

To retract the Deployable Platforms (DP):

1. Go to Home > Monitor and Control > [Deployable Platform](./033_DeployablePlatforms.md)
2. Select `BOTH` or one of the platforms sections (X- or X+).
3. `RESET ALARM` if needed
4. Power `ON`
5. Press `RETRACT`
6. Power `OFF`, once they are fully retracted.

## Deployable Platform extensions management

### Preconditions to manage the DP extensions

- Platform completely deployed and powered OFF (idle state).
- For the M1M3 DP extensions, the Mirror covers should be retracted (mirror exposed).

### Procedure

#### Extending the extensions

1. From Home > Monitor and Control > [Deployable Platform](./033_DeployablePlatforms.md)
    1. Select `BOTH` or one of the platforms sections (`X-` , `X+` ).
    2. **Unlock** the extension you want to extend
        1. Unlock M2 extensions: Press `UNLOCK M2`
        2. Unlock M1M3 extensions: Press `UNLOCK M1M3`
Once unlocked the corresponding **locked** LED will be gray

2. From the deployable platforms on **level 8**:
    1. **Manually remove the pin** on the extension to operate. You’ll see in the TMA EUI the **inserted** led will be gray
    2. Manually extend the extensions.

#### Retracting the extensions

1. From the deployable platforms on **level 8**:
     1. Manually retract the extensions
     2. Manually insert the pin in the extension to operate. You’ll see in the TMA EUI the **inserted** led will be green.  
2. From Home > Monitor and Control > [Deployable Platform](./033_DeployablePlatforms.md)
    1. Select `BOTH` or one of the platforms sections (`X-` or `X+`).
    2. Lock the extension you want
         1. Lock M2 extensions: Press `LOCK M2`
         2. Lock M1M3 extensions: Press `LOCK M1M3`
         3. Once locked the corresponding LED will be green.
