# Twitch Chat Commands
A List of all commands which can be executed by RobotHelpFul

Notes: 
1. Commands will not run when Streamerbot isnt running
2. All commands aren't case sensative unless specified otherwise. 
3. Alternative versions/methods to preform the same command are placed horizonally placed next to eachother, For example `!Music` and `!Song` will give the same output regardless of which one you input   
4. Command options are placed under the main command. Which can be chosen for exmaple `!Plushie Show` and `!Plushie Hide`
5. A small description on what the command does will be located after the either the command or option
6. This does not include global and individual cooldowns 

# Menu
* [General Commands](https://github.com/Robotrowful/Twitch-Chat-Commands/tree/main?tab=readme-ov-file#General-commands)
* [Visual commands](https://github.com/Robotrowful/Twitch-Chat-Commands/tree/main?tab=readme-ov-file#Visual-commands)
  * [Foreground](https://github.com/Robotrowful/Twitch-Chat-Commands/tree/main?tab=readme-ov-file#Foreground)
  * [Background](https://github.com/Robotrowful/Twitch-Chat-Commands/tree/main?tab=readme-ov-file#Background)
  * [Border Corners](https://github.com/Robotrowful/Twitch-Chat-Commands/tree/main?tab=readme-ov-file#Border-Corners)
  * [Window and Fullscreen mode](https://github.com/Robotrowful/Twitch-Chat-Commands/tree/main?tab=readme-ov-file#window-and-fullscreen-mode)
* [Talking](https://github.com/Robotrowful/Twitch-Chat-Commands/tree/main?tab=readme-ov-file#Talking)

# General Commands
* Art Specs `!ArtSpecs` Will give you Information about my tablet and art programs
* Background `!Orignal background` Not to be confused with the Visual Backgrounds commands, This gives you the links to the original creators of backgrounds used by Milan Nohejl and Floris Kloet
* Commands `!Commands` Will give you a link to this place! You are here! 
* Pronouns `!Pronouns` Will give you my pronouns and how to apply them to your user if you want
* Time `!Time` Will give you my current time
* Music `!Music` `!Song` Will give you the current song I'm playing, However If streamerbot cannot get the song for any reasons it will give you a cheecky message back

# Visual Commands
These commands are available to regular/reoccuring members of the channel, This is to prevent spam.  
It is possible in the future that these commands will be replaced with a Redeem channel point reward instead. 
These commands will be reset to their defaults when entering a new screen.  

## Foreground

Only one of these effects can be active at a time. 

* `!Plushie` Plushies are on by default for `Starting`, `Break` or `Ending` screens. 
   - `Hide` If there are plushies active on the screen it will make them fly away 
   - `Show` Will make the plushie be seen on the screen
   - `Big` `Enormous` `Expand` `Giant` `Gigantic` `Ginormous` `Massive` Makes the Plushie really big. This will revert after 5 minutes (300 seconds)
   - `Time left` This command ONLY works when the plushie is giant. It will tell you how long until the plushie reverts to normal size
     
## Background

These commands do not work on the `Starting`, `Break` or `Ending` screens.
Time between Border commands is about a minute

* `!Border` `!Background` `!BG` The background defaults are Arts is `Rainbow`, Codes is `Matrix` and Games is either `Majima` or `Trans`
   - `Majima` `Gold and Red` `Red and Gold` Will display a background that change between the colours Red, Gold and Grey
   - `Matrix` Will display a background which resembles the falling letters from The Matrix
   - `Ocean` `Water` Will display a Bright blue background of Calm water
   - `Rainbow` Will display a split double background that changes to all the colours of the rainbow 
   - `Random` Will make the background a random colour
   - `Reset` `Default` Will default the backgrounds to their original versions
   - `Trans` Will display a background which changes between Pink, Blue and white
   - `Colour` Will change the background to one of these colours
      - `Black`
      - `Blue`
      - `Brown`
      - `Green`
      - `Orange`
      - `Pink`
      - `Purple`
      - `Red`
      - `White`
      - `Yellow`
   - `Cooldown` Will display how long until the backgrounds can be changed again. (Will also display if it's paused or ready)

## Border Corners

These commands allow users to change how the corners of bordered mode will look. Nor do they work on the `Starting`, `Break` or `Ending` screens.

* `!Border Corner` `!Border Corners` 
   - `Round` `Curve` Will give a roundness / curve to them
   - `Square` Will give a sharp point

## Window and Fullscreen mode

These commands do not work on the `Starting`, `Break` or `Ending` screens.

* `!Borderless` `!Border fullscreen ` `!Fullscreen` Will remove the backgrounds. 
* `!Border Window` `!Border Windowed` `!Window` `!Windowed` command will readd the Borders/Backgrounds. 
  
# Talking

* `catJam` `catJAM` `catJAMPARTY` Is a case sensative command. Has a 1 in 3 chance to say catJAMPARTY in chat
* `Huhh` Is a case sensative command. Has a 1 in 3 chance to say Huhh in chat
* `Meow` Is a case sensative command. Has a 1 in 2 chance to say Meow in chat
* `Hi Helpful` `Hello Helpful` Will say a random hello back to you! (Dont worry the bot isn't laggy, Just has a random time between 100ms and 2000ms to reply back to you)
