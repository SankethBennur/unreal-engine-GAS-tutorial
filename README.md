# Gameplay Ability System

## Attributes and UI
 - Implemented
     * Base attributes: Health, Mana, Stamina,
     * Core attributes: Strength, Agility, Intelligence,
     * Battle attributes: Armor, Movement Speed, Attack Speed etc.
 - Attribute widgets appear on HUD dynamically, when a pawn is possessed by player.


https://github.com/user-attachments/assets/37a4526d-9b6d-4cb0-b7d9-711f8a8db142



## Melee, Block and Parry
 - Parry window while blocking.
 - Blocking damages stamina, while parrying returns damage to source' stamina.


https://github.com/user-attachments/assets/c26436f9-406b-4d5c-a705-6e568df1457a



## Triple (or Quadruple) jump!
 - Any number of maximum jumps can be used, just by modifying an attribute.
 - Jump recharge effect occurs to refill number of jumps to maximum.
 - Also updating character walk speed in level based on a movement-speed attribute.


https://github.com/user-attachments/assets/c1ebdd4f-daa2-4538-9ac3-defb68c3fa64



## Disable statuses
 - Implemented disable statuses from DotA 2 such as root, disarm, silence, stun etc.
 - Implemented using Gameplay Cues with appropriate animation across a multiplayer network.


https://github.com/user-attachments/assets/9fe8d972-5ae7-4c79-a142-ad1383f27154



## Ability Target Data
 - Created an Asynchronous method (latent action) that can send a target data to server.
 - The ability sends the target data to server, and upon receiving, the appropriate ability action is performed.
 - So a player can blink to a target location that was set by local input values, and action will be performed by Server.


https://github.com/user-attachments/assets/dd38d66c-5b44-4ead-9b66-c6e878c67e85



## Passive Ability & Break
 - Triggering a passive ability based on an event.
 - Break effect prevents the passive ability from activating.
 - Implemented Mana Burn from dota - notice how mana is damaged on melee hit, and when passive is disabled (break effect) mana burn does not happen.


https://github.com/user-attachments/assets/14842c1c-5ccb-4f5f-847d-ea23e47ca8cb



## Curve Tables, Magnitude Modifier Calculation Class & Effect Execution Class
 - Utilized Curve Tables for Gameplay Effect values for a data-driven approach.
 - Used Magnitude Modifer Calculation Class for complex calculation of an effect modifier.
 - Also used Effect Execution Class to perform operation on a running effect.
![github-curve-table](https://github.com/user-attachments/assets/ea0e9939-b998-43d8-9d6d-183b637a6f2f)


## Meta Attributes, Stacking and Overflowing Effects
 - Health damaged/healed using a distinct meta-attribute.
 - Also refining the damage received through damage reduction from magical or physical damage, as in DotA 2.
 - Stacking an effect that overflows to perform another effect.


https://github.com/user-attachments/assets/8acdbf50-2a8c-4f4c-8ce9-20ff3dec86af

