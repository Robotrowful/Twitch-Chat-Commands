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
  * [Check Commands](https://github.com/Robotrowful/Twitch-Chat-Commands/tree/main?tab=readme-ov-file#Check-Commands)
* [Talking](https://github.com/Robotrowful/Twitch-Chat-Commands/tree/main?tab=readme-ov-file#Talking)
* [Alternative Commands](https://github.com/Robotrowful/Twitch-Chat-Commands/tree/main?tab=readme-ov-file#Alternative-commands)
* [Moderator Commands](https://github.com/Robotrowful/Twitch-Chat-Commands/tree/main?tab=readme-ov-file#Moderator-Commands)

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

Only one dragon plushie visual effects can be active at a time. 
Speed values are Slower, Slow, Normal, Fast, Faster, Fastest, Hyper. 
Speed commands dont affect the dragon plush visability commands, and can be used in conjunction with them.

* `!Plushie` Plushies are on by default for `Starting`, `Break` or `Ending` screens. 
   - `Hide` If there are plushies active on the screen it will make them fly away 
   - `Show` Will make the plushie be seen on the screen
   - `Big` `Enormous` `Expand` `Giant` `Gigantic` `Ginormous` `Massive` Makes the Plushie really big. This will revert after 5 minutes (300 seconds)
   - `Time left` This command ONLY works when the Dragon plushie is giant. It will tell you how long until the plushie reverts to normal size
   - `Reset Size` `Normal` Only works when the Dragon plushie is giant. Will revert to normal size
   - `Speed Up` Will increase it's speed. Will say if it cant go any higher 
   - `Speed Down` Will decrease it's speed Will say if it cant go any lower
   - `Speed Reset` Will reset it's speed to default of 50
   - `Activity` `Check` `State` Will tell you what the dragon plushie is currently doing (Hidden, Shown, Massive)
   - `Pet` Will pet the dragon plush & will keep a total tally
*`!Dragon Plush Pet Counter` Will give the current amount of pettings the dragon plush has recived
* `!I Am The Mouse` `!I'm The Mouse` Will show an image of a mouse on screen with a sound that says "I am the mouse"
* `!I Am Trapped` `!I'm Trapped`  Will show either image of a mouse in jail or a box on screen with a sound that says "I'm trapped"
  
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
   - `Colour` `Color` Will change the background to one of these colours
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
* `!Border Window` `!Border Windowed` `!Window` `!Windowed` command will readd the Borders/Backgrounds to Width 5
* `!Border Width` Will change the pixel width of the border
 - `0` Alternative to !fullscreen
 - `1`
 - `2`
 - `3`
 - `4`
 - `5` `Default`

## Check Commands

  If you need to make sure something's cooldown or to see other info here is a list of useful commands

  * `!Background Current` `!Background State` `!Current Background` `!Check Background` Will tell you the current background
  * `!Border Cooldown` `!BG Cooldown` `!Background Cooldown` Will say how long until the background can be changed, if it cant or if it can be changed
  * `!Check Dragon Plush Activity` `!Check Plushie Activity` `!Plushie Activity` `!Plushie Check` `!Plushie State` Will say if the Dragon Plush is shown, hidden or massive
  * `!Check Dragon Plush Size``!Plushie Time Left` `!How Long Are You Big For Dragon Plush`Will display the time remaining of the giant dragon plush (will only work if it is giant)
  * `!Check Dragon Plush Speed` `!Check Plushie Speed` Will display how fast the dragon plush is moving

# Talking

* `catJam` `catJAM` `catJAMPARTY` Is a case sensative command. Has a 1 in 3 chance to say catJAMPARTY in chat
* `Huhh` Is a case sensative command. Has a 1 in 3 chance to say Huhh in chat
* `Meow` Is a case sensative command. Has a 1 in 2 chance to say Meow in chat
* `Hi Helpful` `Hello Helpful` Will say a random hello back to you! (Dont worry the bot isn't laggy, Just has a random time between 100ms and 2000ms to reply back to you)

# Alternative commands
These commands where made to the sole reason to make it look like your casting a spell. 

## Dragon Plush Commands

### !Plushie Show
* `!Summon` `!Reveal yourself` 
   - `Dragon Plush`

### !Plushie Hide
* `!Flyaway` `!Begone` 
   - `Dragon Plush`

### !Plushie Grow
* `!Grow My Dragon Plush`

### !Plushie Time Left
* `!How Long Are You Big For Dragon Plush`

### !Plushie Reset Size
* `!Return To Normal Size Dragon Plush`

### !Plushie Speed Up
* `!Accelerate My`  `!Hasten My`
  - `Dragon Plush`

### !Plushie Speed Down
* `!Decelerate My` `!Hinder the`
  - `Dragon Plush`

### !Plushie Speed Reset
* `!Dragon Plushie Speed Reset`
* `!Go Easy Dragon Plush`

# Moderator Commands
Only Moderators can use this commands

* `!Add to` Must have a username at the end to work. 
  - `Regular` Will allow someone to use most of the commands listed. 
  - `Suggest` Can allow someone the !Suggest Command
 
* `!Remove` Must have a username at the end to work. 
  - `Regular` Will remove their access to my custom commands
  - `Suggest` Will revoke access to using !Suggest

* `!Suggest` Will allow mods to put their message into a suggestion box. However non mods can be given access to suggest if a moderator adds them to a suggest group 
