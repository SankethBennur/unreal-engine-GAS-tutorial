# Gameplay Ability System

## Attributes and UI
 - Implemented
     * Base attributes: Health, Mana, Stamina,
     * Core attributes: Strength, Agility, Intelligence,
     * Battle attributes: Armor, Movement Speed, Attack Speed etc.
 - Attribute widgets appear on HUD dynamically, when a pawn is possessed by player.


https://github.com/user-attachments/assets/97462568-3de3-4c74-b1bc-3c20fb825ff6



## Melee, Block and Parry
 - Parry window while blocking.
 - Blocking damages stamina, while parrying returns damage to source' stamina.


https://github.com/user-attachments/assets/f3980443-6143-4d4a-ae03-8c9528659ff6



## Triple (or Quadruple) jump!
 - Any number of maximum jumps can be used, just by modifying an attribute.
 - Jump recharge effect occurs to refill number of jumps to maximum.
 - Also updating character walk speed in level based on a movement-speed attribute.


https://github.com/user-attachments/assets/254e26b7-8532-40c7-8d60-53f63569b76a



## Disable statuses
 - Implemented disable statuses from DotA 2 such as root, disarm, silence, stun etc.
 - Implemented using Gameplay Cues with appropriate animation across a multiplayer network.


https://github.com/user-attachments/assets/01c77926-2131-48ae-b2cb-54df70d9af68



## Ability Target Data
 - Created an Asynchronous method (latent action) that can send a target data to server.
 - The ability sends the target data to server, and upon receiving, the appropriate ability action is performed.
 - So a player can blink to a target location that was set by local input values, and action will be performed by Server.


https://github.com/user-attachments/assets/b2742f91-8cb3-4dec-b518-475e3fe29ee5



## Passive Ability & Break
 - Triggering a passive ability based on an event.
 - Break effect prevents the passive ability from activating.
 - Implemented Mana Burn from dota - notice how mana is damaged on melee hit, and when passive is disabled (break effect) mana burn does not happen.


https://github.com/user-attachments/assets/90587df1-83e8-4d04-a92a-78c99d460d62



## Curve Tables, Magnitude Modifier Calculation Class & Effect Execution Class
 - Utilized Curve Tables for Gameplay Effect values for a data-driven approach.
 - Used Magnitude Modifer Calculation Class for complex calculation of an effect modifier.
 - Also used Effect Execution Class to perform operation on a running effect.
![github-curve-table](https://github.com/user-attachments/assets/ea0e9939-b998-43d8-9d6d-183b637a6f2f)


## Meta Attributes, Stacking and Overflowing Effects
 - Health damaged/healed using a distinct meta-attribute.
 - Also refining the damage received through damage reduction from magical or physical damage, as in DotA 2.
 - Stacking an effect that overflows to perform another effect.


https://github.com/user-attachments/assets/dd38e293-000c-4e82-a0fa-76157419eac6

