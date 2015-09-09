# Command List

* Applies to quadcopters
* Assumptions:
  * All four rotors act as one

## Commands (high-level):

*	Takeoff (power on, calibrate, config, etc.)
*	Land
*	Hover
*	Up
*	Down
* Based on the camera position during initial calibration:
  *	Forward
  *	Back
  *	Left
  *	Right
  *	RotateLeft
  *	RotateRight
*	Move
  * this is the actual command the rest for the most part is preset off of this one
  * this command will correspond to AT* move command which will generally be device specific with a general form of cmd: flag, roll, pitch, gaz, yaw.
