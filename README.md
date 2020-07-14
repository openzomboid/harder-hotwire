# harder_hotwire
Project Zomboid mod that makes hotwiring cars harder.
## Description
This mod is mostly useful for multiplayer when cars are enabled.  
Current vanilla skill level requirements of 1 Electrical and 2 Mechanics can be met with perks from the very start, so many newcomers can hotwire and take others' cars without significant effort. Boosting requirements negates that.  
As a bonus the mod has an ability to revert damage done to hotwired cars and even craft a key if your skill is high enough.

### Compatibility
Project Zomboid: `40.43`, `41.37`  
Other mods: mods that overwrite `ISVehicleMenu.showRadialMenu` will be incompatible.
## New Skill Requirements
### Hotwire
* Metalworking: 1;
* Electrical: 4;
* Mechanics: 6;
* Time: 200.

Metalworking is now required in addition to upped Electrical and Mechanics levels as a person should be able to at least know their way with metal to open ignition in most cases.
### Un-hotwire
* Metalworking: 4;
* Electrical: 6;
* Mechanics: 8;
* Time: 900.

Increased requirements. Player should not only be able to revert the damage done to electrical circuits, but also put the lock back in place and weld it all together.
### Craft Car Key
* Metalworking: 8;
* Electrical: 10;
* Mechanics: 10;
* Time: 2100.

Overkill? Maybe. But consider that each player can craft keys if they pass the checks now and even become an auto locksmith on the server – a task that only administrators could perform previously.
## Translations
For the time being this mod has full translations to following languages:
* English (EN)
* Russian (RU)

If you'd like to translate this mod into your native language, please send me your translation file either through Steam Workshop or GitHub merge request and I will add it with credits in-place.
## Links and Copyrights
Development repository on GitHub: https://github.com/rez-spb/harder_hotwire  
License: GPL-3.0 (see LICENSE file).  
Yes, you no longer can misappropriate the code/idea and add your name to the beginning without repercussions.