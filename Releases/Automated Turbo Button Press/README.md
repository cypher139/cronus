## Automated Turbo Button Press
```  
 _________  ___  ___  ________  ________  ________  ________  ________  ________     
|\___   ___\\  \|\  \|\   __  \|\   __  \|\   __  \|\   __  \|\   __  \|\   __  \    
\|___ \  \_\ \  \\\  \ \  \|\  \ \  \|\ /\ \  \|\  \ \  \|\  \ \  \|\  \ \  \|\  \   
     \ \  \ \ \  \\\  \ \   _  _\ \   __  \ \  \\\  \ \  \\\  \ \  \\\  \ \  \\\  \  
      \ \  \ \ \  \\\  \ \  \\  \\ \  \|\  \ \  \\\  \ \  \\\  \ \  \\\  \ \  \\\  \ 
       \ \__\ \ \_______\ \__\\ _\\ \_______\ \_______\ \_______\ \_______\ \_______\
        \|__|  \|_______|\|__|\|__|\|_______|\|_______|\|_______|\|_______|\|_______|
```  
[Changelog](Changelog.md) | [Release](Automated%20Turbo%20Button%20Press.gpc)  
  
- Author: CypherNova139		  
- Console: All  
- Controller: All  
- Script Usage: Task Automation    
  
  
Do you need to press buttons over and over again? This script will press a button (defined as TurboButton) over and over again in a infinite loop, which can be enabled and disabled at will, effectively "turboing" the desired button.  
Unlike turbo controllers this loop stays enabled without your intervention, leaving no need to hold down the button to be "turbo"'d!  

To better gauge the turbo press speed the current player controller LED will light up whenever the Turbo button is pressed, and turns off when it is not being pressed.
 
//\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\\\\  
		  Features  
\\\\\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-//  
  
- Turbo press up to 2 buttons simultaneously
- Adjustable turbo button press frequency, even during gameplay
- LED turns on and off in time with the turbo button presses.
  
//\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\\\\  
		  How To Use  
\\\\\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-//  
  
Basics:  
- Press R3 (default): Start/Stop turbo press loop.

While holding Select:
- L1: Decrement Rest Time by 250ms (up to 50ms)
- R1: Increment Rest Time by 250ms (up to 4 seconds)
- L2: Set Hold and Rest time to 250ms
- R2: Set Hold time to 250ms, Set Rest time to 4 seconds.

TRACE_6: Current RestTime / 100 
  
//\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\\\\  
		  Games Tested / Examples    
\\\\\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-//  
**Game:** Jetpack Joyride  
Start by equipping the "Beat the House" gadget combo, then start a game round, activate this combo script by pressing the StartButton and leave on for a few hours to grind tons of coins!