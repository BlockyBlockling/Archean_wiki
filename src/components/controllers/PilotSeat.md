<p align="center">
  <img src="PilotSeat.png" />
</p>

|Component|`PilotSeat`|
|---|---|
|**Module**|`ARCHEAN_avatar`|
|**Mass**|50 kg|
|[**Size**](# "Based on the component's occupancy in a fixed 25cm grid.")|75 x 75 x 175 cm|
#
---

# Description
The Pilot Seat allows a player to control (send values on different channels) a component using the bound vehicle controls from a keyboard, controller, or joystick.

# Usage
Press `R` to sit in the seat.
Hold `R` for one second to exit a seat.

> While seated, you can move to another nearby seat without needing to exit the current seat using the `R` key.
> When exiting a seat, it remembers where you were relative to the build when you entered the seat, and that is where you will be when you exit it.

### List of outputs
|Channel|Function|Range|
|---|---|---|
|0|Using|1 if an avatar is seated in the seat, otherwise 0|
|1|Backward/Forward|-1.0 to +1.0|
|2|Left/Right|-1.0 to +1.0|
|3|Down/Up|-1.0 to +1.0|
|4|Pitch|-1.0 to +1.0|
|5|Roll|-1.0 to +1.0|
|6|Yaw|-1.0 to +1.0|
|7|Main Thrust|0.0 to 1.0|
|8|Aux 1|0 or 1|
|9|Aux 2|0 or 1|
|10|Aux 3|0 or 1|
|11|Aux 4|0 or 1|
|12|Aux 5|0 or 1|
|13|Aux 6|0 or 1|
|14|Aux 7|0 or 1|
|15|Aux 8|0 or 1|
|16|Aux 9|0 or 1|
|17|Aux 0|0 or 1|

> If an [OwnerPad](../miscellaneous/OwnerPad.md) is present, you must have the "`Sit`" permission sit in the seat and `Interact` to use the controls.
