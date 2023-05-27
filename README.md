# SUCC - SWADE Ultimate Condition Changer

This module is meant to change the condition icons and effects in the SWADE system (v.1+) on Foundry VTT. SUCC is based on [Combat Utility Belt](https://github.com/death-save/combat-utility-belt) but specifically tailored for the SWADE system which allows maximum support and compatibility for players and game masters on that system without the need to ignore any incompatible features found on CUB. We can also react more quickly to changes made in the system. It provides many of the features found in CUB (such as the condition lab which enables game masters to customise existing conditions and set up their own). SUCC also provides a strong API other developers can use within their modules. As a result it is already a dependency for other popular SWADE modules such as [SWIM](https://github.com/SalieriC/SWADE-Immersive-Macros) and [Better Rolls for Savage Worlds](https://github.com/javierriveracastro/betteroll-swade) and thus is fully compatible with both.  
If you want to support the development of SUCC, please consider donating on [![Ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/salieric).  

## Mentions & Credits
### Chat messages & code base
The style (CSS) and part of the template (HBS) for the condition to chat messages are used from [Combat Utility Belt](https://github.com/death-save/combat-utility-belt) (CUB) with kind permission from errational. The Condition Lab and underlying code base was also taken from CUB which is in line with its license.
Great thanks go to @ddbrown30 for all his work and his patience. Without him SUCC wouldn't be as user friendly and powerful as it is today. He basically took CUB as a base and rebuilt SUCC on that to bring over as many features from CUB as possible without loosing any of SUCCs own functionality it had at that point.
### Icons
The icons are modified icons used from [game-icons.net](https://game-icons.net/), modified in [photopea.com](https://www.photopea.com/).
- Intoxicated: [Poison Bottle by Lorc](https://game-icons.net/1x1/lorc/poison-bottle.html)
- Irradiated: [Radioactive by Lorc](https://game-icons.net/1x1/lorc/radioactive.html)
- Shaken: [Pummeled by Lorc](https://game-icons.net/1x1/lorc/pummeled.html)
- Aiming: [Archery Target by Lorc](https://game-icons.net/1x1/lorc/archery-target.html)
- Berserking: [Enraged by Delapouite](https://game-icons.net/1x1/delapouite/enrage.html)
- Defending: [Arrows Shield by Lorc](https://game-icons.net/1x1/lorc/arrows-shield.html)
- Flying: [Feathered Wing by Lorc](https://game-icons.net/1x1/lorc/feathered-wing.html)
- Holding: [Empty Hourglass by Lorc](https://game-icons.net/1x1/lorc/empty-hourglass.html)
- Bound: [Handcuffed by Delapouite](https://game-icons.net/1x1/delapouite/handcuffed.html)
- Entangled: [Daemon Pull by Delapoutite](https://game-icons.net/1x1/delapouite/daemon-pull.html)
- Frightened: [Screaming by Lorc](https://game-icons.net/1x1/lorc/screaming.html)
- Distracted: [Distraction by DarkZaitzev](https://game-icons.net/1x1/darkzaitzev/distraction.html)
- Encumbered: [Light Backpack by Delapoutite](https://game-icons.net/1x1/delapouite/light-backpack.html)
- Out of Control: [City Car by Delapoutite](https://game-icons.net/1x1/delapouite/city-car.html)
- Prone: [Oppression by Lorc](https://game-icons.net/1x1/lorc/oppression.html)
- Stunned: [Knockout by Skoll](https://game-icons.net/1x1/skoll/knockout.html)
- The Drop: [Target Dummy by Lorc](https://game-icons.net/1x1/lorc/target-dummy.html)
- Vulnerable: [On Sight by Darkzaitzev](https://game-icons.net/1x1/darkzaitzev/on-sight.html)
- Bleeding Out: [Heart by Skoll](https://game-icons.net/1x1/skoll/hearts.html) and [Drop by Lorc](https://game-icons.net/1x1/lorc/drop.html)
- Diseased: [Virus by Lorc](https://game-icons.net/1x1/lorc/virus.html)
- Heart Attack: [Heart Beats by Delapoutite](https://game-icons.net/1x1/delapouite/heart-beats.html)
- Incapacitated: [Dead Head by Delapoutite](https://game-icons.net/1x1/delapouite/dead-head.html)
- On Fire: [Flame by Carl Olsen](https://game-icons.net/1x1/carl-olsen/flame.html)
- Poisoned: [Drop by Lorc](https://game-icons.net/1x1/lorc/drop.html) and [Skull Crossed Bones by Lorc](https://game-icons.net/1x1/lorc/skull-crossed-bones.html)
- Wrecked: [Ship Wreck by Delapoutite](https://game-icons.net/1x1/delapouite/ship-wreck.html)
- Cover: [Wooden Crate by Delapoutite](https://game-icons.net/1x1/delapouite/wooden-crate.html) and [Person by Delapoutite](https://game-icons.net/1x1/delapouite/person.html)
- Shield: [Shield by sbed](https://game-icons.net/1x1/sbed/shield.html) and [Person by Delapoutite](https://game-icons.net/1x1/delapouite/person.html)
- Reach: [Arrowhead by Lorc](https://game-icons.net/1x1/lorc/arrowhead.html)
- Torch: [Primitive Torch by Delapoutite](https://game-icons.net/1x1/delapouite/primitive-torch.html)
- Boost: [Mighty Force by Delapoutite](https://game-icons.net/1x1/delapouite/mighty-force.html)
- Invisible: [Invisible by Delapoutite](https://game-icons.net/1x1/delapouite/invisible.html)
- Lower: [Oppression by Lorc](https://game-icons.net/1x1/lorc/oppression.html)
- Protection: [Lamellar by Lorc](https://game-icons.net/1x1/lorc/lamellar.html)
- Smite: [Pointy Sword by Lorc](https://game-icons.net/1x1/lorc/pointy-sword.html)  
- Conviction: [Angel wings by Lorc](https://game-icons.net/1x1/lorc/angel-wings.html)  
- Cold Blooded: [Thermometer cold by Delapoutite](https://game-icons.net/1x1/delapouite/thermometer-cold.html)  
- Blind: [Sight disabled by Skoll](https://game-icons.net/1x1/skoll/sight-disabled.html)  
- Deflection: [Divert by Lorc](https://game-icons.net/1x1/lorc/divert.html)  
- Slumber: [Night sleep by Delapoutite](https://game-icons.net/1x1/delapouite/night-sleep.html)  
All of these icons were modified by SalieriC, their original files are published under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/).
### Mentions
Thank you very much to Javier Rivera Castro for his tireless efforts to teach SalieriC JavaScript, CSS, HTML and HBS.  
Many thanks also go to the fine people of the Foundry VTT Discord server and their helpful advice and explanations.  
### Module Developers
This module is brought to you by SalieriC and Javier Rivera Castro. TheChemist (ddbrown30) is also heavily involved in the development.  
Salieri is accepting donations, so if you wish to support him financially, please head over to his Ko-fi and leave him a donation. =)  
[![Ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/salieric)
