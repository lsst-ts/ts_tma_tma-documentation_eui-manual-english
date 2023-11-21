#### Settings List

##### AmbientTemperatureTracking

###### General Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| AmbientTemperatureTracking | Ambient Temperature Offset | DOUBLE | ºC | Offset to apply to the received ambient temperature |

###### Restricted Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| AmbientTemperatureTracking | Commands to update settings | DOUBLE |  | When the number of commands set in this settings is received by the task, the settings will be updated |
| AmbientTemperatureTracking | Initial Temperature | DOUBLE | ºC | The system will start with this temperature until a commands to update the ambient temperature is received |

##### Balancing

###### General Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| Balancing1 | Balance Position | DOUBLE | mm | This is the balance position for balancing weight. |
| Balancing1 | Default Speed | DOUBLE | mm/s | The default speed of the motor. |
| Balancing1 | ID String | STRING |  | This is the identifier for the cover in string format. |
| Balancing1 | Negative Software Limit Enable | BOOLEAN |  | Enable the software limit. If the value of this param is false the software limit does not work and will not trigger any alarm. Disable this only for testing or to get the system out of software limit |
| Balancing1 | Positive Software Limit Enable | BOOLEAN |  | Enable the software limit. If the value of this param is false the software limit does not work and will not trigger any alarm. Disable this only for testing or to get the system out of software limit |
| Balancing2 | Balance Position | DOUBLE | mm | This is the balance position for balancing weight. |
| Balancing2 | Default Speed | DOUBLE | mm/s | The default speed of the motor. |
| Balancing2 | ID String | STRING |  | This is the identifier for the cover in string format. |
| Balancing2 | Negative Software Limit Enable | BOOLEAN |  | Enable the software limit. If the value of this param is false the software limit does not work and will not trigger any alarm. Disable this only for testing or to get the system out of software limit |
| Balancing2 | Positive Software Limit Enable | BOOLEAN |  | Enable the software limit. If the value of this param is false the software limit does not work and will not trigger any alarm. Disable this only for testing or to get the system out of software limit |
| Balancing3 | Balance Position | DOUBLE | mm | This is the balance position for balancing weight. |
| Balancing3 | Default Speed | DOUBLE | mm/s | The default speed of the motor. |
| Balancing3 | ID String | STRING |  | This is the identifier for the cover in string format. |
| Balancing3 | Max Position Limit | DOUBLE | mm | The maximum position of the balancing motor, at which an error is fired. |
| Balancing3 | Min Position Limit | DOUBLE | mm | The minimum position of the balancing motor, at which an error is fired. |
| Balancing3 | Negative Software Limit Enable | BOOLEAN |  | Enable the software limit. If the value of this param is false the software limit does not work and will not trigger any alarm. Disable this only for testing or to get the system out of software limit |
| Balancing3 | Positive Software Limit Enable | BOOLEAN |  | Enable the software limit. If the value of this param is false the software limit does not work and will not trigger any alarm. Disable this only for testing or to get the system out of software limit |
| Balancing4 | Balance Position | DOUBLE | mm | This is the balance position for balancing weight. |
| Balancing4 | Default Speed | DOUBLE | mm/s | The default speed of the motor. |
| Balancing4 | ID String | STRING |  | This is the identifier for the cover in string format. |
| Balancing4 | Max Position Limit | DOUBLE | mm | The maximum position of the balancing motor, at which an error is fired. |
| Balancing4 | Min Position Limit | DOUBLE | mm | The minimum position of the balancing motor, at which an error is fired. |
| Balancing4 | Negative Software Limit Enable | BOOLEAN |  | Enable the software limit. If the value of this param is false the software limit does not work and will not trigger any alarm. Disable this only for testing or to get the system out of software limit |
| Balancing4 | Positive Software Limit Enable | BOOLEAN |  | Enable the software limit. If the value of this param is false the software limit does not work and will not trigger any alarm. Disable this only for testing or to get the system out of software limit |

###### Restricted Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| Balancing1 | Default Acceleration | DOUBLE | mm/s^2 | The default acceleration of the motor. |
| Balancing1 | Default Jerk | DOUBLE | mm/s^3 | The default jerk of the motor. |
| Balancing1 | First Side Position | DOUBLE | mm | This is the position to which the balancing moves first, when doing a side to side move. |
| Balancing1 | Last Side Position | DOUBLE | mm | This is the position to which the balancing moves last, when doing a side to side move. |
| Balancing1 | Max Critical Speed | DOUBLE | mm/s | The maximum critical speed of the balancing motor, at which an alarm is triggered. |
| Balancing1 | Max Position | DOUBLE | mm | Maximum allowed position, cmds with a position above this one are rejected. |
| Balancing1 | Max Position Limit | DOUBLE | mm | The maximum position of the balancing motor, at which an error is fired. |
| Balancing1 | Max Speed | DOUBLE | deg/s | The maximum speed of the motor, if the speed is greater than this the command is rejected. |
| Balancing1 | Min Position | DOUBLE | mm | Maximum allowed position, cmds with a position above this one are rejected. |
| Balancing1 | Min Position Limit | DOUBLE | mm | The minimum position of the balancing motor, at which an error is fired. |
| Balancing1 | Motor ID | DOUBLE |  | The motor ID used in this instance. |
| Balancing1 | MoveVelocity_Trns_TimeOut | DOUBLE | ms | Timeout for Move Velocity commands. Negative numbers means no timeout. |
| Balancing1 | Move_Trans_TimeMargin | DOUBLE | % | Margin to apply to calculation time for specified movement before a timeout error occurs |
| Balancing1 | OffTrans_Timeout | DOUBLE | ms | Power off transition timeout |
| Balancing1 | OnTrans_Timeout | DOUBLE | ms | Power on transition timeout |
| Balancing1 | ResettingTime | DOUBLE | ms | Timeout for the reset transition. |
| Balancing1 | SlewThreshold | DOUBLE |  | Deprecated, not in use, but kept to prevent errors. |
| Balancing1 | Speed Limit | DOUBLE | deg/s | If this speed value is overcomed a speed limit warning will be triggered. |
| Balancing1 | StopTrans_Timeout | DOUBLE | ms | Maximum time allowed for a stop command |
| Balancing1 | WaitAfterReset | DOUBLE | ms | Time to wait after a reset to go to idle |
| Balancing2 | Default Acceleration | DOUBLE | mm/s^2 | The default acceleration of the motor. |
| Balancing2 | Default Jerk | DOUBLE | mm/s^3 | The default jerk of the motor. |
| Balancing2 | First Side Position | DOUBLE | mm | This is the position to which the balancing moves first, when doing a side to side move. |
| Balancing2 | Last Side Position | DOUBLE | mm | This is the position to which the balancing moves last, when doing a side to side move. |
| Balancing2 | Max Critical Speed | DOUBLE | mm/s | The maximum critical speed of the balancing motor, at which an alarm is triggered. |
| Balancing2 | Max Position | DOUBLE | mm | Maximum allowed position, cmds with a position above this one are rejected. |
| Balancing2 | Max Position Limit | DOUBLE | mm | The maximum position of the balancing motor, at which an error is fired. |
| Balancing2 | Max Speed | DOUBLE | deg/s | The maximum speed of the motor, if the speed is greater than this the command is rejected. |
| Balancing2 | Min Position | DOUBLE | mm | Maximum allowed position, cmds with a position above this one are rejected. |
| Balancing2 | Min Position Limit | DOUBLE | mm | The minimum position of the balancing motor, at which an error is fired. |
| Balancing2 | Motor ID | DOUBLE |  | The motor ID used in this instance. |
| Balancing2 | MoveVelocity_Trns_TimeOut | DOUBLE | ms | Timeout for Move Velocity commands. Negative numbers means no timeout. |
| Balancing2 | Move_Trans_TimeMargin | DOUBLE | % | Margin to apply to calculation time for specified movement before a timeout error occurs |
| Balancing2 | OffTrans_Timeout | DOUBLE | ms | Power off transition timeout |
| Balancing2 | OnTrans_Timeout | DOUBLE | ms | Power on transition timeout |
| Balancing2 | ResettingTime | DOUBLE | ms | Timeout for the reset transition. |
| Balancing2 | SlewThreshold | DOUBLE |  | Deprecated, not in use, but kept to prevent errors. |
| Balancing2 | Speed Limit | DOUBLE | deg/s | If this speed value is overcomed a speed limit warning will be triggered. |
| Balancing2 | StopTrans_Timeout | DOUBLE | ms | Maximum time allowed for a stop command |
| Balancing2 | WaitAfterReset | DOUBLE | ms | Time to wait after a reset to go to idle |
| Balancing3 | Default Acceleration | DOUBLE | mm/s^2 | The default acceleration of the motor. |
| Balancing3 | Default Jerk | DOUBLE | mm/s^3 | The default jerk of the motor. |
| Balancing3 | First Side Position | DOUBLE | mm | This is the position to which the balancing moves first, when doing a side to side move. |
| Balancing3 | Last Side Position | DOUBLE | mm | This is the position to which the balancing moves last, when doing a side to side move. |
| Balancing3 | Max Critical Speed | DOUBLE | mm/s | The maximum critical speed of the balancing motor, at which an alarm is triggered. |
| Balancing3 | Max Position | DOUBLE | mm | Maximum allowed position, cmds with a position above this one are rejected. |
| Balancing3 | Max Speed | DOUBLE | deg/s | The maximum speed of the motor, if the speed is greater than this the command is rejected. |
| Balancing3 | Min Position | DOUBLE | mm | Maximum allowed position, cmds with a position above this one are rejected. |
| Balancing3 | Motor ID | DOUBLE |  | The motor ID used in this instance. |
| Balancing3 | MoveVelocity_Trns_TimeOut | DOUBLE | ms | Timeout for Move Velocity commands. Negative numbers means no timeout. |
| Balancing3 | Move_Trans_TimeMargin | DOUBLE | % | Margin to apply to calculation time for specified movement before a timeout error occurs |
| Balancing3 | OffTrans_Timeout | DOUBLE | ms | Power off transition timeout |
| Balancing3 | OnTrans_Timeout | DOUBLE | ms | Power on transition timeout |
| Balancing3 | ResettingTime | DOUBLE | ms | Timeout for the reset transition. |
| Balancing3 | SlewThreshold | DOUBLE |  | Deprecated, not in use, but kept to prevent errors. |
| Balancing3 | Speed Limit | DOUBLE | deg/s | If this speed value is overcomed a speed limit warning will be triggered. |
| Balancing3 | StopTrans_Timeout | DOUBLE | ms | Maximum time allowed for a stop command |
| Balancing3 | WaitAfterReset | DOUBLE | ms | Time to wait after a reset to go to idle |
| Balancing4 | Default Acceleration | DOUBLE | mm/s^2 | The default acceleration of the motor. |
| Balancing4 | Default Jerk | DOUBLE | mm/s^3 | The default jerk of the motor. |
| Balancing4 | First Side Position | DOUBLE | mm | This is the position to which the balancing moves first, when doing a side to side move. |
| Balancing4 | Last Side Position | DOUBLE | mm | This is the position to which the balancing moves last, when doing a side to side move. |
| Balancing4 | Max Critical Speed | DOUBLE | mm/s | The maximum critical speed of the balancing motor, at which an alarm is triggered. |
| Balancing4 | Max Position | DOUBLE | mm | Maximum allowed position, cmds with a position above this one are rejected. |
| Balancing4 | Max Speed | DOUBLE | deg/s | The maximum speed of the motor, if the speed is greater than this the command is rejected. |
| Balancing4 | Min Position | DOUBLE | mm | Maximum allowed position, cmds with a position above this one are rejected. |
| Balancing4 | Motor ID | DOUBLE |  | The motor ID used in this instance. |
| Balancing4 | MoveVelocity_Trns_TimeOut | DOUBLE | ms | Timeout for Move Velocity commands. Negative numbers means no timeout. |
| Balancing4 | Move_Trans_TimeMargin | DOUBLE | % | Margin to apply to calculation time for specified movement before a timeout error occurs |
| Balancing4 | OffTrans_Timeout | DOUBLE | ms | Power off transition timeout |
| Balancing4 | OnTrans_Timeout | DOUBLE | ms | Power on transition timeout |
| Balancing4 | ResettingTime | DOUBLE | ms | Timeout for the reset transition. |
| Balancing4 | SlewThreshold | DOUBLE |  | Deprecated, not in use, but kept to prevent errors. |
| Balancing4 | Speed Limit | DOUBLE | deg/s | If this speed value is overcomed a speed limit warning will be triggered. |
| Balancing4 | StopTrans_Timeout | DOUBLE | ms | Maximum time allowed for a stop command |
| Balancing4 | WaitAfterReset | DOUBLE | ms | Time to wait after a reset to go to idle |
| General | SystemSource | STRING |  | This is the identifier for the system used when publishing the Alarm source. |
| General | TimeToCheckActiveAlarms | DOUBLE | ms | TimeToCheckActiveAlarms |

##### BoschSystem

###### General Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| General | ChangeToParking | BOOLEAN |  | This setting defines if the system will execute the actions to change some motors to parking/notParking. If true before starting the bosch system some motors will change to parking. If false no actions are executed before starting. |
| General | Parking Motor ID 1 | BOOLEAN |  | This setting defines if the motor has to be in parking or not. Parking means that the motor will be off, and the statechart corresponding to the Motor ID will not start. |
| General | Parking Motor ID 10 | BOOLEAN |  | This setting defines if the motor has to be in parking or not. Parking means that the motor will be off, and the statechart corresponding to the Motor ID will not start. |
| General | Parking Motor ID 11 | BOOLEAN |  | This setting defines if the motor has to be in parking or not. Parking means that the motor will be off, and the statechart corresponding to the Motor ID will not start. |
| General | Parking Motor ID 12 | BOOLEAN |  | This setting defines if the motor has to be in parking or not. Parking means that the motor will be off, and the statechart corresponding to the Motor ID will not start. |
| General | Parking Motor ID 13 | BOOLEAN |  | This setting defines if the motor has to be in parking or not. Parking means that the motor will be off, and the statechart corresponding to the Motor ID will not start. |
| General | Parking Motor ID 14 | BOOLEAN |  | This setting defines if the motor has to be in parking or not. Parking means that the motor will be off, and the statechart corresponding to the Motor ID will not start. |
| General | Parking Motor ID 15 | BOOLEAN |  | This setting defines if the motor has to be in parking or not. Parking means that the motor will be off, and the statechart corresponding to the Motor ID will not start. |
| General | Parking Motor ID 16 | BOOLEAN |  | This setting defines if the motor has to be in parking or not. Parking means that the motor will be off, and the statechart corresponding to the Motor ID will not start. |
| General | Parking Motor ID 17 | BOOLEAN |  | This setting defines if the motor has to be in parking or not. Parking means that the motor will be off, and the statechart corresponding to the Motor ID will not start. |
| General | Parking Motor ID 18 | BOOLEAN |  | This setting defines if the motor has to be in parking or not. Parking means that the motor will be off, and the statechart corresponding to the Motor ID will not start. |
| General | Parking Motor ID 19 | BOOLEAN |  | This setting defines if the motor has to be in parking or not. Parking means that the motor will be off, and the statechart corresponding to the Motor ID will not start. |
| General | Parking Motor ID 2 | BOOLEAN |  | This setting defines if the motor has to be in parking or not. Parking means that the motor will be off, and the statechart corresponding to the Motor ID will not start. |
| General | Parking Motor ID 20 | BOOLEAN |  | This setting defines if the motor has to be in parking or not. Parking means that the motor will be off, and the statechart corresponding to the Motor ID will not start. |
| General | Parking Motor ID 21 | BOOLEAN |  | This setting defines if the motor has to be in parking or not. Parking means that the motor will be off, and the statechart corresponding to the Motor ID will not start. |
| General | Parking Motor ID 22 | BOOLEAN |  | This setting defines if the motor has to be in parking or not. Parking means that the motor will be off, and the statechart corresponding to the Motor ID will not start. |
| General | Parking Motor ID 3 | BOOLEAN |  | This setting defines if the motor has to be in parking or not. Parking means that the motor will be off, and the statechart corresponding to the Motor ID will not start. |
| General | Parking Motor ID 4 | BOOLEAN |  | This setting defines if the motor has to be in parking or not. Parking means that the motor will be off, and the statechart corresponding to the Motor ID will not start. |
| General | Parking Motor ID 5 | BOOLEAN |  | This setting defines if the motor has to be in parking or not. Parking means that the motor will be off, and the statechart corresponding to the Motor ID will not start. |
| General | Parking Motor ID 6 | BOOLEAN |  | This setting defines if the motor has to be in parking or not. Parking means that the motor will be off, and the statechart corresponding to the Motor ID will not start. |
| General | Parking Motor ID 7 | BOOLEAN |  | This setting defines if the motor has to be in parking or not. Parking means that the motor will be off, and the statechart corresponding to the Motor ID will not start. |
| General | Parking Motor ID 8 | BOOLEAN |  | This setting defines if the motor has to be in parking or not. Parking means that the motor will be off, and the statechart corresponding to the Motor ID will not start. |
| General | Parking Motor ID 9 | BOOLEAN |  | This setting defines if the motor has to be in parking or not. Parking means that the motor will be off, and the statechart corresponding to the Motor ID will not start. |

###### Restricted Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| General | address | STRING |  | This is the IP address of the MLC. |
| General | password | STRING |  | This is the password to connect to the MLC. |
| General | SpeedFilterMemory | DOUBLE |  | This is the value used for the speed filter memory, this applies to all the axis that are managed by the bosch task. |
| General | user | STRING |  | This is the user account to connect to the MLC. |

##### CW

###### General Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| ACW | Azimuth Deviation Override | BOOLEAN |  | Override the Azimuth Deviation limits. If the value of this param is true the alarm Critical Azimuth deviation will not trigger. Enable this override only for testing or to get ACW out of Azimuth Camera Deviation limit |
| ACW | Default Speed | DOUBLE | deg/s^2 | The default speed of the motor |
| ACW | Negative Software Limit Enable | BOOLEAN |  | Enable the software limit. If the value of this param is false the software limit does not work and will not trigger any alarm. Disable this only for testing or to get the system out of software limit |
| ACW | Positive Software Limit Enable | BOOLEAN |  | Enable the software limit. If the value of this param is false the software limit does not work and will not trigger any alarm. Disable this only for testing or to get the system out of software limit |
| CCW | Default Speed | DOUBLE | deg/s^2 | The default speed of the motor |
| CCW | InPositionMargin | DOUBLE | deg | This value is used to send the in position event. |
| CCW | Negative Limit Switch Enable | BOOLEAN |  | Enable the limit switch. If the value of this param is false the limit switches does not work. Disable this override only for testing or to get CCW out of limit switch |
| CCW | Negative Software Limit Enable | BOOLEAN |  | Enable the software limit. If the value of this param is false the software limit does not work and will not trigger any alarm. Disable this only for testing or to get the system out of software limit |
| CCW | Positive Limit Switch Enable | BOOLEAN |  | Enable the limit switch. If the value of this param is false the limit switches does not work. Disable this override only for testing or to get CCW out of limit switch |
| CCW | Positive Software Limit Enable | BOOLEAN |  | Enable the software limit. If the value of this param is false the software limit does not work and will not trigger any alarm. Disable this only for testing or to get the system out of software limit |

###### Restricted Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| ACW | Azimuth Deviation | DOUBLE | deg | Allowed deviation between azimuth position and camera cable wrap position. If this limit is overcomed the system will trigger a warning |
| ACW | Critical Azimuth Deviation | DOUBLE | deg | Maximum allowed deviation between this subsystem and the tracked one. |
| ACW | Critical Speed Limit | DOUBLE | deg/s | If this speed value is overcomed an the critical speed limit alarm will be triggered |
| ACW | Default Acceleration | DOUBLE | deg/s^2 | The default acceleration of the motor |
| ACW | Default Jerk | DOUBLE | deg/s^3 | The default jerk of the motor |
| ACW | Force Drive Selection | BOOLEAN |  | Force to use a drive when  powering on and not look to using to times to decide. The selected drive will be managed by setting Forced Drive. This setting is for testing purposes only. |
| ACW | Forced Drive | DOUBLE |  | Drive to use when setting Force Drive Selection is True. Use number  1 or 2 to select Motor 1 or  Motor 2 |
| ACW | ID String 1 | STRING |  | This is the identifier for the Motor 1 in string format. |
| ACW | ID String 2 | STRING |  | This is the identifier for the Motor 2 in string format. |
| ACW | Max Acceleration | DOUBLE | deg/s^2 | The maximum allowed acceleration of the motor. If the command has bigger acceleration than this value the command will be rejected |
| ACW | Max Jerk | DOUBLE | deg/s^3 | The maximum allowed jerk of the motor. If the command has bigger jerk than this value the command will be rejected |
| ACW | Max Position | DOUBLE | deg | Maximum allowed position |
| ACW | Max Software Limit | DOUBLE | deg | Maximum allowed position before triggering and alarm |
| ACW | Max Speed | DOUBLE | deg/s^2 | The maximum allowed speed of the motor. If the command has bigger speed than this value the command will be rejected |
| ACW | Min Position | DOUBLE | deg | Minimum allowed position |
| ACW | Min Software Limit | DOUBLE | deg | Minimum allowed position before triggering and alarm |
| ACW | Motor 1 ID | DOUBLE |  | ID for the first motor in CCW |
| ACW | Motor 2 ID | DOUBLE |  | ID for the first motor in CCW |
| ACW | Motor timer file path | STRING |  | Path for the file where using time of each motor will be saved |
| ACW | Move_Trans_TimeMargin | DOUBLE | % | Margin to perform a move before getting a timeout error. It is expressed in % of the calculated time with movement limits. |
| ACW | OffTrans_Timeout | DOUBLE | ms | Timeout time to switch off the system |
| ACW | OnTrans_Timeout | DOUBLE | ms | Timeout time to switch on the system |
| ACW | Position Offset | DOUBLE | deg | This is the offset added to the position of the CW, it is used both for the telemetry sent by the bosch task as well as the commands sent by the statechart. This setting is updated only after a reboot of the TMA-PXI. |
| ACW | ResettingTime | DOUBLE | ms | Timeout time to reset the system |
| ACW | Rotation sense | DOUBLE |  | Manage the rotation sense. A value of 1 makes the ACW rotates clockwise locking to gears and - 1 makes rotates counter clockwise |
| ACW | Speed Limit | DOUBLE | deg/s | If this speed value is overcomed a speed limit warning will be triggered. |
| ACW | StopTrans_Timeout | DOUBLE | ms | Timeout time to stop a movement |
| ACW | SystemSource | STRING |  | This is the identifier for the system used when publishing the Alarm source. |
| ACW | Tracking Acceleration | DOUBLE | deg/s^2 | The acceleration used when tracking |
| ACW | Tracking CompensationGain | DOUBLE |  | Compensation value used in tracking command to convert to position command, according to ((endVelocity^2)/acceleration)*(0.5)*CompensationGain formula |
| ACW | Tracking Jerk | DOUBLE | deg/s^3 | The jerk used when tracking |
| ACW | Tracking queue size | DOUBLE |  | Queue size for the tracking task. If the maximum is achieved new commands will be lost. This setting is only available in the startup of the application |
| ACW | Tracking Speed | DOUBLE | deg/s^2 | The speed used when tracking |
| ACW | Tracking Time offset | DOUBLE | s | Offset for tracking commands to be applied |
| ACW | Tracking Wait for data before error | DOUBLE | ms | After this time without a new command the tracking task will produce an error |
| ACW | Tracking Wait for first track setpoint error | DOUBLE | ms | After this time without the first tracking command the tracking task will produce an error |
| ACW | Tracking Wait time for check setpoint | DOUBLE | us | Time to wait for a new check with a command in the queue but the time is not fulfilled yet |
| ACW | Tracking Wait time if no data in queue | DOUBLE | us | Time to wait for checking for a new command when no data in the queue |
| ACW | WaitAfterReset | DOUBLE | ms | Time to wait after a reset to go to idle |
| CCW | Camera Deviation | DOUBLE | deg | Allowed deviation between camera position and camera cable wrap position. If this limit is overcomed the system will trigger a warning |
| CCW | Camera Deviation Override | BOOLEAN |  | Override the Camera Deviation limits. If the value of this param is true the alarm Critical Camera deviation will not trigger. Enable this override only for testing or to get CCW out of Critical Camera Deviation limit |
| CCW | Critical Azimuth Deviation | DOUBLE | deg | Maximum allowed deviation between this subsystem and the tracked one. |
| CCW | Critical Speed Limit | DOUBLE | deg/s | If this speed value is overcomed an the critical speed limit alarm will be triggered |
| CCW | Default Acceleration | DOUBLE | deg/s^2 | The default acceleration of the motor |
| CCW | Default Jerk | DOUBLE | deg/s^3 | The default jerk of the motor |
| CCW | Force Drive Selection | BOOLEAN |  | Force to use a drive when  powering on and not look to using to times to decide. The selected drive will be managed by setting Forced Drive. This setting is for testing purposes only. |
| CCW | Forced Drive | DOUBLE |  | Drive to use when setting Force Drive Selection is True. Use number  1 or 2 to select Motor 1 or  Motor 2 |
| CCW | ID String 1 | STRING |  | This is the identifier for the Motor 1 in string format. |
| CCW | ID String 2 | STRING |  | This is the identifier for the Motor 2 in string format. |
| CCW | Max Acceleration | DOUBLE | deg/s^2 | The maximum allowed acceleration of the motor. If the command has bigger acceleration than this value the command will be rejected |
| CCW | Max Jerk | DOUBLE | deg/s^3 | The maximum allowed jerk of the motor. If the command has bigger jerk than this value the command will be rejected |
| CCW | Max Position | DOUBLE | deg | Maximum allowed position |
| CCW | Max Software Limit | DOUBLE | deg | Maximum allowed position before triggering and alarm |
| CCW | Max Speed | DOUBLE | deg/s^2 | The maximum allowed speed of the motor. If the command has bigger speed than this value the command will be rejected |
| CCW | Min Position | DOUBLE | deg | Minimum allowed position |
| CCW | Min Software Limit | DOUBLE | deg | Minimum allowed position before triggering and alarm |
| CCW | Motor 1 ID | DOUBLE |  | ID for the first motor in CCW |
| CCW | Motor 2 ID | DOUBLE |  | ID for the first motor in CCW |
| CCW | Motor timer file path | STRING |  | Path for the file where using time of each motor will be saved |
| CCW | Move_Trans_TimeMargin | DOUBLE | % | Margin to perform a move before getting a timeout error. It is expressed in % of the calculated time with movement limits. |
| CCW | OffTrans_Timeout | DOUBLE | ms | Timeout time to switch off the system |
| CCW | OnTrans_Timeout | DOUBLE | ms | Timeout time to switch on the system |
| CCW | Position Offset | DOUBLE | deg | This is the offset added to the position of the CW, it is used both for the telemetry sent by the bosch task as well as the commands sent by the statechart. This setting is updated only after a reboot of the TMA-PXI. |
| CCW | ResettingTime | DOUBLE | ms | Timeout time to reset the system |
| CCW | Rotation sense | DOUBLE |  | Manage the rotation sense. A value of 1 makes the CCW rotates clockwise locking to gears and - 1 makes rotates counter clockwise |
| CCW | Speed Limit | DOUBLE | deg/s | If this speed value is overcomed a speed limit warning will be triggered. |
| CCW | StopTrans_Timeout | DOUBLE | ms | Timeout time to stop a movement |
| CCW | SystemSource | STRING |  | This is the identifier for the system used when publishing the Alarm source. |
| CCW | Tracking Acceleration | DOUBLE | deg/s^2 | The acceleration used when tracking |
| CCW | Tracking CompensationGain | DOUBLE |  | Compensation value used in tracking command to convert to position command, according to ((endVelocity^2)/acceleration)*(0.5)*CompensationGain formula |
| CCW | Tracking Jerk | DOUBLE | deg/s^3 | The jerk used when tracking |
| CCW | Tracking queue size | DOUBLE |  | Queue size for the tracking task. If the maximum is achieved new commands will be lost. This setting is only available in the startup of the application |
| CCW | Tracking Speed | DOUBLE | deg/s^2 | The speed used when tracking |
| CCW | Tracking Time offset | DOUBLE | s | Offset for tracking commands to be applied |
| CCW | Tracking Wait for data before error | DOUBLE | ms | After this time without a new command the tracking task will produce an error |
| CCW | Tracking Wait for first track setpoint error | DOUBLE | ms | After this time without the first tracking command the tracking task will produce an error |
| CCW | Tracking Wait time for check setpoint | DOUBLE | us | Time to wait for a new check with a command in the queue but the time is not fulfilled yet |
| CCW | Tracking Wait time if no data in queue | DOUBLE | us | Time to wait for checking for a new command when no data in the queue |
| CCW | WaitAfterReset | DOUBLE | ms | Time to wait after a reset to go to idle |
| General | TimeToCheckActiveAlarms | DOUBLE | ms | TimeToCheckActiveAlarms |

##### DeployablePlatform

###### General Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| DeployablePlatform1 | ID String | STRING |  | This is the identifier for the deployable platform in string format. |
| DeployablePlatform1 | Platform Velocity | DOUBLE | mm/s | The moving velocity of any platform element. |
| DeployablePlatform2 | ID String | STRING |  | This is the identifier for the deployable platform in string format. |
| DeployablePlatform2 | Platform Velocity | DOUBLE | mm/s | The moving velocity of any platform element. |

###### Restricted Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| DeployablePlatform1 | Error Timeout Margin | DOUBLE |  | The error timeout margin in %. |
| DeployablePlatform1 | InRangeMargin | DOUBLE | mm | The margin for deployed and retracted positions of the system |
| DeployablePlatform1 | Max Platform Position 1 | DOUBLE | mm | The maximum position of platform element 1. |
| DeployablePlatform1 | Max Platform Position 2 | DOUBLE | mm | The maximum position of platform element 2. |
| DeployablePlatform1 | Min Platform Position 1 | DOUBLE | mm | The minimum position of platform element 1. |
| DeployablePlatform1 | Min Platform Position 2 | DOUBLE | mm | The minimum position of platform element 2. |
| DeployablePlatform1 | Motor ID Platform 1 | DOUBLE |  | The motor ID of platform motor 1. |
| DeployablePlatform1 | Motor ID Platform 2 | DOUBLE |  | The motor ID of platform motor 2. |
| DeployablePlatform1 | Platform Acceleration | DOUBLE | mm/s^2 | The acceleration of the platform. |
| DeployablePlatform1 | Platform Deceleration | DOUBLE | mm/s^2 | The deceleration of any platform element. |
| DeployablePlatform1 | Platform Jerk | DOUBLE | mm/s^3 | The jerk of any platform element. |
| DeployablePlatform1 | Platform Max Critical Velocity | DOUBLE | mm/s | The maximum critical velocity, which causes an alarm to be triggered. |
| DeployablePlatform1 | Platform Max Velocity | DOUBLE | mm/s | The maximum velocity, which causes a warning to be triggered. |
| DeployablePlatform1 | TimeoutLockExtension | DOUBLE | ms | Timeout time for the lock extension command. |
| DeployablePlatform1 | TimeoutMoveMargin | DOUBLE | % | Timeout time margin for the move cmd. |
| DeployablePlatform1 | TimeoutPowerOff | DOUBLE | ms | Timeout time for the power off cmd. |
| DeployablePlatform1 | TimeoutPowerOn | DOUBLE | ms | Timeout time for the power on cmd. |
| DeployablePlatform1 | TimeoutReset | DOUBLE | ms | Timeout time for the reset cmd. |
| DeployablePlatform1 | TimeoutStop | DOUBLE | ms | Timeout time for the stop cmd. |
| DeployablePlatform2 | Error Timeout Margin | DOUBLE |  | The error timeout margin in %. |
| DeployablePlatform2 | InRangeMargin | DOUBLE | mm | The margin for deployed and retracted positions of the system |
| DeployablePlatform2 | Max Platform Position 1 | DOUBLE | mm | The maximum position of platform element 1. |
| DeployablePlatform2 | Max Platform Position 2 | DOUBLE | mm | The maximum position of platform element 2. |
| DeployablePlatform2 | Min Platform Position 1 | DOUBLE | mm | The minimum position of platform element 1. |
| DeployablePlatform2 | Min Platform Position 2 | DOUBLE | mm | The minimum position of platform element 2. |
| DeployablePlatform2 | Motor ID Platform 1 | DOUBLE |  | The motor ID of platform motor 1. |
| DeployablePlatform2 | Motor ID Platform 2 | DOUBLE |  | The motor ID of platform motor 2. |
| DeployablePlatform2 | Platform Acceleration | DOUBLE | mm/s^2 | The acceleration of the platform. |
| DeployablePlatform2 | Platform Deceleration | DOUBLE | mm/s^2 | The deceleration of any platform element. |
| DeployablePlatform2 | Platform Jerk | DOUBLE | mm/s^3 | The jerk of any platform element. |
| DeployablePlatform2 | Platform Max Critical Velocity | DOUBLE | mm/s | The maximum critical velocity, which causes an alarm to be triggered. |
| DeployablePlatform2 | Platform Max Velocity | DOUBLE | mm/s | The maximum velocity, which causes a warning to be triggered. |
| DeployablePlatform2 | TimeoutLockExtension | DOUBLE | ms | Timeout time for the lock extension command. |
| DeployablePlatform2 | TimeoutMoveMargin | DOUBLE | % | Timeout time margin for the move cmd. |
| DeployablePlatform2 | TimeoutPowerOff | DOUBLE | ms | Timeout time for the power off cmd. |
| DeployablePlatform2 | TimeoutPowerOn | DOUBLE | ms | Timeout time for the power on cmd. |
| DeployablePlatform2 | TimeoutReset | DOUBLE | ms | Timeout time for the reset cmd. |
| DeployablePlatform2 | TimeoutStop | DOUBLE | ms | Timeout time for the stop cmd. |
| General | EnableExtensionLockGuard | BOOLEAN |  | If true the guard that checks that the deployable platform extension is inserted is executed. If false this guar is not executed. |
| General | Max Elevation Angle | DOUBLE | deg | The maximum position of the elevation angle for allowing the deployable platforms to power on. |
| General | Min Elevation Angle | DOUBLE | deg | The minimum position of the elevation angle for allowing the deployable platforms to power on. |
| General | SystemSource | STRING |  | This is the identifier for the system used when publishing the Alarm source. |
| General | TimeToCheckActiveAlarms | DOUBLE | ms | TimeToCheckActiveAlarms |

##### EncoderSystem

###### General Access Setting list

There are no settings under this section.

###### Restricted Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| General | ACW margin | DOUBLE | deg | Marin used in azimuth reference calculation with Azimuth Cable Wrap (ACW). The algorithm will use ACW as base value for azimuth and compare it to adapt to ACW value or to set as invalid reference. |
| General | Azimuth Critical Active Heads | DOUBLE |  | If the number of active heads for azimuth axis is bellow this value an alarm will be triggered |
| General | Azimuth heads reference threshold [i.u] | DOUBLE |  | Maximum error in the reference of azimuth heads |
| General | Azimuth reference margin | DOUBLE | deg | If the reference between any head and the mean value of the 4 heads is higher than this value, the encoder reference (homing) will fail. |
| General | Azimuth Tape Line Count | DOUBLE |  | Number of line counts in the azimuth tape |
| General | Azimuth Telescope Offset | DOUBLE | deg | REBOOT AFTER CHANGING!! This is the offset between telescope zero and encoder tape zero for azimuth. The zero for encoder is the junction of the tape and the zero for telescope is the north orientation |
| General | Check UPD timeout | DOUBLE | ms | Time to start UPD loop in AXES PXI. This time must be less than CMD timeout power on, since this is an step of power on |
| General | CMD timeout clear errors | DOUBLE | ms | Timeout for  clearing active errors in EIB task |
| General | CMD timeout clear heads errors | DOUBLE | ms | Timeout for  clearing active heads errors |
| General | CMD timeout power off | DOUBLE | ms | Timeout for  powering off axis heads |
| General | CMD timeout power on | DOUBLE | ms | Timeout for  powering on axis heads |
| General | CMD timeout reboot | DOUBLE | ms | Timeout for rebooting EIB hardware |
| General | CMD timeout reference off | DOUBLE | ms | Timeout to stop reference execution |
| General | CMD timeout reference on | DOUBLE | ms | Timeout to perform reference |
| General | CMD timeout Relative Offset | DOUBLE | ms | Timeout to set the relative position offset in the EIB readings |
| General | EIB config file path | STRING |  | The file path in PXI to get the EIB configuration. This file is Heidenhain developed file |
| General | Elevation Critical Active Heads | DOUBLE |  | If the number of active heads for elevation axis is bellow this value an alarm will be triggered |
| General | Elevation heads reference threshold [i.u] | DOUBLE | i.u. | Maximum error in the reference of elevation heads |
| General | Elevation reference margin | DOUBLE | deg | If the reference between any head and the mean value of the 4 heads is higher than this value, the encoder reference (homing) will fail. |
| General | Elevation Tape Line Count | DOUBLE |  | Number of line counts in the elevation tape |
| General | Elevation Telescope Offset | DOUBLE | deg | This is the offset between telescope zero and encoder tape zero for Elevation. The zero for encoder is the start of the tape closest when telescope is horizon position and the zero for telescope is the horizon position |
| General | FPGA Clock Rate | DOUBLE | MHz | Clock rate in MHz of the trigger program running in FPGA |
| General | Logging IP | STRING |  | IP for logging errors. The errors found by EIB will be sent to this port |
| General | Sync Trigger Offset | DOUBLE | us | Time in us to wait before sending trigger to EIB |
| General | Sync Trigger on Time | DOUBLE | us | Time in us the EIB synchronization trigger will be on |
| General | UDP reading timeout | DOUBLE | ms | Timeout for getting data from EIB UDP port |
| General | Wait after Reset | DOUBLE | s | This is the time to wait before reconnecting to EIB when a reset is performed |
| Head1 | Azimuth Axis | BOOLEAN |  | If True the head is a azimuth axis head, otherwise is for elevation |
| Head1 | EIB Input Name | STRING |  | Input name of the head definition in the EIB |
| Head1 | Head Name | STRING |  | Name of the head according to Empresarios (UTE TMA) naming |
| Head1 | NSV_LinkID | DOUBLE |  | This ID is used to link the encoder head data to the corresponding NSV. The options are 1, 2 ,3 or 4.  |
| Head1 | Position Gain | DOUBLE | rad/periods | Convert from periods to rad or periods/s to rad/s |
| Head1 | Position Offset | DOUBLE | i.u. | Position offset of the head to do all heads read the same value after referencing |
| Head2 | Azimuth Axis | BOOLEAN |  | If True the head is a azimuth axis head, otherwise is for elevation |
| Head2 | EIB Input Name | STRING |  | Input name of the head definition in the EIB |
| Head2 | Head Name | STRING |  | Name of the head according to Empresarios (UTE TMA) naming |
| Head2 | NSV_LinkID | DOUBLE |  | This ID is used to link the encoder head data to the corresponding NSV. The options are 1, 2 ,3 or 4.  |
| Head2 | Position Gain | DOUBLE | rad/periods | Convert from periods to rad or periods/s to rad/s |
| Head2 | Position Offset | DOUBLE | i.u. | Position offset of the head to do all heads read the same value after referencing |
| Head3 | Azimuth Axis | BOOLEAN |  | If True the head is a azimuth axis head, otherwise is for elevation |
| Head3 | EIB Input Name | STRING |  | Input name of the head definition in the EIB |
| Head3 | Head Name | STRING |  | Name of the head according to Empresarios (UTE TMA) naming |
| Head3 | NSV_LinkID | DOUBLE |  | This ID is used to link the encoder head data to the corresponding NSV. The options are 1, 2 ,3 or 4.  |
| Head3 | Position Gain | DOUBLE | rad/periods | Convert from periods to rad or periods/s to rad/s |
| Head3 | Position Offset | DOUBLE | i.u. | Position offset of the head to do all heads read the same value after referencing |
| Head4 | Azimuth Axis | BOOLEAN |  | If True the head is a azimuth axis head, otherwise is for elevation |
| Head4 | EIB Input Name | STRING |  | Input name of the head definition in the EIB |
| Head4 | Head Name | STRING |  | Name of the head according to Empresarios (UTE TMA) naming |
| Head4 | NSV_LinkID | DOUBLE |  | This ID is used to link the encoder head data to the corresponding NSV. The options are 1, 2 ,3 or 4.  |
| Head4 | Position Gain | DOUBLE | rad/periods | Convert from periods to rad or periods/s to rad/s |
| Head4 | Position Offset | DOUBLE | i.u. | Position offset of the head to do all heads read the same value after referencing |
| Head5 | Azimuth Axis | BOOLEAN |  | If True the head is a azimuth axis head, otherwise is for elevation |
| Head5 | EIB Input Name | STRING |  | Input name of the head definition in the EIB |
| Head5 | Head Name | STRING |  | Name of the head according to Empresarios (UTE TMA) naming |
| Head5 | NSV_LinkID | DOUBLE |  | This ID is used to link the encoder head data to the corresponding NSV. The options are 1, 2 ,3 or 4.  |
| Head5 | Position Gain | DOUBLE | rad/periods | Convert from periods to rad or periods/s to rad/s |
| Head5 | Position Offset | DOUBLE | i.u. | Position offset of the head to do all heads read the same value after referencing |
| Head6 | Azimuth Axis | BOOLEAN |  | If True the head is a azimuth axis head, otherwise is for elevation |
| Head6 | EIB Input Name | STRING |  | Input name of the head definition in the EIB |
| Head6 | Head Name | STRING |  | Name of the head according to Empresarios (UTE TMA) naming |
| Head6 | NSV_LinkID | DOUBLE |  | This ID is used to link the encoder head data to the corresponding NSV. The options are 1, 2 ,3 or 4.  |
| Head6 | Position Gain | DOUBLE | rad/periods | Convert from periods to rad or periods/s to rad/s |
| Head6 | Position Offset | DOUBLE | i.u. | Position offset of the head to do all heads read the same value after referencing |
| Head7 | Azimuth Axis | BOOLEAN |  | If True the head is a azimuth axis head, otherwise is for elevation |
| Head7 | EIB Input Name | STRING |  | Input name of the head definition in the EIB |
| Head7 | Head Name | STRING |  | Name of the head according to Empresarios (UTE TMA) naming |
| Head7 | NSV_LinkID | DOUBLE |  | This ID is used to link the encoder head data to the corresponding NSV. The options are 1, 2 ,3 or 4.  |
| Head7 | Position Gain | DOUBLE | rad/periods | Convert from periods to rad or periods/s to rad/s |
| Head7 | Position Offset | DOUBLE | i.u. | Position offset of the head to do all heads read the same value after referencing |
| Head8 | Azimuth Axis | BOOLEAN |  | If True the head is a azimuth axis head, otherwise is for elevation |
| Head8 | EIB Input Name | STRING |  | Input name of the head definition in the EIB |
| Head8 | Head Name | STRING |  | Name of the head according to Empresarios (UTE TMA) naming |
| Head8 | NSV_LinkID | DOUBLE |  | This ID is used to link the encoder head data to the corresponding NSV. The options are 1, 2 ,3 or 4.  |
| Head8 | Position Gain | DOUBLE | rad/periods | Convert from periods to rad or periods/s to rad/s |
| Head8 | Position Offset | DOUBLE | i.u. | Position offset of the head to do all heads read the same value after referencing |

##### LockingPins

###### General Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| General | DisableElevationPsotionCheck | BOOLEAN |  | This is for disabling the elevation position check, this allows inserting the LP without checking the elevation position. |
| LockingPin1 | DefaultSpeed | DOUBLE | mm/s | Default Speed used by the motor to move |
| LockingPin1 | ID String | STRING |  | This is the identifier for the cover in string format. |
| LockingPin2 | DefaultSpeed | DOUBLE | mm/s | Default Speed used by the motor to move |
| LockingPin2 | ID String | STRING |  | This is the identifier for the cover in string format. |

###### Restricted Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| General | ElevationPosNinetyMinus | DOUBLE | deg | This is the - limit for the Elevation axis to be able to insert the LP at 90 degrees for EL axis.  |
| General | ElevationPosNinetyPlus | DOUBLE | deg | This is the + limit for the Elevation axis to be able to insert the LP at 90 degrees for EL axis. |
| General | ElevationPosZeroMinus | DOUBLE | deg | This is the - limit for the Elevation axis to be able to insert the LP at 0 degrees for EL axis. |
| General | ElevationPosZeroPlus | DOUBLE | deg | This is the + limit for the Elevation axis to be able to insert the LP at 0 degrees for EL axis. |
| General | SystemSource | STRING |  | This is the identifier for the system used when publishing the Alarm source. |
| General | TimeToCheckActiveAlarms | DOUBLE | ms | TimeToCheckActiveAlarms |
| LockingPin1 | DefaultAcceleration | DOUBLE | mm/s^2 | Default acceleration used by the motor to move |
| LockingPin1 | DefaultJerk | DOUBLE | mm/s^3 | Default Jerk used by the motor to move |
| LockingPin1 | FreePosition | DOUBLE | mm | Position to move locking pin where the elevation axis is free to move |
| LockingPin1 | LockPosition | DOUBLE | mm | Position to move locking pin where the elevation axis is locked |
| LockingPin1 | Max Critical Speed | DOUBLE | mm/s | Max speed allowable. Above this limit the event system will trigger an alarm |
| LockingPin1 | Max Position | DOUBLE | mm | The maximum position of the locking pin motor, at which an error is fired. |
| LockingPin1 | Max Speed | DOUBLE | mm/s | The maximum speed of the locking pin motor, if the speed is greater than this the command is rejected. |
| LockingPin1 | Min Position | DOUBLE | mm | The minimum position of the balancing motor, at which an error is fired. |
| LockingPin1 | MotorID | DOUBLE |  | The motor ID used in this instance. |
| LockingPin1 | MoveVelocity_Trns_Timeout | DOUBLE | ms | Timeout for a move velocity command. -1 no timeout |
| LockingPin1 | Move_Trans_TimeMargin | DOUBLE | % | Margin to apply to calculation time for specified movement before a timeout error occurs |
| LockingPin1 | OffTrans_Timeout | DOUBLE | ms | Power off transition timeout |
| LockingPin1 | OnTrans_Timeout | DOUBLE | ms | Power on transition timeout |
| LockingPin1 | ResetTrans_Timeout | DOUBLE | ms | Reset transition timeout |
| LockingPin1 | Speed Limit | DOUBLE | deg/s | If this speed value is overcomed a speed limit warning will be triggered. |
| LockingPin1 | StopTrans_Timeout | DOUBLE | ms | Maximum time allowed for a stop command |
| LockingPin1 | TestPosition | DOUBLE | mm | Position to move locking pin where the elevation axis has the ability to perform small movements. Position for testing and balancing |
| LockingPin2 | DefaultAcceleration | DOUBLE | mm/s^2 | Default acceleration used by the motor to move |
| LockingPin2 | DefaultJerk | DOUBLE | mm/s^3 | Default Jerk used by the motor to move |
| LockingPin2 | FreePosition | DOUBLE | mm | Position to move locking pin where the elevation axis is free to move |
| LockingPin2 | LockPosition | DOUBLE | mm | Position to move locking pin where the elevation axis is locked |
| LockingPin2 | Max Critical Speed | DOUBLE | mm/s | Max speed allowable. Above this limit the event system will trigger an alarm |
| LockingPin2 | Max Position | DOUBLE | mm | The maximum position of the locking pin motor, at which an error is fired. |
| LockingPin2 | Max Speed | DOUBLE | mm/s | The maximum speed of the locking pin motor, if the speed is greater than this the command is rejected. |
| LockingPin2 | Min Position | DOUBLE | mm | The minimum position of the balancing motor, at which an error is fired. |
| LockingPin2 | MotorID | DOUBLE |  | The motor ID used in this instance. |
| LockingPin2 | MoveVelocity_Trns_Timeout | DOUBLE | ms | Timeout for a move velocity command. -1 no timeout |
| LockingPin2 | Move_Trans_TimeMargin | DOUBLE | % | Margin to apply to calculation time for specified movement before a timeout error occurs |
| LockingPin2 | OffTrans_Timeout | DOUBLE | ms | Power off transition timeout |
| LockingPin2 | OnTrans_Timeout | DOUBLE | ms | Power on transition timeout |
| LockingPin2 | ResetTrans_Timeout | DOUBLE | ms | Reset transition timeout |
| LockingPin2 | Speed Limit | DOUBLE | deg/s | If this speed value is overcomed a speed limit warning will be triggered. |
| LockingPin2 | StopTrans_Timeout | DOUBLE | ms | Maximum time allowed for a stop command |
| LockingPin2 | TestPosition | DOUBLE | mm | Position to move locking pin where the elevation axis has the ability to perform small movements. Position for testing and balancing |

##### MainAxis

###### General Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| Azimuth | EUI Default Acceleration | DOUBLE | deg/s^2 | Default acceleration in EUI command mode |
| Azimuth | EUI Default Jerk | DOUBLE | deg/s^3 | Default Jerk in EUI command mode |
| Azimuth | EUI Default Velocity | DOUBLE | deg/s | Default velocity in EUI command mode |
| Azimuth | EUI Max Acceleration | DOUBLE | deg/s^2 | Maximum allowed acceleration in EUI command mode |
| Azimuth | EUI Max Jerk | DOUBLE | deg/s^3 | Maximum Jerk in EUI command mode |
| Azimuth | EUI Max Velocity | DOUBLE | deg/s | Maximum allowed velocity in EUI command mode |
| Azimuth | HHD Default Acceleration | DOUBLE | deg/s^2 | Default acceleration in HHD command mode |
| Azimuth | HHD Default Jerk | DOUBLE | deg/s^3 | Default Jerk in HHD command mode |
| Azimuth | HHD Default Velocity | DOUBLE | deg/s | Default velocity in HHD command mode |
| Azimuth | HHD Max Acceleration | DOUBLE | deg/s^2 | Maximum allowed acceleration in HHD command mode |
| Azimuth | HHD Max Jerk | DOUBLE | deg/s^3 | Maximum Jerk in HHD command mode |
| Azimuth | HHD Max Velocity | DOUBLE | deg/s | Maximum allowed velocity in HHD command mode |
| Azimuth | In Position Margin | DOUBLE | deg | This value is used to send the in position event |
| Azimuth | Limits Max Position enable | BOOLEAN |  | Maximum allowed position command verification is enabled |
| Azimuth | Limits Min Position enable | BOOLEAN |  | Minimum allowed position command verification is enabled |
| Azimuth | Limits Negative Adjustable Software limit enable | BOOLEAN |  | Enable negative adjustable software limit |
| Azimuth | Limits Negative Limit Switch enable | BOOLEAN |  | Enable negative Limit Switch |
| Azimuth | Limits Negative Operational Limit Switch enable | BOOLEAN |  | Enable negative Operational limit switch |
| Azimuth | Limits Negative Positive Software limit enable | BOOLEAN |  | Enable positive software limit in softmotion. Over this limit the axis does not allow any movement. |
| Azimuth | Limits Negative Software limit enable | BOOLEAN |  | Enable negative software limit |
| Azimuth | Limits Overspeed Warning Value | DOUBLE | deg/s | If this speed value is overcomed a speed limit warning will be triggered. |
| Azimuth | Limits Positive Adjustable Software limit enable | BOOLEAN |  | Enable positive adjustable software limit |
| Azimuth | Limits Positive Limit Switch enable | BOOLEAN |  | Enable positive Limit Switch |
| Azimuth | Limits Positive Operational Limit Switch enable | BOOLEAN |  | Enable positive Operational imit switch |
| Azimuth | Limits Positive Software limit enable | BOOLEAN |  | Enable positive software limit |
| Azimuth | Limits Softmotion Negative Software limit enable | BOOLEAN |  | Enable positive software limit in softmotion. Bellow this limit the axis does not allow any movement. |
| Azimuth | Limits Softmotion Positive Software limit enable | BOOLEAN |  | Enable positive software limit in softmotion. Over this limit the axis does not allow any movement. |
| Azimuth | TCS Default Acceleration | DOUBLE | deg/s^2 | Default acceleration in CSC command mode |
| Azimuth | TCS Default Jerk | DOUBLE | deg/s^3 | Default Jerk in CSC command mode |
| Azimuth | TCS Default Velocity | DOUBLE | deg/s | Default velocity in CSC command mode |
| Azimuth | TCS Max Acceleration | DOUBLE | deg/s^2 | Maximum allowed acceleration in CSC command mode |
| Azimuth | TCS Max Jerk | DOUBLE | deg/s^3 | Maximum Jerk in CSC command mode |
| Azimuth | TCS Max Velocity | DOUBLE | deg/s | Maximum allowed velocity in CSC command mode |
| Elevation | EUI Default Acceleration | DOUBLE | deg/s^2 | Default acceleration in EUI command mode |
| Elevation | EUI Default Jerk | DOUBLE | deg/s^3 | Default Jerk in EUI command mode |
| Elevation | EUI Default Velocity | DOUBLE | deg/s | Default velocity in EUI command mode |
| Elevation | EUI Max Acceleration | DOUBLE | deg/s^2 | Maximum allowed acceleration in EUI command mode |
| Elevation | EUI Max Jerk | DOUBLE | deg/s^3 | Maximum Jerk in EUI command mode |
| Elevation | EUI Max Velocity | DOUBLE | deg/s | Maximum allowed velocity in EUI command mode |
| Elevation | HHD Default Acceleration | DOUBLE | deg/s^2 | Default acceleration in HHD command mode |
| Elevation | HHD Default Jerk | DOUBLE | deg/s^3 | Default Jerk in HHD command mode |
| Elevation | HHD Default Velocity | DOUBLE | deg/s | Default velocity in HHD command mode |
| Elevation | HHD Max Acceleration | DOUBLE | deg/s^2 | Maximum allowed acceleration in HHD command mode |
| Elevation | HHD Max Jerk | DOUBLE | deg/s^3 | Maximum Jerk in HHD command mode |
| Elevation | HHD Max Velocity | DOUBLE | deg/s | Maximum allowed velocity in HHD command mode |
| Elevation | In Position Margin | DOUBLE | deg | This value is used to send the in position event |
| Elevation | Limits Max Position enable | BOOLEAN |  | Maximum allowed position command verification is enabled |
| Elevation | Limits Min Position enable | BOOLEAN |  | Minimum allowed position command verification is enabled |
| Elevation | Limits Negative Adjustable Software limit enable | BOOLEAN |  | Enable negative adjustable software limit |
| Elevation | Limits Negative Limit Switch enable | BOOLEAN |  | Enable negative Limit Switch |
| Elevation | Limits Negative Operational Limit Switch enable | BOOLEAN |  | Enable negative Operational limit switch |
| Elevation | Limits Negative Software limit enable | BOOLEAN |  | Enable negative software limit |
| Elevation | Limits Overspeed Warning Value | DOUBLE | deg/s | If this speed value is overcomed a speed limit warning will be triggered. |
| Elevation | Limits Positive Adjustable Software limit enable | BOOLEAN |  | Enable positive adjustable software limit |
| Elevation | Limits Positive Limit Switch enable | BOOLEAN |  | Enable positive Limit Switch |
| Elevation | Limits Positive Operational Limit Switch enable | BOOLEAN |  | Enable positive Operational imit switch |
| Elevation | Limits Positive Software limit enable | BOOLEAN |  | Enable positive software limit |
| Elevation | Limits Softmotion Negative Software limit enable | BOOLEAN |  | Enable positive software limit in softmotion. Bellow this limit the axis does not allow any movement. |
| Elevation | Limits Softmotion Positive Software limit enable | BOOLEAN |  | Enable positive software limit in softmotion. Over this limit the axis does not allow any movement. |
| Elevation | TCS Default Acceleration | DOUBLE | deg/s^2 | Default acceleration in CSC command mode |
| Elevation | TCS Default Jerk | DOUBLE | deg/s^3 | Default Jerk in CSC command mode |
| Elevation | TCS Default Velocity | DOUBLE | deg/s | Default velocity in CSC command mode |
| Elevation | TCS Max Acceleration | DOUBLE | deg/s^2 | Maximum allowed acceleration in CSC command mode |
| Elevation | TCS Max Jerk | DOUBLE | deg/s^3 | Maximum Jerk in CSC command mode |
| Elevation | TCS Max Velocity | DOUBLE | deg/s | Maximum allowed velocity in CSC command mode |

###### Restricted Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| Azimuth | Allow Relative Movements | BOOLEAN |  | Allow to move the telescope without doing reference in position mode |
| Azimuth | Command Relative Movements | BOOLEAN |  | The move commands will be relative movements if this parameter is true and otherwise absolute movements will be performed |
| Azimuth | Control Acceleration FeedForward Gain | DOUBLE | % | Controller Acceleration feedforward gain |
| Azimuth | Control Activate Speed FeedForward In Tracking? | BOOLEAN |  | The FeedForward for speed gain will be activated if the axis is in Tracking mode. Otherwise it will be deactivated. The activation will increase according to Control FeedForward Activation Variation settings. See also Control Apply FeedForward? setting |
| Azimuth | Control Apply Speed FeedForward? | BOOLEAN |  | If this settings is True the speed feedforward is always active otherwise could be active or not depending on the Control Activate FeedForward In Tracking? setting |
| Azimuth | Control Damping Active | BOOLEAN |  | For azimuth axis, activate the active damping control |
| Azimuth | Control Damping Max Allowed Force X Direction | DOUBLE | N | The maximum allowed force for active damping control action in X direction. This saturation affects only to active damping. Take into account that active damping action is superposed to rotation control action |
| Azimuth | Control Damping Max Allowed Force Y Direction | DOUBLE | N | The maximum allowed force for active damping control action in Y direction. This saturation affects only to active damping. Take into account that active damping action is superposed to rotation control action |
| Azimuth | Control Damping X Direction Gain | DOUBLE |  | Active controller gain for  X direction |
| Azimuth | Control Damping Y Direction Gain | DOUBLE |  | Active controller gain for  Y direction |
| Azimuth | Control Inertia | DOUBLE | kg*m^2 | Inertia of the axis |
| Azimuth | Control Integral Disabled | BOOLEAN |  | The integral action of the controller is disabled |
| Azimuth | Control Kp (Speed Error Gain) | DOUBLE | rad/s | Speed error gain to use in the controller |
| Azimuth | Control Kv (Position Error Gain) | DOUBLE | rad/s | Position error gain to use in the controller |
| Azimuth | Control Maximun Torque Variation | DOUBLE | N*m | Maximum allowed torque variation. There is a filter in the controller that allows the value of this settings as maximum change between iterations |
| Azimuth | Control Speed FeedForward Activation Variation | DOUBLE |  | The speed feedforward gain will increase this value every iteration until the required value in Control Speed FeedForward setting is achieved. Decrease of the value will be made next iteration and this setting has no effect. |
| Azimuth | Control Speed FeedForward Gain | DOUBLE | % | Controller Speed feedforward gain |
| Azimuth | Control Ti (Integral time) | DOUBLE | s | Integral time for the controller |
| Azimuth | Homing Acceleration | DOUBLE | deg/s^2 | Acceleration for Homing procedure |
| Azimuth | Homing Jerk | DOUBLE | deg/s^3 | Jerk for Homing procedure |
| Azimuth | Homing Position Direction | DOUBLE | deg | If the actual position is higher than the value in this setting the homing will be performed in negative direction. Otherwise positive direction homing will be done |
| Azimuth | Homing Speed | DOUBLE | deg/s | Speed for Homing procedure |
| Azimuth | Limits Active Drives | DOUBLE |  | Bellow this value the system will send a warning |
| Azimuth | Limits AZCW Critical Deviation Value | DOUBLE |  | Maximum allowed deviation between AZCW and AZ verification value. If this value is overcomed an alarm will be generated in azimuth |
| Azimuth | Limits AZCW Deviation Enable | BOOLEAN |  | Maximum allowed deviation between AZCW and AZ verification is enabled |
| Azimuth | Limits AZCW Maximum Deviation Value | DOUBLE |  | Maximum allowed deviation between AZCW and AZ verification value. If this value is overcomed a warning will be generated in azimuth |
| Azimuth | Limits Following Error enable | BOOLEAN |  | Enable the following error |
| Azimuth | Limits Following Error Value | DOUBLE | deg | Set the maximum allowed following error |
| Azimuth | Limits Max Position value | DOUBLE | deg | Maximum allowed position command |
| Azimuth | Limits Min Position value | DOUBLE | deg | Minimum allowed position command |
| Azimuth | Limits Negative Adjustable Software limit value | DOUBLE | deg | Value for Negative adjustable software limit.  This limit will be valid if it is enabled independent if the axis may move in relative mode |
| Azimuth | Limits Negative Software limit value | DOUBLE | deg | Value for negative software limit.  This limit will be valid if it is enabled independent if the axis may move in relative mode |
| Azimuth | Limits Overspeed enable | BOOLEAN | deg/s | Enable the overspeed limit, does not affect the warning. |
| Azimuth | Limits Overspeed Value | DOUBLE | deg/s | If this speed value is overcomed an the critical speed limit alarm will be triggered. |
| Azimuth | Limits Positive Adjustable Software limit value | DOUBLE | deg | Value for Positive adjustable software limit.  This limit will be valid if it is enabled independent if the axis may move in relative mode |
| Azimuth | Limits Positive Software limit value | DOUBLE | deg | Value for Positive software limit.  This limit will be valid if it is enabled independent if the axis may move in relative mode |
| Azimuth | Limits Softmotion Negative Software limit value | DOUBLE | deg | Value for softmotion Positive software limit.  Bellow this limit the axis does not allow any movement. This limit must allow all desired movements, also maintenance movements to safety limits |
| Azimuth | Limits Softmotion Positive Software limit value | DOUBLE | deg | Value for softmotion Positive software limit.  Over this limit the axis does not allow any movement. This limit must allow all desired movements, also maintenance movements to safety limits |
| Azimuth | Observer Ad | STRING |  | A matrix for the position/speed observer. It is a matrix, use "," to separate columns and "_" to add rows |
| Azimuth | Observer Bd | STRING |  | B matrix for the position/speed observer. It is a matrix, use "," to separate columns and "_" to add rows |
| Azimuth | Observer K | STRING |  | K matrix for the position/speed observer. It is a matrix, use "," to separate columns and "_" to add rows |
| Azimuth | Observer MaxAllowedError | DOUBLE | rad | Maximum allowed deviation from the real position to consider the observer as stable. Over this deviation the observer will not be used if the data from the encoder is missing and an extrapolation from the last valid position and speed will be used. |
| Azimuth | OVERRIDE Default Acceleration | DOUBLE | deg/s^2 | Default acceleration when a safety override of limit switches is active |
| Azimuth | OVERRIDE Default Jerk | DOUBLE | deg/s^3 | Default jerk when a safety override of limit switches is active |
| Azimuth | OVERRIDE Default Velocity | DOUBLE | deg/s | Default velocity when a safety limit switch is overrided |
| Azimuth | OVERRIDE Max Acceleration | DOUBLE | deg/s^2 | Maximum allowed acceleration when a safety override of limit switches is active |
| Azimuth | OVERRIDE Max Jerk | DOUBLE | deg/s^3 | Maximum jerk when a safety override of limit switches is active |
| Azimuth | OVERRIDE Max Velocity | DOUBLE | deg/s | Maximum allowed velocity when a safety limit switch is overrided |
| Azimuth | Position readings when homming | DOUBLE |  | This value will manage the times data is get from AxesPXI to calculate the actual absolute position. Each reading is a packet of 50 elements. More data makes the mean more insensitive to noise effect. |
| Azimuth | Softmotion Error Stop acceleration | DOUBLE | deg/s^2 | This acceleration will be applied when the softmotion axis detects a fault, like overspeed or following error |
| Azimuth | Softmotion Error Stop jerk | DOUBLE | deg/s^3 | This jerk will be applied when the softmotion axis detects a fault, like overspeed or following error |
| Azimuth | Softmotion In position buffer size | DOUBLE |  | This value manage the buffer size to calculate the position rms value that is used for In position event |
| Azimuth | Softmotion In position Hysteresis | DOUBLE | deg | This value added to the Softmotion In position Margin determines when the in position is set to false |
| Azimuth | Softmotion In position Margin | DOUBLE | deg | This value will indicate when the softmotion axis indicates that the axis in desired position |
| Azimuth | Softmotion max acceleration | DOUBLE | deg/s^2 | This acceleration is the maximum available acceleration for the axis. |
| Azimuth | Softmotion max jerk | DOUBLE | deg/s^3 | This jerk is the maximum available jerk for the axis. |
| Azimuth | Softmotion max speed | DOUBLE | deg/s | This speed is the maximum available speed for the axis. |
| Azimuth | Softmotion Maximum Torque Per Drive | DOUBLE | Nm | The maximum allowed torque per drive. The system will not allow that command to each drive goes over this value |
| Azimuth | Softmotion Minimun drives for no fault | DOUBLE |  | Bellow this limit the axis will be in fault |
| Azimuth | Softmotion No received Data Counter Alarm Value | DOUBLE |  | Above this number the  softmotion driver is in fault. Its time, no new data is received from encoder an internal counter increases its value by 1000, decreasing by 1 each no problem iteration |
| Azimuth | Softmotion No received Data Counter Warning Value | DOUBLE |  | Above this number the softmotion driver send a warning. Its time, no new data is received from encoder an internal counter increases its value by 1000, decreasing by 1 each no problem iteration |
| Azimuth | Softmotion Number of Electric Turns | DOUBLE |  | Number of electric turns in for the axis. This is the number of poles |
| Azimuth | Softmotion Speed From Position | BOOLEAN |  | If true the speed is calculated from position data, otherwise the EIB speed will be used |
| Azimuth | Softmotion Tracking margin acceleration | DOUBLE | % | This acceleration is the margin available acceleration when axis is in tracking mode. This is used by tracking algorithm from the maximum available for tracking/slewing when slewing. |
| Azimuth | Softmotion Tracking margin jerk | DOUBLE | % | This acceleration is the margin available jerk when axis is in tracking mode. This is used by tracking algorithm from the maximum available for tracking/slewing when slewing. |
| Azimuth | Softmotion Tracking margin speed | DOUBLE | % | This acceleration is the margin available jerk when axis is in tracking mode. This is used by tracking algorithm from the maximum available for tracking/slewing when slewing. |
| Azimuth | Softmotion Tracking max acceleration | DOUBLE | deg/s^2 | This acceleration is the maximum available acceleration when axis is in tracking mode. This is used for tracking and slewing combination |
| Azimuth | Softmotion Tracking max jerk | DOUBLE | deg/s^3 | This jerk is the maximum available acceleration when axis is in tracking mode. This is used for tracking and slewing combination |
| Azimuth | Softmotion Tracking max speed | DOUBLE | deg/s | This jerk is the maximum available speed when axis is in tracking mode. This is used for tracking and slewing combination |
| Azimuth | Stabilization Time | DOUBLE | ms | Time to wait after finding references in Homing process |
| Azimuth | Subsystem Path | STRING |  | Defines the subsystem path when an error must be transmitted |
| Azimuth | Timeout for Ack CW | DOUBLE | ms | Timeout for receive and ack from Cable Wrap |
| Azimuth | Timeout for Ack EIB | DOUBLE | ms | Timeout for receive and ack from EIB |
| Azimuth | Timeout for Axis Disable | DOUBLE | ms | Timeout for disable axis and drives in the softmotion axis |
| Azimuth | Timeout for Axis Enable | DOUBLE | ms | Timeout for enable axis and drives in the softmotion axis |
| Azimuth | Timeout for Brake Engage | DOUBLE | ms | Timeout for engaging brakes |
| Azimuth | Timeout for Brake Release | DOUBLE | ms | Timeout for releasing brakes |
| Azimuth | Timeout for Cable Wrap Power Off | DOUBLE | ms | Timeout for power off cable wrap |
| Azimuth | Timeout for Cable Wrap Power On | DOUBLE | ms | Timeout for power on cable wrap |
| Azimuth | Timeout for EnableTracking | DOUBLE | ms | Timeout for enabling the tracking |
| Azimuth | Timeout for Fault Stop | DOUBLE | % | Timeout margin to stop when a fault is detected |
| Azimuth | Timeout for Homming | DOUBLE | ms | Timeout for perform a homing operation |
| Azimuth | Timeout for Power Off | DOUBLE | ms | Timeout for all power off sequence |
| Azimuth | Timeout for Power On | DOUBLE | ms | Timeout for all power on sequence |
| Azimuth | Timeout for Reset | DOUBLE | ms | Timeout for resetting actions |
| Azimuth | Timeout for Reset Axis | DOUBLE | ms | Timeout for resetting axis faults |
| Azimuth | Timeout for Stop | DOUBLE | % | Margin for a standard stop |
| Azimuth | Timeout for Stop in Homing | DOUBLE | % | Timeout margin for stopping homing operation  |
| Azimuth | Timeout Move Margin | DOUBLE | % | Margin for a movement |
| Azimuth | Traking Consecutive tracking command timeout | DOUBLE | ms | After the firs tracking command is received, the time to generate and error if another tracking command is not received |
| Azimuth | Traking First tracking command timeout | DOUBLE | ms | After the enable tracking command is received, the time to generate and error if a tracking command is not received |
| Azimuth | Traking Time offset | DOUBLE | s | Time offset to apply to received command time in tracking command |
| Elevation | Allow Relative Movements | BOOLEAN |  | Allow to move the telescope without doing reference in position mode |
| Elevation | Command Relative Movements | BOOLEAN |  | The move commands will be relative movements if this parameter is true and otherwise absolute movements will be performed |
| Elevation | Control Acceleration FeedForward Gain | DOUBLE | % | Controller Acceleration feedforward gain |
| Elevation | Control Activate Speed FeedForward In Tracking? | BOOLEAN |  | The FeedForward for speed gain will be activated if the axis is in Tracking mode. Otherwise it will be deactivated. The activation will increase according to Control FeedForward Activation Variation settings. See also Control Apply FeedForward? setting |
| Elevation | Control Apply Speed FeedForward? | BOOLEAN |  | If this settings is True the speed feedforward is always active otherwise could be active or not depending on the Control Activate FeedForward In Tracking? setting |
| Elevation | Control Damping Active | BOOLEAN |  | For azimuth axis, activate the active damping control |
| Elevation | Control Damping Max Allowed Force X Direction | DOUBLE | N | The maximum allowed force for active damping control action in X direction. This saturation affects only to active damping. Take into account that active damping action is superposed to rotation control action |
| Elevation | Control Damping Max Allowed Force Y Direction | DOUBLE | N | The maximum allowed force for active damping control action in Y direction. This saturation affects only to active damping. Take into account that active damping action is superposed to rotation control action |
| Elevation | Control Damping X Direction Gain | DOUBLE |  | Active controller gain for  X direction |
| Elevation | Control Damping Y Direction Gain | DOUBLE |  | Active controller gain for  Y direction |
| Elevation | Control Inertia | DOUBLE | kg*m^2 | Inertia of the axis |
| Elevation | Control Integral Disabled | BOOLEAN |  | The integral action of the controller is disabled |
| Elevation | Control Kp (Speed Error Gain) | DOUBLE | rad/s | Speed error gain to use in the controller |
| Elevation | Control Kv (Position Error Gain) | DOUBLE | rad/s | Position error gain to use in the controller |
| Elevation | Control Maximun Torque Variation | DOUBLE | N*m | Maximum allowed torque variation. There is a filter in the controller that allows the value of this settings as maximum change between iterations |
| Elevation | Control Speed FeedForward Activation Variation | DOUBLE |  | The speed feedforward gain will increase this value every iteration until the required value in Control Speed FeedForward setting is achieved. Decrease of the value will be made next iteration and this setting has no effect. |
| Elevation | Control Speed FeedForward Gain | DOUBLE | % | Controller Speed feedforward gain |
| Elevation | Control Ti (Integral time) | DOUBLE | s | Integral time for the controller |
| Elevation | Homing Acceleration | DOUBLE | deg/s^2 | Acceleration for Homing procedure |
| Elevation | Homing Jerk | DOUBLE | deg/s^3 | Jerk for Homing procedure |
| Elevation | Homing Position Direction | DOUBLE | deg | If the actual position is higher than the value in this setting the homing will be performed in negative direction. Otherwise positive direction homing will be done |
| Elevation | Homing Speed | DOUBLE | deg/s | Speed for Homing procedure |
| Elevation | Homing Start in Positive Direction | BOOLEAN |  | If True the start direction will be positive one, otherwise it will try in negative direction first |
| Elevation | Limits Active Drives | DOUBLE |  | Bellow this value the system will send a warning |
| Elevation | Limits Following Error enable | BOOLEAN |  | Enable the following error |
| Elevation | Limits Following Error Value | DOUBLE | deg | Set the maximum allowed following error |
| Elevation | Limits Max Position value | DOUBLE | deg | Maximum allowed position command |
| Elevation | Limits Min Position value | DOUBLE | deg | Minimum allowed position command |
| Elevation | Limits Negative Adjustable Software limit value | DOUBLE | deg | Value for Negative adjustable software limit.  This limit will be valid if it is enabled independent if the axis may move in relative mode |
| Elevation | Limits Negative Software limit value | DOUBLE | deg | Value for negative software limit.  This limit will be valid if it is enabled independent if the axis may move in relative mode |
| Elevation | Limits Overspeed enable | BOOLEAN | deg/s | Enable the overspeed limit, does not affect the warning. |
| Elevation | Limits Overspeed Value | DOUBLE | deg/s | If this speed value is overcomed an the critical speed limit alarm will be triggered. |
| Elevation | Limits Positive Adjustable Software limit value | DOUBLE | deg | Value for Positive adjustable software limit.  This limit will be valid if it is enabled independent if the axis may move in relative mode |
| Elevation | Limits Positive Software limit value | DOUBLE | deg | Value for Positive software limit.  This limit will be valid if it is enabled independent if the axis may move in relative mode |
| Elevation | Limits Softmotion Negative Software limit value | DOUBLE | deg | Value for softmotion Positive software limit.  Bellow this limit the axis does not allow any movement. This limit must allow all desired movements, also maintenance movements to safety limits |
| Elevation | Limits Softmotion Positive Software limit value | DOUBLE | deg | Value for softmotion Positive software limit.  Over this limit the axis does not allow any movement. This limit must allow all desired movements, also maintenance movements to safety limits |
| Elevation | Observer Ad | STRING |  | A matrix for the position/speed observer. It is a matrix, use "," to separate columns and "_" to add rows |
| Elevation | Observer Bd | STRING |  | B matrix for the position/speed observer. It is a matrix, use "," to separate columns and "_" to add rows |
| Elevation | Observer K | STRING |  | K matrix for the position/speed observer. It is a matrix, use "," to separate columns and "_" to add rows |
| Elevation | Observer MaxAllowedError | DOUBLE | rad | Maximum allowed deviation from the real position to consider the observer as stable. Over this deviation the observer will not be used if the data from the encoder is missing and an extrapolation from the last valid position and speed will be used. |
| Elevation | OVERRIDE Default Acceleration | DOUBLE | deg/s^2 | Default acceleration when a safety override of limit switches is active |
| Elevation | OVERRIDE Default Jerk | DOUBLE | deg/s^3 | Default jerk when a safety override of limit switches is active |
| Elevation | OVERRIDE Default Velocity | DOUBLE | deg/s | Default velocity when a safety limit switch is overrided |
| Elevation | OVERRIDE Max Acceleration | DOUBLE | deg/s^2 | Maximum allowed acceleration when a safety override of limit switches is active |
| Elevation | OVERRIDE Max Jerk | DOUBLE | deg/s^3 | Maximum jerk when a safety override of limit switches is active |
| Elevation | OVERRIDE Max Velocity | DOUBLE | deg/s | Maximum allowed velocity when a safety limit switch is overrided |
| Elevation | Position readings when homming | DOUBLE |  | This value will manage the times data is get from AxesPXI to calculate the actual absolute position. Each reading is a packet of 50 elements. More data makes the mean more insensitive to noise effect. |
| Elevation | Softmotion Error Stop acceleration | DOUBLE | deg/s^2 | This acceleration will be applied when the softmotion axis detects a fault, like overspeed or following error |
| Elevation | Softmotion Error Stop jerk | DOUBLE | deg/s^3 | This jerk will be applied when the softmotion axis detects a fault, like overspeed or following error |
| Elevation | Softmotion In position buffer size | DOUBLE |  | This value manage the buffer size to calculate the position rms value that is used for In position event |
| Elevation | Softmotion In position Hysteresis | DOUBLE | deg | This value added to the Softmotion In position Margin determines when the in position is set to false |
| Elevation | Softmotion In position Margin | DOUBLE | deg | This value will indicate when the softmotion axis indicates that the axis in desired position |
| Elevation | Softmotion max acceleration | DOUBLE | deg/s^2 | This acceleration is the maximum available acceleration for the axis. |
| Elevation | Softmotion max jerk | DOUBLE | deg/s^3 | This jerk is the maximum available jerk for the axis. |
| Elevation | Softmotion max speed | DOUBLE | deg/s | This speed is the maximum available speed for the axis. |
| Elevation | Softmotion Maximum Torque Per Drive | DOUBLE | Nm | The maximum allowed torque per drive. The system will not allow that command to each drive goes over this value |
| Elevation | Softmotion Minimun drives for no fault | DOUBLE |  | Bellow this limit the axis will be in fault |
| Elevation | Softmotion No received Data Counter Alarm Value | DOUBLE |  | Above this number the  softmotion driver is in fault. Its time, no new data is received from encoder an internal counter increases its value by 1000, decreasing by 1 each no problem iteration |
| Elevation | Softmotion No received Data Counter Warning Value | DOUBLE |  | Above this number the softmotion driver send a warning. Its time, no new data is received from encoder an internal counter increases its value by 1000, decreasing by 1 each no problem iteration |
| Elevation | Softmotion Number of Electric Turns | DOUBLE |  | Number of electric turns in for the axis. This is the number of poles |
| Elevation | Softmotion Speed From Position | BOOLEAN |  | If true the speed is calculated from position data, otherwise the EIB speed will be used |
| Elevation | Softmotion Tracking margin acceleration | DOUBLE | % | This acceleration is the margin available acceleration when axis is in tracking mode. This is used by tracking algorithm from the maximum available for tracking/slewing when slewing. |
| Elevation | Softmotion Tracking margin jerk | DOUBLE | % | This acceleration is the margin available jerk when axis is in tracking mode. This is used by tracking algorithm from the maximum available for tracking/slewing when slewing. |
| Elevation | Softmotion Tracking margin speed | DOUBLE | % | This acceleration is the margin available jerk when axis is in tracking mode. This is used by tracking algorithm from the maximum available for tracking/slewing when slewing. |
| Elevation | Softmotion Tracking max acceleration | DOUBLE | deg/s^2 | This acceleration is the maximum available acceleration when axis is in tracking mode. This is used for tracking and slewing combination |
| Elevation | Softmotion Tracking max jerk | DOUBLE | deg/s^3 | This jerk is the maximum available acceleration when axis is in tracking mode. This is used for tracking and slewing combination |
| Elevation | Softmotion Tracking max speed | DOUBLE | deg/s | This jerk is the maximum available speed when axis is in tracking mode. This is used for tracking and slewing combination |
| Elevation | Stabilization Time | DOUBLE | ms | Time to wait after finding references in Homing process |
| Elevation | Subsystem Path | STRING |  | Defines the subsystem path when an error must be transmitted |
| Elevation | Timeout for Ack CW | DOUBLE | ms | Timeout for receive and ack from Cable Wrap |
| Elevation | Timeout for Ack EIB | DOUBLE | ms | Timeout for receive and ack from EIB |
| Elevation | Timeout for Axis Disable | DOUBLE | ms | Timeout for disable axis and drives in the softmotion axis |
| Elevation | Timeout for Axis Enable | DOUBLE | ms | Timeout for enable axis and drives in the softmotion axis |
| Elevation | Timeout for Brake Engage | DOUBLE | ms | Timeout for engaging brakes |
| Elevation | Timeout for Brake Release | DOUBLE | ms | Timeout for releasing brakes |
| Elevation | Timeout for Cable Wrap Power Off | DOUBLE | ms | Timeout for power off cable wrap |
| Elevation | Timeout for Cable Wrap Power On | DOUBLE | ms | Timeout for power on cable wrap |
| Elevation | Timeout for EnableTracking | DOUBLE | ms | Timeout for enabling the tracking |
| Elevation | Timeout for Fault Stop | DOUBLE | % | Timeout margin to stop when a fault is detected |
| Elevation | Timeout for Homming | DOUBLE | ms | Timeout for perform a homing operation |
| Elevation | Timeout for Power Off | DOUBLE | ms | Timeout for all power off sequence |
| Elevation | Timeout for Power On | DOUBLE | ms | Timeout for all power on sequence |
| Elevation | Timeout for Reset | DOUBLE | ms | Timeout for resetting actions |
| Elevation | Timeout for Reset Axis | DOUBLE | ms | Timeout for resetting axis faults |
| Elevation | Timeout for Stop | DOUBLE | % | Margin for a standard stop |
| Elevation | Timeout for Stop in Homing | DOUBLE | % | Timeout margin for stopping homing operation  |
| Elevation | Timeout Move Margin | DOUBLE | % | Margin for a movement |
| Elevation | Traking Consecutive tracking command timeout | DOUBLE | ms | After the firs tracking command is received, the time to generate and error if another tracking command is not received |
| Elevation | Traking First tracking command timeout | DOUBLE | ms | After the enable tracking command is received, the time to generate and error if a tracking command is not received |
| Elevation | Traking Time offset | DOUBLE | s | Time offset to apply to received command time in tracking command |
| General | Horn Time (s) | DOUBLE | s | Time that the horn will be sounding |
| General | Inclinometer Gain | DOUBLE | deg/V | Gain to calculate deg from V input |
| General | Inclinometer Mean Samples Number | DOUBLE |  | The number of samples used to calculate a mean with the inclinometer analog input |
| General | Inclinometer Offset | DOUBLE | deg | Offset to apply to the inclinometer after applying the gain to the analog input |
| General | Light Time (s) | DOUBLE | s | Time that the light will be lighting |
| General | TimeToCheckActiveAlarms | DOUBLE | ms | TimeToCheckActiveAlarms |

##### MainAxisSoftMotion

###### General Access Setting list

There are no settings under this section.

##### MainCabinetTemperature

###### General Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| MainCabinet | High Cabinet Temperature | DOUBLE | degC | Temperature causing a warning. |
| MainCabinet | High Surface Temperature | DOUBLE | degC | The difference between ambient temperature and surface temperature is above the allowed one |
| MainCabinet | Low Cabinet Temperature | DOUBLE | degC | Temperature causing a warning. |
| MainCabinet | Low Surface Temperature | DOUBLE | degC | The difference between ambient temperature and surface temperature is bellow the allowed one |
| MainCabinet | Lower Limit Hysteresis Relative | DOUBLE | degC | This is the lower temperature limit  relative to the ambient temperature for the hysteresis control used when RMC is not working |

###### Restricted Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| General | TimeToCheckActiveAlarms | DOUBLE | ms | TimeToCheckActiveAlarms |
| MainCabinet | Commands to update settings | DOUBLE |  | When the number of commands to track ambient temperature set in this settings is received by the task, the settings will be updated |
| MainCabinet | Critical High Cabinet Temperature | DOUBLE | degC | This is the temperature at which an alarm is triggered. |
| MainCabinet | Critical Low Cabinet Temperature | DOUBLE | degC | This is the temperature at which an alarm is triggered. |
| MainCabinet | DefaultSetpoint | DOUBLE | degC | The setpoint sent when initializing, exiting and when going to fault in the Cabinet OMT. |
| MainCabinet | HighCabinetTemperatureHysteresis | DOUBLE | degC | Hysteresis value for temperature causing a warning. |
| MainCabinet | ID String | STRING |  | This is not used for this subsystem, is kept for consistency. |
| MainCabinet | IP address | STRING |  | This is the IP address of the RMC for the modbus connection. |
| MainCabinet | Maximum Setpoint Temperature | DOUBLE | degC | Maximum allowed temperature for setpoint |
| MainCabinet | Minimum Setpoint Temperature | DOUBLE | degC | Minimum allowed temperature for setpoint |
| MainCabinet | port | DOUBLE |  | This is the connection port for the modbus of the RMC. |
| MainCabinet | Special Error Lower Limit | DOUBLE |  | The error numbers between this setting and the Special Error Upper Limit will trigger the special fault in the main cabinet statechart. This special fault will trigger a fault in all subsystem to prepare for a possible cabinet switch off. |
| MainCabinet | Special Error Upper Limit | DOUBLE |  | The error numbers between this setting and the Special Error Lower Limit will trigger the special fault in the main cabinet statechart. This special fault will trigger a fault in all subsystem to prepare for a possible cabinet switch off. |
| MainCabinet | SystemSource | STRING |  | This is the identifier for the system used when publishing the Alarm source. |
| MainCabinet | Upper Limit Hysteresis Relative | DOUBLE | degC | This is the upper temperature limit  relative to the ambient temperature for the hysteresis control used when RMC is not working |

##### MainPowerSupply

###### General Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| MainPowerSupply | MaxCurrentWarning | DOUBLE | A | This is the maximum allowed current, above this value a warning is sent. |
| MainPowerSupply | MinVoltageWarning | DOUBLE | V | This is the minimum allowed voltage, bellow this value a warning is sent. |

###### Restricted Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| General | SystemSource | STRING |  | This is the identifier for the system used when publishing the Alarm source. |
| General | TimeToCheckActiveAlarms | DOUBLE | ms | TimeToCheckActiveAlarms |
| MainPowerSupply | CW Power Off | DOUBLE |  | Control Word value for powering off the MPS |
| MainPowerSupply | CW Power On | DOUBLE |  | Control Word value for powering on the MPS |
| MainPowerSupply | CW Reset | DOUBLE |  | Control Word value for resetting the error of the MPS |
| MainPowerSupply | MaxCurrent | DOUBLE | A | This is the maximum allowed current, above this value an alarm is sent. |
| MainPowerSupply | MaxPowerOnVoltage | DOUBLE | V | This is the maximum allowed voltage for enabling power on, if the voltage is above this value the power on command in idle is rejected. |
| MainPowerSupply | MinVoltage | DOUBLE | V | This is the minimum allowed voltage, bellow this value an alarm is sent. |
| MainPowerSupply | Powering time out | DOUBLE | ms | Timeout of the powering process |
| MainPowerSupply | Reseting time | DOUBLE | ms | Waiting time between the MPS reset and clearing faults |
| MainPowerSupply | Wait Power Off In Fault | DOUBLE | ms | Time to wait before sending switch off to Power supply |

##### MirrorCover

###### General Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| MC1 | ID String | STRING |  | This is the identifier for the cover in string format. |
| MC1 | Motor Velocity | DOUBLE | deg/s | The motor velocity at which sequences are executed. |
| MC2 | ID String | STRING |  | This is the identifier for the cover in string format. |
| MC2 | Motor Velocity | DOUBLE | deg/s | The motor velocity at which sequences are executed. |
| MC3 | ID String | STRING |  | This is the identifier for the cover in string format. |
| MC3 | Motor Velocity | DOUBLE | deg/s | The motor velocity at which sequences are executed. |
| MC4 | ID String | STRING |  | This is the identifier for the cover in string format. |
| MC4 | Motor Velocity | DOUBLE | deg/s | The motor velocity at which sequences are executed. |

###### Restricted Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| General | MinElevationPosition | DOUBLE | deg | Minimum Elevation Position for the mirror cover to close. |
| General | SystemSource | STRING |  | This is the identifier for the system used when publishing the Alarm source. |
| General | TimeToCheckActiveAlarms | DOUBLE | ms | TimeToCheckActiveAlarms |
| General | WaitTrans_Timeout | DOUBLE | ms | Wait transition timeout |
| MC1 | Critical Max Motor Velocity | DOUBLE | deg/s | The motor velocity at which an alarm is triggered. |
| MC1 | Deployed Position | DOUBLE | deg | The deployed position. |
| MC1 | DisableColisionCheck | BOOLEAN |  | WARNING! This setting is used to disable the collision check (value TRUE), use only when something is wrong. Otherwise leave it to FALSE. |
| MC1 | Error ID | STRING |  | Error id of the current instance. |
| MC1 | IDStringsToCheck | STRING |  | Here specify the ID Strings to search when guard executed. (separated by ","). |
| MC1 | InRangeMargin | DOUBLE | deg | This is the value used to verify that the mirror cover is deployed or retracted. |
| MC1 | IsOnTop | BOOLEAN |  | This setting is used to know if this MC is on top or not. This is used in the guard. |
| MC1 | Jog Speed | DOUBLE | deg/s | The motor speed used when jog 100 percent is used. |
| MC1 | Max Angle Position | DOUBLE | deg | The maximum angle position of the motor. |
| MC1 | Max Speed | DOUBLE | deg/s | The maximum speed of the motor, if the speed is greater than this the command is rejected. |
| MC1 | Min Angle Position | DOUBLE | deg | The minimum angle position of the motor. |
| MC1 | Motor Acceleration | DOUBLE | deg/s^2 | The acceleration of the motor. |
| MC1 | Motor Deceleration | DOUBLE |  deg/s^2 | The deceleration of the motor. |
| MC1 | Motor ID | DOUBLE |  | ID of the instances motor. |
| MC1 | Motor Jerk | DOUBLE |  deg/s^3 | The jerk of the motor. |
| MC1 | Motor Max Velocity | DOUBLE | deg/s | The motor velocity at which a warning is triggered. |
| MC1 | MoveVelocity_Trns_TimeOut | DOUBLE | ms | Timeout for Move Velocity commands. Negative numbers means no timeout. |
| MC1 | Move_Trans_TimeMargin | DOUBLE | % | Margin to apply to calculation time for specified movement before a timeout error occurs |
| MC1 | OffTrans_Timeout | DOUBLE | ms | Power off transition timeout |
| MC1 | OnTrans_Timeout | DOUBLE | ms | Power on transition timeout |
| MC1 | OpenOrder | BOOLEAN |  | This parameter indicates if this MC is one of the first MC to open. If true goes first, if false goes second |
| MC1 | ResettingTime | DOUBLE | ms | Timeout for the reset transition. |
| MC1 | Retracted Position | DOUBLE | deg | The retracted position. |
| MC1 | StopTrans_Timeout | DOUBLE | ms | Maximum time allowed for a stop command |
| MC1 | WaitAfterReset | DOUBLE | ms | Time to wait after a reset to go to idle |
| MC2 | Critical Max Motor Velocity | DOUBLE | deg/s | The motor velocity at which an alarm is triggered. |
| MC2 | Deployed Position | DOUBLE | deg | The deployed position. |
| MC2 | DisableColisionCheck | BOOLEAN |  | WARNING! This setting is used to disable the collision check (value TRUE), use only when something is wrong. Otherwise leave it to FALSE. |
| MC2 | Error ID | STRING |  | Error id of the current instance. |
| MC2 | IDStringsToCheck | STRING |  | Here specify the ID Strings to search when guard executed. (separated by ","). |
| MC2 | InRangeMargin | DOUBLE | deg | This is the value used to verify that the mirror cover is deployed or retracted. |
| MC2 | IsOnTop | BOOLEAN |  | This setting is used to know if this MC is on top or not. This is used in the guard. |
| MC2 | Jog Speed | DOUBLE | deg/s | The motor speed used when jog 100 percent is used. |
| MC2 | Max Angle Position | DOUBLE | deg | The maximum angle position of the motor. |
| MC2 | Max Speed | DOUBLE | deg/s | The maximum speed of the motor, if the speed is greater than this the command is rejected. |
| MC2 | Min Angle Position | DOUBLE | deg | The minimum angle position of the motor. |
| MC2 | Motor Acceleration | DOUBLE | deg/s^2 | The acceleration of the motor. |
| MC2 | Motor Deceleration | DOUBLE |  deg/s^2 | The deceleration of the motor. |
| MC2 | Motor ID | DOUBLE |  | ID of the instances motor. |
| MC2 | Motor Jerk | DOUBLE |  deg/s^3 | The jerk of the motor. |
| MC2 | Motor Max Velocity | DOUBLE | deg/s | The motor velocity at which a warning is triggered. |
| MC2 | MoveVelocity_Trns_TimeOut | DOUBLE | ms | Timeout for Move Velocity commands. Negative numbers means no timeout. |
| MC2 | Move_Trans_TimeMargin | DOUBLE | % | Margin to apply to calculation time for specified movement before a timeout error occurs |
| MC2 | OffTrans_Timeout | DOUBLE | ms | Power off transition timeout |
| MC2 | OnTrans_Timeout | DOUBLE | ms | Power on transition timeout |
| MC2 | OpenOrder | BOOLEAN |  | This parameter indicates if this MC is one of the first MC to open. If true goes first, if false goes second |
| MC2 | ResettingTime | DOUBLE | ms | Timeout for the reset transition. |
| MC2 | Retracted Position | DOUBLE | deg | The retracted position. |
| MC2 | StopTrans_Timeout | DOUBLE | ms | Maximum time allowed for a stop command |
| MC2 | WaitAfterReset | DOUBLE | ms | Time to wait after a reset to go to idle |
| MC3 | Critical Max Motor Velocity | DOUBLE | deg/s | The motor velocity at which an alarm is triggered. |
| MC3 | Deployed Position | DOUBLE | deg | The deployed position. |
| MC3 | DisableColisionCheck | BOOLEAN |  | WARNING! This setting is used to disable the collision check (value TRUE), use only when something is wrong. Otherwise leave it to FALSE. |
| MC3 | Error ID | STRING |  | Error id of the current instance. |
| MC3 | IDStringsToCheck | STRING |  | Here specify the ID Strings to search when guard executed. (separated by ","). |
| MC3 | InRangeMargin | DOUBLE | deg | This is the value used to verify that the mirror cover is deployed or retracted. |
| MC3 | IsOnTop | BOOLEAN |  | This setting is used to know if this MC is on top or not. This is used in the guard. |
| MC3 | Jog Speed | DOUBLE | deg/s | The motor speed used when jog 100 percent is used. |
| MC3 | Max Angle Position | DOUBLE | deg | The maximum angle position of the motor. |
| MC3 | Max Speed | DOUBLE | deg/s | The maximum speed of the motor, if the speed is greater than this the command is rejected. |
| MC3 | Min Angle Position | DOUBLE | deg | The minimum angle position of the motor. |
| MC3 | Motor Acceleration | DOUBLE | deg/s^2 | The acceleration of the motor. |
| MC3 | Motor Deceleration | DOUBLE |  deg/s^2 | The deceleration of the motor. |
| MC3 | Motor ID | DOUBLE |  | ID of the instances motor. |
| MC3 | Motor Jerk | DOUBLE |  deg/s^3 | The jerk of the motor. |
| MC3 | Motor Max Velocity | DOUBLE | deg/s | The motor velocity at which a warning is triggered. |
| MC3 | MoveVelocity_Trns_TimeOut | DOUBLE | ms | Timeout for Move Velocity commands. Negative numbers means no timeout. |
| MC3 | Move_Trans_TimeMargin | DOUBLE | % | Margin to apply to calculation time for specified movement before a timeout error occurs |
| MC3 | OffTrans_Timeout | DOUBLE | ms | Power off transition timeout |
| MC3 | OnTrans_Timeout | DOUBLE | ms | Power on transition timeout |
| MC3 | OpenOrder | BOOLEAN |  | This parameter indicates if this MC is one of the first MC to open. If true goes first, if false goes second |
| MC3 | ResettingTime | DOUBLE | ms | Timeout for the reset transition. |
| MC3 | Retracted Position | DOUBLE | deg | The retracted position. |
| MC3 | StopTrans_Timeout | DOUBLE | ms | Maximum time allowed for a stop command |
| MC3 | WaitAfterReset | DOUBLE | ms | Time to wait after a reset to go to idle |
| MC4 | Critical Max Motor Velocity | DOUBLE | deg/s | The motor velocity at which an alarm is triggered. |
| MC4 | Deployed Position | DOUBLE | deg | The deployed position. |
| MC4 | DisableColisionCheck | BOOLEAN |  | WARNING! This setting is used to disable the collision check (value TRUE), use only when something is wrong. Otherwise leave it to FALSE. |
| MC4 | Error ID | STRING |  | Error id of the current instance. |
| MC4 | IDStringsToCheck | STRING |  | Here specify the ID Strings to search when guard executed. (separated by ","). |
| MC4 | InRangeMargin | DOUBLE | deg | This is the value used to verify that the mirror cover is deployed or retracted. |
| MC4 | IsOnTop | BOOLEAN |  | This setting is used to know if this MC is on top or not. This is used in the guard. |
| MC4 | Jog Speed | DOUBLE | deg/s | The motor speed used when jog 100 percent is used. |
| MC4 | Max Angle Position | DOUBLE | deg | The maximum angle position of the motor. |
| MC4 | Max Speed | DOUBLE | deg/s | The maximum speed of the motor, if the speed is greater than this the command is rejected. |
| MC4 | Min Angle Position | DOUBLE | deg | The minimum angle position of the motor. |
| MC4 | Motor Acceleration | DOUBLE | deg/s^2 | The acceleration of the motor. |
| MC4 | Motor Deceleration | DOUBLE |  deg/s^2 | The deceleration of the motor. |
| MC4 | Motor ID | DOUBLE |  | ID of the instances motor. |
| MC4 | Motor Jerk | DOUBLE |  deg/s^3 | The jerk of the motor. |
| MC4 | Motor Max Velocity | DOUBLE | deg/s | The motor velocity at which a warning is triggered. |
| MC4 | MoveVelocity_Trns_TimeOut | DOUBLE | ms | Timeout for Move Velocity commands. Negative numbers means no timeout. |
| MC4 | Move_Trans_TimeMargin | DOUBLE | % | Margin to apply to calculation time for specified movement before a timeout error occurs |
| MC4 | OffTrans_Timeout | DOUBLE | ms | Power off transition timeout |
| MC4 | OnTrans_Timeout | DOUBLE | ms | Power on transition timeout |
| MC4 | OpenOrder | BOOLEAN |  | This parameter indicates if this MC is one of the first MC to open. If true goes first, if false goes second |
| MC4 | ResettingTime | DOUBLE | ms | Timeout for the reset transition. |
| MC4 | Retracted Position | DOUBLE | deg | The retracted position. |
| MC4 | StopTrans_Timeout | DOUBLE | ms | Maximum time allowed for a stop command |
| MC4 | WaitAfterReset | DOUBLE | ms | Time to wait after a reset to go to idle |

##### MirrorCoverLocks

###### General Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| MCL1 | ID String | STRING |  | This is the identifier for the cover in string format. |
| MCL1 | Motor Velocity | DOUBLE | deg/s | The motor velocity at which sequences are executed. |
| MCL2 | ID String | STRING |  | This is the identifier for the cover in string format. |
| MCL2 | Motor Velocity | DOUBLE | deg/s | The motor velocity at which sequences are executed. |
| MCL3 | ID String | STRING |  | This is the identifier for the cover in string format. |
| MCL3 | Motor Velocity | DOUBLE | deg/s | The motor velocity at which sequences are executed. |
| MCL4 | ID String | STRING |  | This is the identifier for the cover in string format. |
| MCL4 | Motor Velocity | DOUBLE | deg/s | The motor velocity at which sequences are executed. |

###### Restricted Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| General | SystemSource | STRING |  | This is the identifier for the system used when publishing the Alarm source. |
| General | TimeToCheckActiveAlarms | DOUBLE | ms | TimeToCheckActiveAlarms |
| MCL1 | Critical Max Motor Velocity | DOUBLE | deg/s | The motor velocity at which an alarm is triggered. |
| MCL1 | DisableColisionCheck | BOOLEAN |  | WARNING! This setting is used to disable the collision check (value TRUE), use only when something is wrong. Otherwise leave it to FALSE. |
| MCL1 | Error ID | STRING |  | Error id of the current instance. |
| MCL1 | IDStringsToCheck | STRING |  | Here specify the ID Strings to search when guard executed. (separated by ","). |
| MCL1 | InRangeMargin | DOUBLE | deg | This is the value used to verify that the mirror cover is deployed or retracted. |
| MCL1 | Jog Speed | DOUBLE | deg/s | The motor speed used when jog 100 percent is used. |
| MCL1 | Locked Position | DOUBLE | deg | The locked position. |
| MCL1 | Max Angle Position | DOUBLE | deg | The maximum angle position of the motor. |
| MCL1 | Max Speed | DOUBLE | deg/s | The maximum speed of the motor, if the speed is greater than this the command is rejected. |
| MCL1 | Min Angle Position | DOUBLE | deg | The minimum angle position of the motor. |
| MCL1 | Motor Acceleration | DOUBLE | deg/s^2 | The acceleration of the motor. |
| MCL1 | Motor Deceleration | DOUBLE |  deg/s^2 | The deceleration of the motor. |
| MCL1 | Motor ID | DOUBLE |  | ID of the instances motor. |
| MCL1 | Motor Jerk | DOUBLE |  deg/s^3 | The jerk of the motor. |
| MCL1 | Motor Max Velocity | DOUBLE | deg/s | The motor velocity at which a warning is triggered. |
| MCL1 | MoveVelocity_Trns_TimeOut | DOUBLE | ms | Timeout for Move Velocity commands. Negative numbers means no timeout. |
| MCL1 | Move_Trans_TimeMargin | DOUBLE | % | Margin to apply to calculation time for specified movement before a timeout error occurs |
| MCL1 | OffTrans_Timeout | DOUBLE | ms | Power off transition timeout |
| MCL1 | OnTrans_Timeout | DOUBLE | ms | Power on transition timeout |
| MCL1 | ResettingTime | DOUBLE | ms | Timeout for the reset transition. |
| MCL1 | StopTrans_Timeout | DOUBLE | ms | Maximum time allowed for a stop command |
| MCL1 | Unlocked Position | DOUBLE | deg | The unlocked position. |
| MCL1 | WaitAfterReset | DOUBLE | ms | Time to wait after a reset to go to idle |
| MCL2 | Critical Max Motor Velocity | DOUBLE | deg/s | The motor velocity at which an alarm is triggered. |
| MCL2 | DisableColisionCheck | BOOLEAN |  | WARNING! This setting is used to disable the collision check (value TRUE), use only when something is wrong. Otherwise leave it to FALSE. |
| MCL2 | Error ID | STRING |  | Error id of the current instance. |
| MCL2 | IDStringsToCheck | STRING |  | Here specify the ID Strings to search when guard executed. (separated by ","). |
| MCL2 | InRangeMargin | DOUBLE | deg | This is the value used to verify that the mirror cover is deployed or retracted. |
| MCL2 | Jog Speed | DOUBLE | deg/s | The motor speed used when jog 100 percent is used. |
| MCL2 | Locked Position | DOUBLE | deg | The locked position. |
| MCL2 | Max Angle Position | DOUBLE | deg | The maximum angle position of the motor. |
| MCL2 | Max Speed | DOUBLE | deg/s | The maximum speed of the motor, if the speed is greater than this the command is rejected. |
| MCL2 | Min Angle Position | DOUBLE | deg | The minimum angle position of the motor. |
| MCL2 | Motor Acceleration | DOUBLE | deg/s^2 | The acceleration of the motor. |
| MCL2 | Motor Deceleration | DOUBLE |  deg/s^2 | The deceleration of the motor. |
| MCL2 | Motor ID | DOUBLE |  | ID of the instances motor. |
| MCL2 | Motor Jerk | DOUBLE |  deg/s^3 | The jerk of the motor. |
| MCL2 | Motor Max Velocity | DOUBLE | deg/s | The motor velocity at which a warning is triggered. |
| MCL2 | MoveVelocity_Trns_TimeOut | DOUBLE | ms | Timeout for Move Velocity commands. Negative numbers means no timeout. |
| MCL2 | Move_Trans_TimeMargin | DOUBLE | % | Margin to apply to calculation time for specified movement before a timeout error occurs |
| MCL2 | OffTrans_Timeout | DOUBLE | ms | Power off transition timeout |
| MCL2 | OnTrans_Timeout | DOUBLE | ms | Power on transition timeout |
| MCL2 | ResettingTime | DOUBLE | ms | Timeout for the reset transition. |
| MCL2 | StopTrans_Timeout | DOUBLE | ms | Maximum time allowed for a stop command |
| MCL2 | Unlocked Position | DOUBLE | deg | The unlocked position. |
| MCL2 | WaitAfterReset | DOUBLE | ms | Time to wait after a reset to go to idle |
| MCL3 | Critical Max Motor Velocity | DOUBLE | deg/s | The motor velocity at which an alarm is triggered. |
| MCL3 | DisableColisionCheck | BOOLEAN |  | WARNING! This setting is used to disable the collision check (value TRUE), use only when something is wrong. Otherwise leave it to FALSE. |
| MCL3 | Error ID | STRING |  | Error id of the current instance. |
| MCL3 | IDStringsToCheck | STRING |  | Here specify the ID Strings to search when guard executed. (separated by ","). |
| MCL3 | InRangeMargin | DOUBLE | deg | This is the value used to verify that the mirror cover is deployed or retracted. |
| MCL3 | Jog Speed | DOUBLE | deg/s | The motor speed used when jog 100 percent is used. |
| MCL3 | Locked Position | DOUBLE | deg | The locked position. |
| MCL3 | Max Angle Position | DOUBLE | deg | The maximum angle position of the motor. |
| MCL3 | Max Speed | DOUBLE | deg/s | The maximum speed of the motor, if the speed is greater than this the command is rejected. |
| MCL3 | Min Angle Position | DOUBLE | deg | The minimum angle position of the motor. |
| MCL3 | Motor Acceleration | DOUBLE | deg/s^2 | The acceleration of the motor. |
| MCL3 | Motor Deceleration | DOUBLE |  deg/s^2 | The deceleration of the motor. |
| MCL3 | Motor ID | DOUBLE |  | ID of the instances motor. |
| MCL3 | Motor Jerk | DOUBLE |  deg/s^3 | The jerk of the motor. |
| MCL3 | Motor Max Velocity | DOUBLE | deg/s | The motor velocity at which a warning is triggered. |
| MCL3 | MoveVelocity_Trns_TimeOut | DOUBLE | ms | Timeout for Move Velocity commands. Negative numbers means no timeout. |
| MCL3 | Move_Trans_TimeMargin | DOUBLE | % | Margin to apply to calculation time for specified movement before a timeout error occurs |
| MCL3 | OffTrans_Timeout | DOUBLE | ms | Power off transition timeout |
| MCL3 | OnTrans_Timeout | DOUBLE | ms | Power on transition timeout |
| MCL3 | ResettingTime | DOUBLE | ms | Timeout for the reset transition. |
| MCL3 | StopTrans_Timeout | DOUBLE | ms | Maximum time allowed for a stop command |
| MCL3 | Unlocked Position | DOUBLE | deg | The unlocked position. |
| MCL3 | WaitAfterReset | DOUBLE | ms | Time to wait after a reset to go to idle |
| MCL4 | Critical Max Motor Velocity | DOUBLE | deg/s | The motor velocity at which an alarm is triggered. |
| MCL4 | DisableColisionCheck | BOOLEAN |  | WARNING! This setting is used to disable the collision check (value TRUE), use only when something is wrong. Otherwise leave it to FALSE. |
| MCL4 | Error ID | STRING |  | Error id of the current instance. |
| MCL4 | IDStringsToCheck | STRING |  | Here specify the ID Strings to search when guard executed. (separated by ","). |
| MCL4 | InRangeMargin | DOUBLE | deg | This is the value used to verify that the mirror cover is deployed or retracted. |
| MCL4 | Jog Speed | DOUBLE | deg/s | The motor speed used when jog 100 percent is used. |
| MCL4 | Locked Position | DOUBLE | deg | The locked position. |
| MCL4 | Max Angle Position | DOUBLE | deg | The maximum angle position of the motor. |
| MCL4 | Max Speed | DOUBLE | deg/s | The maximum speed of the motor, if the speed is greater than this the command is rejected. |
| MCL4 | Min Angle Position | DOUBLE | deg | The minimum angle position of the motor. |
| MCL4 | Motor Acceleration | DOUBLE | deg/s^2 | The acceleration of the motor. |
| MCL4 | Motor Deceleration | DOUBLE |  deg/s^2 | The deceleration of the motor. |
| MCL4 | Motor ID | DOUBLE |  | ID of the instances motor. |
| MCL4 | Motor Jerk | DOUBLE |  deg/s^3 | The jerk of the motor. |
| MCL4 | Motor Max Velocity | DOUBLE | deg/s | The motor velocity at which a warning is triggered. |
| MCL4 | MoveVelocity_Trns_TimeOut | DOUBLE | ms | Timeout for Move Velocity commands. Negative numbers means no timeout. |
| MCL4 | Move_Trans_TimeMargin | DOUBLE | % | Margin to apply to calculation time for specified movement before a timeout error occurs |
| MCL4 | OffTrans_Timeout | DOUBLE | ms | Power off transition timeout |
| MCL4 | OnTrans_Timeout | DOUBLE | ms | Power on transition timeout |
| MCL4 | ResettingTime | DOUBLE | ms | Timeout for the reset transition. |
| MCL4 | StopTrans_Timeout | DOUBLE | ms | Maximum time allowed for a stop command |
| MCL4 | Unlocked Position | DOUBLE | deg | The unlocked position. |
| MCL4 | WaitAfterReset | DOUBLE | ms | Time to wait after a reset to go to idle |

##### ModbusTemperatureControllers

###### General Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| TMA_AX_DZ_CBT_0001 | DisableController | BOOLEAN |  | This setting is used  to disable the code for this temperature controller. A reboot of the PXI is necessary to apply this setting |
| TMA_AX_DZ_CBT_0001 | ID String | STRING |  | This is the identifier for the cabinet in string format. |
| TMA_AX_DZ_CBT_0001 | SetpointOffset | DOUBLE | degC | This value is added to the setpoint set to the modbus controller. |
| TMA_AX_DZ_CBT_0001 | TemperatureDeviationAlarm | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooHigh alarm is sent, the difference must be positive for being an overtemperature. |
| TMA_AX_DZ_CBT_0001 | TemperatureDeviationWarning | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooLow warning is sent, the difference must be negative for being an under temperature. |
| TMA_AZ_PD_CBT_0001 | DisableController | BOOLEAN |  | This setting is used  to disable the code for this temperature controller. A reboot of the PXI is necessary to apply this setting |
| TMA_AZ_PD_CBT_0001 | ID String | STRING |  | This is the identifier for the cabinet in string format. |
| TMA_AZ_PD_CBT_0001 | SetpointOffset | DOUBLE | degC | This value is added to the setpoint set to the modbus controller. |
| TMA_AZ_PD_CBT_0001 | TemperatureDeviationAlarm | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooHigh alarm is sent, the difference must be positive for being an overtemperature. |
| TMA_AZ_PD_CBT_0001 | TemperatureDeviationWarning | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooLow warning is sent, the difference must be negative for being an under temperature. |
| TMA_AZ_PD_TRM_0001 | DisableController | BOOLEAN |  | This setting is used  to disable the code for this temperature controller. A reboot of the PXI is necessary to apply this setting |
| TMA_AZ_PD_TRM_0001 | ID String | STRING |  | This is the identifier for the cabinet in string format. |
| TMA_AZ_PD_TRM_0001 | SetpointOffset | DOUBLE | degC | This value is added to the setpoint set to the modbus controller. |
| TMA_AZ_PD_TRM_0001 | TemperatureDeviationAlarm | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooHigh alarm is sent, the difference must be positive for being an overtemperature. |
| TMA_AZ_PD_TRM_0001 | TemperatureDeviationWarning | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooLow warning is sent, the difference must be negative for being an under temperature. |
| TMA_EL_PD_CBT_0001 | DisableController | BOOLEAN |  | This setting is used  to disable the code for this temperature controller. A reboot of the PXI is necessary to apply this setting |
| TMA_EL_PD_CBT_0001 | ID String | STRING |  | This is the identifier for the cabinet in string format. |
| TMA_EL_PD_CBT_0001 | SetpointOffset | DOUBLE | degC | This value is added to the setpoint set to the modbus controller. |
| TMA_EL_PD_CBT_0001 | TemperatureDeviationAlarm | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooHigh alarm is sent, the difference must be positive for being an overtemperature. |
| TMA_EL_PD_CBT_0001 | TemperatureDeviationWarning | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooLow warning is sent, the difference must be negative for being an under temperature. |
| TMA_EL_PD_CBT_0002 | DisableController | BOOLEAN |  | This setting is used  to disable the code for this temperature controller. A reboot of the PXI is necessary to apply this setting |
| TMA_EL_PD_CBT_0002 | ID String | STRING |  | This is the identifier for the cabinet in string format. |
| TMA_EL_PD_CBT_0002 | SetpointOffset | DOUBLE | degC | This value is added to the setpoint set to the modbus controller. |
| TMA_EL_PD_CBT_0002 | TemperatureDeviationAlarm | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooHigh alarm is sent, the difference must be positive for being an overtemperature. |
| TMA_EL_PD_CBT_0002 | TemperatureDeviationWarning | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooLow warning is sent, the difference must be negative for being an under temperature. |

###### Restricted Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| General | SystemSource | STRING |  | This is the identifier for the system used when publishing the Alarm source. |
| General | TaskSamplingTime | DOUBLE | ms | The sampling time used to execute the task that monitors all the Modbus Temperature Controllers. |
| General | TimeToCheckActiveAlarms | DOUBLE | ms | TimeToCheckActiveAlarms |
| TMA_AX_DZ_CBT_0001 | CommandTimeout | DOUBLE | ms | The timeout for the received commands. |
| TMA_AX_DZ_CBT_0001 | ModbusServerConfigFilePath | STRING |  | Path of the configuration file for the modbus server for this instance. |
| TMA_AX_DZ_CBT_0001 | ModbusServerMappingFilePath | STRING |  | Path of the mapping file for the modbus server for this instance. |
| TMA_AX_DZ_CBT_0001 | ResetValue | DOUBLE |  | The value to send over modbus for resetting the controller. |
| TMA_AX_DZ_CBT_0001 | SendResetValue | BOOLEAN |  | This setting defines if the reset command will send the ResetValue setting over modbus for resetting the controller or not. TRUE sends the ResetValue, FALSE does not. |
| TMA_AX_DZ_CBT_0001 | TemperatureConversionRead | DOUBLE |  | The conversion used to convert the read data from the modbus to the right data for displaying. |
| TMA_AX_DZ_CBT_0001 | TemperatureConversionWrite | DOUBLE |  | The conversion used to convert the command data to send through modbus the right data. |
| TMA_AX_DZ_CBT_0001 | TemperatureDeviationHysteresis | DOUBLE | Cdeg | This is the temperature hysteresis for temperature deviation alarm and warning. |
| TMA_AX_DZ_CBT_0001 | TemperatureWritableMaxValue | DOUBLE |  | The maximum value for setpoint. This value must be the same as one fixed in the hardware to avoid errors when writing not allowed values |
| TMA_AX_DZ_CBT_0001 | TemperatureWritableMinValue | DOUBLE |  | The minimum value for setpoint. This value must be the same as one fixed in the hardware to avoid errors when writing not allowed values |
| TMA_AZ_PD_CBT_0001 | CommandTimeout | DOUBLE | ms | The timeout for the received commands. |
| TMA_AZ_PD_CBT_0001 | ModbusServerConfigFilePath | STRING |  | Path of the configuration file for the modbus server for this instance. |
| TMA_AZ_PD_CBT_0001 | ModbusServerMappingFilePath | STRING |  | Path of the mapping file for the modbus server for this instance. |
| TMA_AZ_PD_CBT_0001 | ResetValue | DOUBLE |  | The value to send over modbus for resetting the controller. |
| TMA_AZ_PD_CBT_0001 | SendResetValue | BOOLEAN |  | This setting defines if the reset command will send the ResetValue setting over modbus for resetting the controller or not. TRUE sends the ResetValue, FALSE does not. |
| TMA_AZ_PD_CBT_0001 | TemperatureConversionRead | DOUBLE |  | The conversion used to convert the read data from the modbus to the right data for displaying. |
| TMA_AZ_PD_CBT_0001 | TemperatureConversionWrite | DOUBLE |  | The conversion used to convert the command data to send through modbus the right data. |
| TMA_AZ_PD_CBT_0001 | TemperatureDeviationHysteresis | DOUBLE | Cdeg | This is the temperature hysteresis for temperature deviation alarm and warning. |
| TMA_AZ_PD_CBT_0001 | TemperatureWritableMaxValue | DOUBLE |  | The maximum value for setpoint. This value must be the same as one fixed in the hardware to avoid errors when writing not allowed values |
| TMA_AZ_PD_CBT_0001 | TemperatureWritableMinValue | DOUBLE |  | The minimum value for setpoint. This value must be the same as one fixed in the hardware to avoid errors when writing not allowed values |
| TMA_AZ_PD_TRM_0001 | CommandTimeout | DOUBLE | ms | The timeout for the received commands. |
| TMA_AZ_PD_TRM_0001 | ModbusServerConfigFilePath | STRING |  | Path of the configuration file for the modbus server for this instance. |
| TMA_AZ_PD_TRM_0001 | ModbusServerMappingFilePath | STRING |  | Path of the mapping file for the modbus server for this instance. |
| TMA_AZ_PD_TRM_0001 | ResetValue | DOUBLE |  | The value to send over modbus for resetting the controller. |
| TMA_AZ_PD_TRM_0001 | SendResetValue | BOOLEAN |  | This setting defines if the reset command will send the ResetValue setting over modbus for resetting the controller or not. TRUE sends the ResetValue, FALSE does not. |
| TMA_AZ_PD_TRM_0001 | TemperatureConversionRead | DOUBLE |  | The conversion used to convert the read data from the modbus to the right data for displaying. |
| TMA_AZ_PD_TRM_0001 | TemperatureConversionWrite | DOUBLE |  | The conversion used to convert the command data to send through modbus the right data. |
| TMA_AZ_PD_TRM_0001 | TemperatureDeviationHysteresis | DOUBLE | Cdeg | This is the temperature hysteresis for temperature deviation alarm and warning. |
| TMA_AZ_PD_TRM_0001 | TemperatureWritableMaxValue | DOUBLE |  | The maximum value for setpoint. This value must be the same as one fixed in the hardware to avoid errors when writing not allowed values |
| TMA_AZ_PD_TRM_0001 | TemperatureWritableMinValue | DOUBLE |  | The minimum value for setpoint. This value must be the same as one fixed in the hardware to avoid errors when writing not allowed values |
| TMA_EL_PD_CBT_0001 | CommandTimeout | DOUBLE | ms | The timeout for the received commands. |
| TMA_EL_PD_CBT_0001 | ModbusServerConfigFilePath | STRING |  | Path of the configuration file for the modbus server for this instance. |
| TMA_EL_PD_CBT_0001 | ModbusServerMappingFilePath | STRING |  | Path of the mapping file for the modbus server for this instance. |
| TMA_EL_PD_CBT_0001 | ResetValue | DOUBLE |  | The value to send over modbus for resetting the controller. |
| TMA_EL_PD_CBT_0001 | SendResetValue | BOOLEAN |  | This setting defines if the reset command will send the ResetValue setting over modbus for resetting the controller or not. TRUE sends the ResetValue, FALSE does not. |
| TMA_EL_PD_CBT_0001 | TemperatureConversionRead | DOUBLE |  | The conversion used to convert the read data from the modbus to the right data for displaying. |
| TMA_EL_PD_CBT_0001 | TemperatureConversionWrite | DOUBLE |  | The conversion used to convert the command data to send through modbus the right data. |
| TMA_EL_PD_CBT_0001 | TemperatureDeviationHysteresis | DOUBLE | Cdeg | This is the temperature hysteresis for temperature deviation alarm and warning. |
| TMA_EL_PD_CBT_0001 | TemperatureWritableMaxValue | DOUBLE |  | The maximum value for setpoint. This value must be the same as one fixed in the hardware to avoid errors when writing not allowed values |
| TMA_EL_PD_CBT_0001 | TemperatureWritableMinValue | DOUBLE |  | The minimum value for setpoint. This value must be the same as one fixed in the hardware to avoid errors when writing not allowed values |
| TMA_EL_PD_CBT_0002 | CommandTimeout | DOUBLE | ms | The timeout for the received commands. |
| TMA_EL_PD_CBT_0002 | ModbusServerConfigFilePath | STRING |  | Path of the configuration file for the modbus server for this instance. |
| TMA_EL_PD_CBT_0002 | ModbusServerMappingFilePath | STRING |  | Path of the mapping file for the modbus server for this instance. |
| TMA_EL_PD_CBT_0002 | ResetValue | DOUBLE |  | The value to send over modbus for resetting the controller. |
| TMA_EL_PD_CBT_0002 | SendResetValue | BOOLEAN |  | This setting defines if the reset command will send the ResetValue setting over modbus for resetting the controller or not. TRUE sends the ResetValue, FALSE does not. |
| TMA_EL_PD_CBT_0002 | TemperatureConversionRead | DOUBLE |  | The conversion used to convert the read data from the modbus to the right data for displaying. |
| TMA_EL_PD_CBT_0002 | TemperatureConversionWrite | DOUBLE |  | The conversion used to convert the command data to send through modbus the right data. |
| TMA_EL_PD_CBT_0002 | TemperatureDeviationHysteresis | DOUBLE | Cdeg | This is the temperature hysteresis for temperature deviation alarm and warning. |
| TMA_EL_PD_CBT_0002 | TemperatureWritableMaxValue | DOUBLE |  | The maximum value for setpoint. This value must be the same as one fixed in the hardware to avoid errors when writing not allowed values |
| TMA_EL_PD_CBT_0002 | TemperatureWritableMinValue | DOUBLE |  | The minimum value for setpoint. This value must be the same as one fixed in the hardware to avoid errors when writing not allowed values |

##### MotorThermalControl

###### General Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| AzimuthGroup1 | AmbientTemperatureOffset | DOUBLE | Cdeg | The offset from the ambient temperature |
| AzimuthGroup1 | ID String | STRING |  | This is the identifier for the motor group in string format. |
| AzimuthGroup1 | TemperatureDeviationAlarm | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooHigh alarm is sent, the difference must be positive for being an overtemperature. |
| AzimuthGroup1 | TemperatureDeviationWarning | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooLow warning is sent, the difference must be negative for being an under temperature. |
| AzimuthGroup2 | AmbientTemperatureOffset | DOUBLE | Cdeg | The offset from the ambient temperature |
| AzimuthGroup2 | ID String | STRING |  | This is the identifier for the motor group in string format. |
| AzimuthGroup2 | TemperatureDeviationAlarm | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooHigh alarm is sent, the difference must be positive for being an overtemperature. |
| AzimuthGroup2 | TemperatureDeviationWarning | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooLow warning is sent, the difference must be negative for being an under temperature. |
| AzimuthGroup3 | AmbientTemperatureOffset | DOUBLE | Cdeg | The offset from the ambient temperature |
| AzimuthGroup3 | ID String | STRING |  | This is the identifier for the motor group in string format. |
| AzimuthGroup3 | TemperatureDeviationAlarm | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooHigh alarm is sent, the difference must be positive for being an overtemperature. |
| AzimuthGroup3 | TemperatureDeviationWarning | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooLow warning is sent, the difference must be negative for being an under temperature. |
| AzimuthGroup4 | AmbientTemperatureOffset | DOUBLE | Cdeg | The offset from the ambient temperature |
| AzimuthGroup4 | ID String | STRING |  | This is the identifier for the motor group in string format. |
| AzimuthGroup4 | TemperatureDeviationAlarm | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooHigh alarm is sent, the difference must be positive for being an overtemperature. |
| AzimuthGroup4 | TemperatureDeviationWarning | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooLow warning is sent, the difference must be negative for being an under temperature. |
| Cabinet0101 | AmbientTemperatureOffset | DOUBLE | Cdeg | The offset from the ambient temperature |
| Cabinet0101 | ID String | STRING |  | This is the identifier for the motor group in string format. |
| Cabinet0101 | SystemSource | STRING |  | This is the identifier for the system used when publishing the Alarm source. |
| Cabinet0101 | TemperatureDeviationAlarm | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooHigh alarm is sent, the difference must be positive for being an overtemperature. |
| Cabinet0101 | TemperatureDeviationWarning | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooLow warning is sent, the difference must be negative for being an under temperature. |
| ElevationGroup1 | AmbientTemperatureOffset | DOUBLE | Cdeg | The offset from the ambient temperature |
| ElevationGroup1 | ID String | STRING |  | This is the identifier for the motor group in string format. |
| ElevationGroup1 | TemperatureDeviationAlarm | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooHigh alarm is sent, the difference must be positive for being an overtemperature. |
| ElevationGroup1 | TemperatureDeviationWarning | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooLow warning is sent, the difference must be negative for being an under temperature. |
| ElevationGroup2 | AmbientTemperatureOffset | DOUBLE | Cdeg | The offset from the ambient temperature |
| ElevationGroup2 | ID String | STRING |  | This is the identifier for the motor group in string format. |
| ElevationGroup2 | TemperatureDeviationAlarm | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooHigh alarm is sent, the difference must be positive for being an overtemperature. |
| ElevationGroup2 | TemperatureDeviationWarning | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooLow warning is sent, the difference must be negative for being an under temperature. |

###### Restricted Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| AzimuthGroup1 | AlarmCodesNoFaultTransition | STRING |  | Coma separated list of alarm codes that do not make the system go to fault |
| AzimuthGroup1 | Control alpha | DOUBLE |  | Specifies the derivative filter time constant. Increasing this value increases damping action. Alpha can be a value between 0 and 1 or NaN, which specifies no derivative filter is applied |
| AzimuthGroup1 | Control Kp | DOUBLE |  | This is the proportional gain value of the temperature controller. |
| AzimuthGroup1 | Control Td | DOUBLE | min | This is the derivative time value of the temperature controller. |
| AzimuthGroup1 | Control Ti | DOUBLE | min | This is the integral time value of the temperature controller. |
| AzimuthGroup1 | Plant Delay Time | DOUBLE | s | Delay Time of first order plant used in control algorithm compensation of tunning |
| AzimuthGroup1 | Plant Process Gain | DOUBLE |  | Gain of first order plant used in control algorithm compensation of tunning |
| AzimuthGroup1 | Plant Time Constant | DOUBLE | s | Time Constant of first order plant used in control algorithm compensation of tunning |
| AzimuthGroup1 | SystemSource | STRING |  | This is the identifier for the system used when publishing the Alarm source. |
| AzimuthGroup1 | TemperatureDeviationHysteresis | DOUBLE | Cdeg | This is the temperature hysteresis for temperature deviation alarm and warning. |
| AzimuthGroup1 | Timeout_PowerOn | DOUBLE | ms | The timeout value after which an alarm is ent if the command was not completed. |
| AzimuthGroup1 | ValveApertureOffset | DOUBLE | % | Offset added to the controller output for manage the aperture of the valve |
| AzimuthGroup1 | ValveDisabledAperture | DOUBLE | % | This is the value to set the valve to when it is disabled. |
| AzimuthGroup1 | ValveInPositionTimeout | DOUBLE | s | The valve must be in position before this Timeout time is due |
| AzimuthGroup1 | ValveOutputHigh | DOUBLE | % | The highest value that the controller can have as an output |
| AzimuthGroup1 | ValveOutputLow | DOUBLE | % | The lowest value that the controller can have as an output |
| AzimuthGroup1 | ValveValidBand | DOUBLE | % | This is the band at which the valve will tell that is in position. |
| AzimuthGroup2 | AlarmCodesNoFaultTransition | STRING |  | Coma separated list of alarm codes that do not make the system go to fault |
| AzimuthGroup2 | Control alpha | DOUBLE |  | Specifies the derivative filter time constant. Increasing this value increases damping action. Alpha can be a value between 0 and 1 or NaN, which specifies no derivative filter is applied |
| AzimuthGroup2 | Control Kp | DOUBLE |  | This is the proportional gain value of the temperature controller. |
| AzimuthGroup2 | Control Td | DOUBLE | min | This is the derivative time value of the temperature controller. |
| AzimuthGroup2 | Control Ti | DOUBLE | min | This is the integral time value of the temperature controller. |
| AzimuthGroup2 | Plant Delay Time | DOUBLE | s | Delay Time of first order plant used in control algorithm compensation of tunning |
| AzimuthGroup2 | Plant Process Gain | DOUBLE |  | Gain of first order plant used in control algorithm compensation of tunning |
| AzimuthGroup2 | Plant Time Constant | DOUBLE | s | Time Constant of first order plant used in control algorithm compensation of tunning |
| AzimuthGroup2 | SystemSource | STRING |  | This is the identifier for the system used when publishing the Alarm source. |
| AzimuthGroup2 | TemperatureDeviationHysteresis | DOUBLE | Cdeg | This is the temperature hysteresis for temperature deviation alarm and warning. |
| AzimuthGroup2 | Timeout_PowerOn | DOUBLE | ms | The timeout value after which an alarm is ent if the command was not completed. |
| AzimuthGroup2 | ValveApertureOffset | DOUBLE | % | Offset added to the controller output for manage the aperture of the valve |
| AzimuthGroup2 | ValveDisabledAperture | DOUBLE | % | This is the value to set the valve to when it is disabled. |
| AzimuthGroup2 | ValveInPositionTimeout | DOUBLE | s | The valve must be in position before this Timeout time is due |
| AzimuthGroup2 | ValveOutputHigh | DOUBLE | % | The highest value that the controller can have as an output |
| AzimuthGroup2 | ValveOutputLow | DOUBLE | % | The lowest value that the controller can have as an output |
| AzimuthGroup2 | ValveValidBand | DOUBLE | % | This is the band at which the valve will tell that is in position. |
| AzimuthGroup3 | AlarmCodesNoFaultTransition | STRING |  | Coma separated list of alarm codes that do not make the system go to fault |
| AzimuthGroup3 | Control alpha | DOUBLE |  | Specifies the derivative filter time constant. Increasing this value increases damping action. Alpha can be a value between 0 and 1 or NaN, which specifies no derivative filter is applied |
| AzimuthGroup3 | Control Kp | DOUBLE |  | This is the proportional gain value of the temperature controller. |
| AzimuthGroup3 | Control Td | DOUBLE | min | This is the derivative time value of the temperature controller. |
| AzimuthGroup3 | Control Ti | DOUBLE | min | This is the integral time value of the temperature controller. |
| AzimuthGroup3 | Plant Delay Time | DOUBLE | s | Delay Time of first order plant used in control algorithm compensation of tunning |
| AzimuthGroup3 | Plant Process Gain | DOUBLE |  | Gain of first order plant used in control algorithm compensation of tunning |
| AzimuthGroup3 | Plant Time Constant | DOUBLE | s | Time Constant of first order plant used in control algorithm compensation of tunning |
| AzimuthGroup3 | SystemSource | STRING |  | This is the identifier for the system used when publishing the Alarm source. |
| AzimuthGroup3 | TemperatureDeviationHysteresis | DOUBLE | Cdeg | This is the temperature hysteresis for temperature deviation alarm and warning. |
| AzimuthGroup3 | Timeout_PowerOn | DOUBLE | ms | The timeout value after which an alarm is ent if the command was not completed. |
| AzimuthGroup3 | ValveApertureOffset | DOUBLE | % | Offset added to the controller output for manage the aperture of the valve |
| AzimuthGroup3 | ValveDisabledAperture | DOUBLE | % | This is the value to set the valve to when it is disabled. |
| AzimuthGroup3 | ValveInPositionTimeout | DOUBLE | s | The valve must be in position before this Timeout time is due |
| AzimuthGroup3 | ValveOutputHigh | DOUBLE | % | The highest value that the controller can have as an output |
| AzimuthGroup3 | ValveOutputLow | DOUBLE | % | The lowest value that the controller can have as an output |
| AzimuthGroup3 | ValveValidBand | DOUBLE | % | This is the band at which the valve will tell that is in position. |
| AzimuthGroup4 | AlarmCodesNoFaultTransition | STRING |  | Coma separated list of alarm codes that do not make the system go to fault |
| AzimuthGroup4 | Control alpha | DOUBLE |  | Specifies the derivative filter time constant. Increasing this value increases damping action. Alpha can be a value between 0 and 1 or NaN, which specifies no derivative filter is applied |
| AzimuthGroup4 | Control Kp | DOUBLE |  | This is the proportional gain value of the temperature controller. |
| AzimuthGroup4 | Control Td | DOUBLE | min | This is the derivative time value of the temperature controller. |
| AzimuthGroup4 | Control Ti | DOUBLE | min | This is the integral time value of the temperature controller. |
| AzimuthGroup4 | Plant Delay Time | DOUBLE | s | Delay Time of first order plant used in control algorithm compensation of tunning |
| AzimuthGroup4 | Plant Process Gain | DOUBLE |  | Gain of first order plant used in control algorithm compensation of tunning |
| AzimuthGroup4 | Plant Time Constant | DOUBLE | s | Time Constant of first order plant used in control algorithm compensation of tunning |
| AzimuthGroup4 | SystemSource | STRING |  | This is the identifier for the system used when publishing the Alarm source. |
| AzimuthGroup4 | TemperatureDeviationHysteresis | DOUBLE | Cdeg | This is the temperature hysteresis for temperature deviation alarm and warning. |
| AzimuthGroup4 | Timeout_PowerOn | DOUBLE | ms | The timeout value after which an alarm is ent if the command was not completed. |
| AzimuthGroup4 | ValveApertureOffset | DOUBLE | % | Offset added to the controller output for manage the aperture of the valve |
| AzimuthGroup4 | ValveDisabledAperture | DOUBLE | % | This is the value to set the valve to when it is disabled. |
| AzimuthGroup4 | ValveInPositionTimeout | DOUBLE | s | The valve must be in position before this Timeout time is due |
| AzimuthGroup4 | ValveOutputHigh | DOUBLE | % | The highest value that the controller can have as an output |
| AzimuthGroup4 | ValveOutputLow | DOUBLE | % | The lowest value that the controller can have as an output |
| AzimuthGroup4 | ValveValidBand | DOUBLE | % | This is the band at which the valve will tell that is in position. |
| Cabinet0101 | AlarmCodesNoFaultTransition | STRING |  | Coma separated list of alarm codes that do not make the system go to fault |
| Cabinet0101 | Control alpha | DOUBLE |  | Specifies the derivative filter time constant. Increasing this value increases damping action. Alpha can be a value between 0 and 1 or NaN, which specifies no derivative filter is applied |
| Cabinet0101 | Control Kp | DOUBLE |  | This is the proportional gain value of the temperature controller. |
| Cabinet0101 | Control Td | DOUBLE | min | This is the derivative time value of the temperature controller. |
| Cabinet0101 | Control Ti | DOUBLE | min | This is the integral time value of the temperature controller. |
| Cabinet0101 | Plant Delay Time | DOUBLE | s | Delay Time of first order plant used in control algorithm compensation of tunning |
| Cabinet0101 | Plant Process Gain | DOUBLE |  | Gain of first order plant used in control algorithm compensation of tunning |
| Cabinet0101 | Plant Time Constant | DOUBLE | s | Time Constant of first order plant used in control algorithm compensation of tunning |
| Cabinet0101 | TemperatureDeviationHysteresis | DOUBLE | Cdeg | This is the temperature hysteresis for temperature deviation alarm and warning. |
| Cabinet0101 | Timeout_PowerOn | DOUBLE | ms | The timeout value after which an alarm is ent if the command was not completed. |
| Cabinet0101 | ValveApertureOffset | DOUBLE | % | Offset added to the controller output for manage the aperture of the valve |
| Cabinet0101 | ValveDisabledAperture | DOUBLE | % | This is the value to set the valve to when it is disabled. |
| Cabinet0101 | ValveInPositionTimeout | DOUBLE | s | The valve must be in position before this Timeout time is due |
| Cabinet0101 | ValveOutputHigh | DOUBLE | % | The highest value that the controller can have as an output |
| Cabinet0101 | ValveOutputLow | DOUBLE | % | The lowest value that the controller can have as an output |
| Cabinet0101 | ValveValidBand | DOUBLE | % | This is the band at which the valve will tell that is in position. |
| ElevationGroup1 | AlarmCodesNoFaultTransition | STRING |  | Coma separated list of alarm codes that do not make the system go to fault |
| ElevationGroup1 | Control alpha | DOUBLE |  | Specifies the derivative filter time constant. Increasing this value increases damping action. Alpha can be a value between 0 and 1 or NaN, which specifies no derivative filter is applied |
| ElevationGroup1 | Control Kp | DOUBLE |  | This is the proportional gain value of the temperature controller. |
| ElevationGroup1 | Control Td | DOUBLE | min | This is the derivative time value of the temperature controller. |
| ElevationGroup1 | Control Ti | DOUBLE | min | This is the integral time value of the temperature controller. |
| ElevationGroup1 | Plant Delay Time | DOUBLE | s | Delay Time of first order plant used in control algorithm compensation of tunning |
| ElevationGroup1 | Plant Process Gain | DOUBLE |  | Gain of first order plant used in control algorithm compensation of tunning |
| ElevationGroup1 | Plant Time Constant | DOUBLE | s | Time Constant of first order plant used in control algorithm compensation of tunning |
| ElevationGroup1 | SystemSource | STRING |  | This is the identifier for the system used when publishing the Alarm source. |
| ElevationGroup1 | TemperatureDeviationHysteresis | DOUBLE | Cdeg | This is the temperature hysteresis for temperature deviation alarm and warning. |
| ElevationGroup1 | Timeout_PowerOn | DOUBLE | ms | The timeout value after which an alarm is ent if the command was not completed. |
| ElevationGroup1 | ValveApertureOffset | DOUBLE | % | Offset added to the controller output for manage the aperture of the valve |
| ElevationGroup1 | ValveDisabledAperture | DOUBLE | % | This is the value to set the valve to when it is disabled. |
| ElevationGroup1 | ValveInPositionTimeout | DOUBLE | s | The valve must be in position before this Timeout time is due |
| ElevationGroup1 | ValveOutputHigh | DOUBLE | % | The highest value that the controller can have as an output |
| ElevationGroup1 | ValveOutputLow | DOUBLE | % | The lowest value that the controller can have as an output |
| ElevationGroup1 | ValveValidBand | DOUBLE | % | This is the band at which the valve will tell that is in position. |
| ElevationGroup2 | AlarmCodesNoFaultTransition | STRING |  | Coma separated list of alarm codes that do not make the system go to fault |
| ElevationGroup2 | Control alpha | DOUBLE |  | Specifies the derivative filter time constant. Increasing this value increases damping action. Alpha can be a value between 0 and 1 or NaN, which specifies no derivative filter is applied |
| ElevationGroup2 | Control Kp | DOUBLE |  | This is the proportional gain value of the temperature controller. |
| ElevationGroup2 | Control Td | DOUBLE | min | This is the derivative time value of the temperature controller. |
| ElevationGroup2 | Control Ti | DOUBLE | min | This is the integral time value of the temperature controller. |
| ElevationGroup2 | Plant Delay Time | DOUBLE | s | Delay Time of first order plant used in control algorithm compensation of tunning |
| ElevationGroup2 | Plant Process Gain | DOUBLE |  | Gain of first order plant used in control algorithm compensation of tunning |
| ElevationGroup2 | Plant Time Constant | DOUBLE | s | Time Constant of first order plant used in control algorithm compensation of tunning |
| ElevationGroup2 | SystemSource | STRING |  | This is the identifier for the system used when publishing the Alarm source. |
| ElevationGroup2 | TemperatureDeviationHysteresis | DOUBLE | Cdeg | This is the temperature hysteresis for temperature deviation alarm and warning. |
| ElevationGroup2 | Timeout_PowerOn | DOUBLE | ms | The timeout value after which an alarm is ent if the command was not completed. |
| ElevationGroup2 | ValveApertureOffset | DOUBLE | % | Offset added to the controller output for manage the aperture of the valve |
| ElevationGroup2 | ValveDisabledAperture | DOUBLE | % | This is the value to set the valve to when it is disabled. |
| ElevationGroup2 | ValveInPositionTimeout | DOUBLE | s | The valve must be in position before this Timeout time is due |
| ElevationGroup2 | ValveOutputHigh | DOUBLE | % | The highest value that the controller can have as an output |
| ElevationGroup2 | ValveOutputLow | DOUBLE | % | The lowest value that the controller can have as an output |
| ElevationGroup2 | ValveValidBand | DOUBLE | % | This is the band at which the valve will tell that is in position. |
| General | TimeForWaitTemperatureStabilization | DOUBLE | ms | Time to wait before enabling the temperature faults |
| General | TimeToCheckActiveAlarms | DOUBLE | ms | TimeToCheckActiveAlarms |

##### OSS

###### General Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| General | TemperatureDeviationAlarm | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooHigh alarm is sent, the difference must be positive for being an overtemperature. |
| General | TemperatureDeviationWarning | DOUBLE | Cdeg | This is the temperature difference at which a TemperatureTooLow warning is sent, the difference must be negative for being an under temperature. |
| OSS | watchdogMaximumTime | DOUBLE | s | Maximum time that the controller will wait without a watchdog signal |

###### Restricted Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| General | AlarmCodesNoFaultTransition | STRING |  | Coma separated list of alarm codes that do not make the system go to fault |
| General | TemperatureDeviationHysteresis | DOUBLE | Cdeg | This is the temperature hysteresis for temperature deviation alarm and warning. |
| General | TimeToCheckActiveAlarms | DOUBLE | ms | TimeToCheckActiveAlarms |
| OSS | coolDownBearingsTimeout | DOUBLE | s | Timeout for the bearings to cool down during the observation sequence |
| OSS | coolDownTankTimeout | DOUBLE | s | Timeout for the tank to cool down during the observation sequence |
| OSS | ID String | STRING |  | This is not used for this subsystem, is kept for consistency. |
| OSS | operationTransitionTimeout | DOUBLE | s | Timeout for the transition between automatic and manual mode, in seconds. |
| OSS | powerOffCoolingTimeout | DOUBLE | s | Timeout for the cooling system to power off |
| OSS | powerOffMainPumpTimeout | DOUBLE | s | Timeout for the main pump system to power off |
| OSS | powerOffOilCirculationTimeout | DOUBLE | s | Timeout for the oil circulation system to power off |
| OSS | powerOnCoolingTimeout | DOUBLE | s | Timeout for the cooling system to power on |
| OSS | powerOnMainPumpTimeout | DOUBLE | s | Timeout for the main pump system to power on |
| OSS | powerOnOilCirculationTimeout | DOUBLE | s | Timeout for the oil circulation system to power on |
| OSS | ResettingTime | DOUBLE | ms | Timeout for the reset transition. |
| OSS | SystemSource | STRING |  | This is the identifier for the system used when publishing the Alarm source. |

##### Safety

###### General Access Setting list

There are no settings under this section.

###### Restricted Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| General | Fault Iterations Safety NoOk | DOUBLE |  | This is a counter used to trigger the Safety NO OK variable as TRUE if the value is greater than the set value. |
| General | Monitoring Timeout ms | DOUBLE | ms | This is the timeout for the monitoring task in the TMA safety code. |
| General | OverrideCausesTimeout | DOUBLE | ms | This is the timeout for executing the override causes command. |
| General | ResetCausesNumberOfChecks | DOUBLE |  | This is a setting used to trigger a warning that tells that some causes persist and were not restored. The trigger is sent if the number of checks is greater or equal to this setting value. |
| General | ResetCausesTimeBeforeChecking s | DOUBLE | s | Time to wait before checking that the causes were reset. |
| General | ResetCausesTimeBetweenChecking s | DOUBLE | s | Time to wait between checking that the causes were reset. |
| General | ResetCausesTimeout | DOUBLE | ms | This is the timeout for executing the reset causes command. |
| General | RT to Safety Clock ms | DOUBLE | ms | This is the RT to safety clock time value. |
| General | Safety Clock ms | DOUBLE | ms | This is the safety clock time value. |

##### TMAMainRT

###### General Access Setting list

There are no settings under this section.

###### Restricted Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| General | AfterCommanderLaunchWait | DOUBLE | ms | This is the time to wait after launching the commander |
| General | BeforeAmbientTemperatureTaskLaunchWait | DOUBLE | ms | This is the time to wait before launching the Ambient Temperature task |
| General | BeforeAZMotorThermalLaunchWait | DOUBLE | ms | This is the time to wait before launching the azimuth motor thermal control task |
| General | BeforeBALLaunchWait | DOUBLE | ms | This is the time to wait before launching the balancing task |
| General | BeforeBoschLaunchWait | DOUBLE | ms | This is the time to wait before launching the bosch task |
| General | BeforeBoschPowerSupplyLaunchWait | DOUBLE | ms | This is the time to wait before launching the bosch power supply task |
| General | BeforeCabinet0101LaunchWait | DOUBLE | ms | This is the time to wait before launching the cabinet 0101 thermal control task |
| General | BeforeCabinetLaunchWait | DOUBLE | ms | This is the time to wait before launching the cabinet task |
| General | BeforeCCWLaunchWait | DOUBLE | ms | This is the time to wait before launching the azimuth motor thermal control task |
| General | BeforeDPLaunchWait | DOUBLE | ms | This is the time to wait before launching the deployable platform task |
| General | BeforeELMotorThermalLaunchWait | DOUBLE | ms | This is the time to wait before launching the azimuth motor thermal control task |
| General | BeforeIOTelemetryPublicationLaunchWait | DOUBLE | ms | This is the time to wait before launching the IO Telemetry publication task |
| General | BeforeLPLaunchWait | DOUBLE | ms | This is the time to wait before launching the locking pins task |
| General | BeforeMainAxesOMTTaskLaunchWait | DOUBLE | ms | This is the time to wait before launching the OMT tasks for Main Axes |
| General | BeforeMainAxesPXICommTaskLaunchWait | DOUBLE | ms | This is the time to wait before launching the task to communicate with the Axes PXI |
| General | BeforeMainAxisLaunchWait | DOUBLE | ms | This is the time to wait before launching the main axis task |
| General | BeforeMCLaunchWait | DOUBLE | ms | This is the time to wait before launching the mirror cover task |
| General | BeforeMCLLaunchWait | DOUBLE | ms | This is the time to wait before launching the mirror cover lock task |
| General | BeforeModbusTempControllersLaunchWait | DOUBLE | ms | This is the time to wait before launching the Modbus temperature controllers task |
| General | BeforeMPSLaunchWait | DOUBLE | ms | This is the time to wait before launching the main power supply task |
| General | BeforeOSSLaunchWait | DOUBLE | ms | This is the time to wait before launching the deployable platform task |
| General | BeforeSafetyLaunchWait | DOUBLE | ms | This is the time to wait before launching the safety task |
| General | BeforeTECLaunchWait | DOUBLE | ms | This is the time to wait before launching the TEC task |

##### TopEndChiller

###### General Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| General | ID String | STRING |  | This is not used for this subsystem, is kept for consistency. |
| General | LocalRemote timeout | DOUBLE | ms | After this time the Top End chiller checking for local remote change will send a timeout error |
| General | Power ON/OFF timeout | DOUBLE | ms | After this time the Top End chiller checking for power on or off will send a timeout error |
| General | Reset pulse time | DOUBLE | ms | Time of the reset pulse sent to Top end chiller controller |

###### Restricted Access Setting list

| Instance | Name | Type | Unit | Description |
| ---- | ---- | ----------- | ----------------- | ----- |
| General | SystemSource | STRING |  | This is the identifier for the system used when publishing the Alarm source. |
| General | TimeToCheckActiveAlarms | DOUBLE | ms | TimeToCheckActiveAlarms |
