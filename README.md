# SSJ: Advanced (fix)
Fixed version of SSJ: Advanced by alkatrazbhop for CSGO. This was done by replacing the PrintColorText() function with multicolours' CPrintToChat().

I am aware this isn't a very complicated change -_-

## Original plugin from: https://forums.alliedmods.net/showthread.php?t=287039


Jump stats plugin intended for use on bhop servers.

The features (all except the first are toggleable):

      • Count your jumps.
      • 2 modes: display stats of every jump; display stats only of the sixth jump.
      • Display your current speed every time you perform a bunnyhop.
      • Calculate and display the amount of speed gained per jump.
      • Display height difference between surfaces of the current and the previous jump.
      • Calculate and display sufficiency ('gained speed/max possible gain' ratio) of your strafes.
      • Display stats of the player you spectate.


How to use:

      • Open the menu either by typing '!ssj' in chat, or 'sm_ssj' in console.
      • Toggle all the features to your liking.
      • Close the menu (optional).


Installation:

    • Copy the 'ssj.smx' to your server's '\addons\sourcemod\plugins\' directory.
    • Load the plugin by typing the following into the server's console: 'sm plugins load ssj'


Cvars:

      • ssj_msgstart "{green}[SSJ] {darkblue}- "  – prefix, this precedes the main message;
      • ssj_msgtext "{lightblue}"                 – main message's color, can also include any text;
      • ssj_msgvar "{darkred}"                    – variables' color, can also include any text;
      
Colors:

      • {default}
      • {darkred}
      • {green}
      • {lightgreen}
      • {red}
      • {blue}
      • {olive}
      • {lime}
      • {lightred}
      • {purple}
      • {grey}
      • {orange}
      • {bluegrey}
      • {lightblue}
      • {darkblue}
      • {grey2}
      • {orchid}
      • {lightred2}
