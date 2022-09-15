### Sixaxis Remapper

###### 2.3 (5/8/20)
- Sixaxis to Stick: Upgrade axis default inversion logic. 
	- In relation to sticks: PS3 / Wii controllers use normal Sixaxis Y, PS4 does not. Wii IR uses inverted X, Sixaxis/Touchpad does not.
- Documentation Updates

###### 2.2 (5/4/20)
Additions: 
- Ported edited script version from forums that combined the Stick and Sixaxis inputs from the controller. Thanks forum posters! Use Select + [] to enable/disable.
- Split script enable into separate enables for Y and X axis. Use Select + /\ to Enable/Disable Y axis; Select + () to Enable/Disable X axis
- Stick to Sixaxis: Added toggle to send (or not) original input axis to console.
Fixes:
- Added 100/-100 limiter. (CM seems to invert sent inputs if values are \>= 101/-101)

Developer's note:  
After scanning the latest support DM (that ended up being a support forum post) to make sure the 2.1 version is working for them, to my surprise I saw a new post of them asking for sixaxis remap and original thumbstick data to simultaneously output to console.  
By the time I saw the new posts another poster hardcoded in the commands needed to combine both inputs anyways, nice! Where is the pull request button on forum threads?  
I ended up porting over the concept version posted, removed hardcoded style from the forum post to better fit with existing code, added some enable toggles and voila version 2.2!

###### 2.1 (4/30/20)
- Integrated "reverse" version: You can now use Sixaxis (or Wii IR/PS4 Touchpad) to remap to a thumbstick! This mode is activated by default if using an Xbox. Use Select + Cross / A to switch between Stick <\-> Sixaxis remap modes.

Developer's note:  
Before 2.1 I had two sixaxis remapper script versions - this one (stick to sixaxis output) and a "Reverse" one for Xbox systems (sixaxis to thumbstick output).  
Over the years I kept getting support DMs of people trying to use the normal version (stick to sixaxis output) on an Xbox, then DM me for support in getting script working.  
By integrating both versions and forcing 'Sixaxis to thumbstick' mode if the console detected is a Xbox that finally solved the DMs.  
Note to self: people don't research which code version they need to use, easier to have the code itself select the proper version needed.

###### 2.0.2 (12/1/16) | 2.0.1 (10/9/16) | 2.0 (10/8/16)
- New: Load/Save a custom profile, use a preset profile, and change all settings in-game!
- Added separate Y and X value for response sensitivity of the original axis vs. what Sixaxis values is sent to console.
- Added custom profile function (Select + L1 to load, Select + R1 to save custom profile)
- Added hold of ACCZ axis (holds at -25: upside down, must be manually enabled in script)
- Added changing of which Sixaxis axises to remap on the fly (use Select + L2 to switch axises, this part of script also acts as the preset profiles)
- Added adjustment of sensitivity response from the original axis to the Sixaxis remaps (use Select + face buttons to adjust)
- ~~Added support for Everybody's Gone To The Rapture (thanks to those who helped with this).~~ 

Developer's note: I was misled on this one, someone said EGTTR worked with these settings and I ported it in untested.  
What I didn't know is CM didn't have support (and afaik still doesn't) for editing PS4 sixaxis data.  
2.0.2 (12/1/16) &  2.0.1 (10/9/16) are identical releases with updated changelogs to disclaim PS4 sixaxis support, due to a slew of downloads of people hoping for PS4 sixaxis support.

###### 1.91 (1/12/16)
- Added support for PS4 Touchpad
- Added support for original axis's travel vs. game's responsiveness.
- Cleanup Wii IR support code.
- Update description due to confusion of use of motion controls with Xbox controller.

###### 1.91 (6/19/14)
- Added support for Wii remote IR. Tested with "Bentley's Hackpack" again, and accuracy: Needs work. At least you can have some fun with ur Wiimotes now.