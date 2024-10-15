#### Main Cabinet Screen

This screen displays the temperature of the main cabinet of the MCS, TMA-AZ-CS-CBT-0001, and allows its control.

![](../Resources/media/image78.png)

*Figure 2‑62. Main cabinet screen.*

<table class="table">
<colgroup>
<col style="width: 13<col style="width: 86</colgroup>
<thead>
<tr class="header">
<th><p>ITEM</p></th>
<th><p>DESCRIPTION</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1</p></td>
<td><p>Displays the status, external temperature (in ºC), internal temperature 1 (in ºC), internal temperature 2
(in ºC) and the setpoint (in ºC) of the main cabinet.</p>
<p>This screen can have two different fault statuses:</p>
<ul>
<li><p>“RMCFAULTY”: This means that the temperature controller is not communicating correctly, but the system can
continue to operate.</p></li>
<li><p>“SPECIAL FAULT”: The cabinet temperature is out of range and the entire MCS will be shut down.</p>
<p>Displays whether the doors are open or closed. Lit up in green “open” if they are open,
or “close” if they are closed. If the doors are open, the system does not control the
temperature.</p></li>
</ul>
<p>Displays a graph with the temperatures in real time.</p>
<p>Softkey “FREEZE GRAPH”: Freezes the graph.</p>
<p>Softkey “UPDATE GRAPH”: <p>Updates the graph, after it has been frozen.</p>
<p>The blue softkey navigates between the active interlocks, if there is more than one.</p>
<p>When an interlock is active, the top box is displayed in red. If no interlocks are active, the
box will be green and the blue softkey cannot be pressed.</p></td>
</tr>
<tr class="even">
<td><p>2</p></td>
<td><p>Softkey “RESET ALARM”: Resets the controller alarms or resets the interlock if
there is one.</p>
<p>Softkey “TRACK SETPOINT”: Enables manual temperature control using the value entered in
the control “setpoint”.</p>
<p>Softkey “TRACK AMBIENT”: Allows the temperature controller to track the ambient temperature.</p></td>
</tr>
</tbody>
</table>
