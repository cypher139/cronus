### LBP1 Crowd Pleaser trophy:
###### 1.1 (5/8/18)
Updates to combo: 
- Removed redundant wait commands as wait times above 4 seconds seem to be working nowdays. 
- Added a Circle button press in-game to account for levels which start immediately with a text bubble message.


### ModNation Racers Creation Downloader:
###### 1.1 (4/11/18)
- Reworked next row setup portion of script to accommodate different size pages in-game; downloads of Tracks and Karts (4x3 grid) now works properly.
- Finishing last row no longer moves cursor to start of row, rather it now immediately loads next page. 
- Variables renamed for better readability.
###### 1.2 (4/16/18)
- Added support for creator profile screen (7x7 grid).
- Added customizing grid sizes (use Select+ D-pad).
- Default size added (8x3 - default for Modz)
- Added "Success" rumble to Enable/Disable commands.
- Added ability to restart script where previously stopped. (Select + PS)
###### 1.3 (4/19/18)
- Fix / Optimizations: 
Adjusted wait times for each area of Download combo. Hopefully the script doesn't get stuck in posting comments now. This also accounts for previously downloaded creations better - those creations should now get viewed.
- Addition: Added an option to adjust how long the script waits for game to download creation - wait time is now increased if 4x3 grid is used to accommodate larger track downloads.
- Fix: "Download / Vote" combo changed to "Download / View Creation Info" as part of the wait times adjustments above, as voting does not give any XP.
###### 1.4 (4/20/18)
- Added feature to disable certain controls (Both stick, L1, L2, R2) while script is running to avoid accidental button presses.
- Various fixes mainly related to (hopefully) managing longer than usual vibration commands on old CM devices.
###### 1.9 (9/23/18)
NOTE NOTE NOTE: Server shutdown is imminent for this game: 10/10/2018. This affects this script as all it does is download user creations from the online servers ;)
- Addition: Script now turns controller off while loading the next Row to search, if the controller battery is low or if the script has completed at least 3 Download Search pages.
- Fix / Addition: New Cronus Pro software version did not compile the script due to a missing return value in a function (What? Said "missing" return was nested in an if.)
  So, instead the script uses a new method to move the selection cursor in-game; also has the added benefit to no longer need to move the cursor back to start of row when starting a new row.
- Documentation Updates, Make comments look nicer, etc.
