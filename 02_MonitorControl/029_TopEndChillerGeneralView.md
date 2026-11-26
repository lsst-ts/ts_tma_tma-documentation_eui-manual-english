#### Top End Chiller General View Screen

This screen displays the status and allows the control of the Top End Chiller system.

![Alt text](../Resources/media/image_TEC.png)

*Figure 2‑63. Top End Chiller screen.*

<table class="table">
  <colgroup>
    <col style="width: 13<col style="width: 86
  </colgroup>
<thead>
<tr class="header">
      <th><p>ITEM</p></th>
      <th><p>DESCRIPTION</p></th>
    </tr>
  </thead>
  <tbody>
    <tr class="odd">
      <td><p>1</p></td>
      <td>
        <p>
          Displays the status of the “Top End Chiller (TEC)” and lights up the
          upper box in the corresponding color.
        </p>
        <p>
          It shows, in green, whether the “Top End Chiller (TEC)” is in manual
          or automatic mode.
        </p>
        <p>
          If shows, in green, whether control is local or remote. This change
          requires the local system to get the command, that's why during this
          transition both remote and local LEDs are off, this is because the
          system is waiting for the local to take the control. It will light
          green once the local gets it.
        </p>
        <p>
          Displays the values of the general “Top End Chiller (TEC)” elements
          and lights up the elements in the corresponding color as they are
          activated:
        </p>
        <ul>
          <li>
            <p>Grey: If the element is not active.</p>
          </li>
          <li>
            <p>Green: If the element is active.</p>
          </li>
          <li>
            <p>Red: If the element is faulty.</p>
          </li>
        </ul>
      </td>
    </tr>
    <tr class="even">
      <td><p>2</p></td>
      <td>
        <p>
          The following softkeys can only be used when the system is in
          automatic and remote mode.
        </p>
        <p>
          Softkey “ON”: Only switches on the “Top End Chiller (TEC)” if it is
          in “Idle”, in “REMOTE+AUTO” and if there is no active interlock.
        </p>
        <p>
          Softkey “OFF”: Switches off the “Top End Chiller (TEC)”, while in
          “REMOTE+AUTO”.
        </p>
        <p>
          Softkey “RESET ALARM”: Resets the system from its current alarm state
          or resets the interlock if one exists.
        </p>
      </td>
    </tr>
    <tr class="odd">
      <td><p>3</p></td>
      <td>
        <p>
          Softkey “ON”: Sets the “Top End Chiller (TEC)” to work in remote mode.
        </p>
        <p>
          Softkey “OFF”: Sets the “Top End Chiller (TEC)” to work in local mode. This will wait for the local to take
          the control.
        </p>
      </td>
    </tr>
    <tr class="even">
      <td><p>4</p></td>
      <td>
        <p>
          Softkey “MANUAL”: Sets the “Top End Chiller (TEC)” to work in manual mode.
        </p>
        <p>
          Softkey “AUTO”: Sets the “Top End Chiller (TEC)” to work in auto mode.
        </p>
      </td>
    </tr>
    <tr class="odd">
      <td><p>5</p></td>
      <td>
        <p>
          The following softkeys can only be used when the system is in manual
          and remote mode.
        </p>
        <p>Softkey “CAMERA ON”: Turns on the fans for the camera.</p>
        <p>Softkey “CAMERA OFF”: Turns off the fans for the camera.</p>
        <p>Softkey M2 ON”: Turns on the fans for the M2.</p>
        <p>Softkey M2 OFF”: Turns off the fans for the M2.</p>
      </td>
    </tr>
    <tr class="even">
      <td><p>6</p></td>
      <td>
        <p>
          The following softkeys can only be used when the system is in manual
          and remote mode.
        </p>
        <p>Softkey “OPEN”: Opens the compressed air valve 0501</p>
        <p>Softkey “CLOSE”: Closes the compressed air valve 0501</p>
      </td>
    </tr>
    <tr class="odd">
      <td><p>7</p></td>
      <td>
        <p>
          The following softkeys can only be used when the system is in manual
          and remote mode.
        </p>
        <p>Softkey “hx1. ON”: Turns on the heat exchanger 1.</p>
        <p>Softkey “hx1. OFF”: Turns off the heat exchanger 1.</p>
        <p>Softkey “hx2. ON”: Turns on the heat exchanger 1.</p>
        <p>Softkey “hx2. OFF”: Turns off the heat exchanger 1.</p>
      </td>
    </tr>
  </tbody>
</table>

##### Icons

The table below shows the main icons present in the TEC.

| icon| name|
|----------|----------|
| ![fan](../Resources/media/image39.png)| Fan |
| ![valve](../Resources/media/image40.png) ![valve](../Resources/media/image41.png)| Valve|
| ![tempMeter](../Resources/media/TEC_tempMeter.png)| Temperature sensor |
| ![humiditySensor](../Resources/media/TEC_humiditySensor.png)| Humidity sensor |
