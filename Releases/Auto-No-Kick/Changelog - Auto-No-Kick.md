### Auto-No-Kick

###### 3.1 (12/29/21)

Additions:
- 2nd activation axis. 
	- By default it will now sense X axis along with the usual Y axis. 
	- Both axises need to be idle for script actions to activate. Movement on either axis beyond deadzone stops script actions.
- A 2nd button can now also be held down.
- Configurable strength of held down button(s).
- Configuration Controls Updates:
	- Moved misc script controls to Right stick/R3. (R3 = Enable, R3+RS Up = Enable Rumble, R3+RS Down = Enable LED)
	- Added in-game ability to select nearly any Button/axis in-game and bind it to button #1 / #2 to Press, or Axis #1 / #2 to hold. (Select + [] to select button ID, Select + L1/R1 for binding)
	- Updated Wait Time adjustment (Select + Up/Down). You can now hold Up to set wait time to 250ms; Down to set wait time to 20, rest time to 25.
- Presets Updates:
	- Added 2 Games.
	- Removed presets for games in which servers have closed, and an untested preset.
- Related documentation, variable names, and customzation area updates.

Fixes: 
- Start preset listened to the wrong button to activate.
- Saved 9 bytes by updating process for detecting if controller is idle.
- some compile fixes for Zen (PS4_TOUCHX depreciated)


###### 3.0 (12/29/19)

Additions:
 - Added various Presets for specific games, including CoD: Black Ops 4!
 - Hold Axis function for up to 2 axises. Stick Rubberbanding!
 - "Step Move", steps forward, backward, left, right every few Auto-No-Kick iterations.
 - Hold Button for a Timed Interval (Useful for Flight Simulators: Flying in a Holding Pattern)
 - Enable switch, allows you to temporarily disable and re-enable Auto-No-Kick's anti-idle actions. (Select + Left)
 - LED Status Notifications. (LED Status can be disabled.)
 - Touchpad X for listen axis: Hold Select + touch Touchpad + L3 to activate
 
Changes:
 - Consolidated old TRACE_2/3/4 status notifications to also display the status of new features added in this release.
 - Activation zone configuration officially added for use with controllers unable to properly center their sticks, so as to not accidentally deactivate script.
 - Updated In-Game User Configuration Controls and documentations to accommodate new Features and Presets.
 - Documentation and variable name Updates to reference new features and improve readability.
 - Fix: In deadzone detection, check for negative axis was checking double the required amount. (added inv() instead of shortcut op -)
 
###### 2.6 (8/13/18)
Changelog not found.
(Simpler feature set: No LEDs, Axis hold, Timed Button Hold, Step movement, Temporary Script Disable, or various Presets.)

###### 2.2 (4/21/18)
Changelog not found.