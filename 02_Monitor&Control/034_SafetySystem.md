#### Safety System Screen

This screen shows the safety system in table format. The rows being the causes, and the columns the sub-systems/effects. When a row is activated, the boxes corresponding to the subsystems/effects affected by that cause are coloured in. There are four different colors:

- White: No active interlock.

- Orange: An interlock is active. No operation by the operator is required. Once the cause is solved, it is released without resetting.

- Red: An interlock is active. The cause of the interlock needs to be reset by the operator once it has been resolved.

- Purple: overrides the cause for a certain amount of time (180s). The interlock reappears if the cause is not released and reset during this time.

![](../Resources/media/image84.png)

*Figure 2‑68. Safety system screen.*

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
<td><p>Displays the table of causes and subsystems.</p>
<p>Enables browsing through the interlocks.</p>
<p>Enables selection of the desired causes to be added to the item 2 list.</p></td>
</tr>
<tr class="even">
<td><p>2</p></td>
<td><p>Displays the selected causes.</p>
<p>Softkey “RESET SELECTED”: Resets the selected cause (or causes). If the cause is not active it will
reset. If it remains active it will not reset.</p>
<p>Softkey "SET OVERRIDE": override allows the established limit to be exceeded, for those settings where this is
permitted. This action lasts for a certain time (180s). If the cause is not released and reset during this time,
the interlock reappears.</p>
<p>Softkey “RELEASE OVERRIDE”: Releases the setting and it is no longer possible to exceed its limit.</p></td>
</tr>
</tbody>
</table>
