# x4-Better-piracy
_X4 Foundations mod to improve piracy_

## Compatibility
Compatible with `3.x`, with and without `Split vendetta`.
Savegame friendly. (Both adding and removal)

## Description
This mod addresses several piracy gameplay-aspects in X4 that I really dislike.

If you want to force some S/M ship to bail, right-click it, choose "Harass" and follow the instructions.

## Detailed changes explanation

### Replaced "Surrender!" dialog option by "Harass" contextual action.
Replaced the confusing and mostly random "Surrender!" dialog option by a more streamlined "Harass" contextual menu action.

If you want to force some S/M ship to bail, right-click it and choose "Harass".

That will start a quest, like the one for boarding L/XL ships, but targeted towards S/M ships.

### Removed "Ship type penalty" from the bailing calculation
Before, you were heavily punished if you were flying a ship with a higher `maxHull` than the enemy you were harassing.

This has been removed.

### Improved feedback when crew bails
If the crew is bailing out of the ship, a notification will appear of the lower-left corner detailing it.

### Piracy is a crime!
By default, nobody cared about piracy, you could hijack 1000 ships in front of them and you will still be their best friend.

Now, piracy is a crime, and if you do it enough, people will consider you a criminal.

### Removed extra damage done when claiming with marines
Your marines have been instructed to be as careful as you are when claiming ships, so they will no longer cause any extra damage to the ships they claim. 

## Credits
 - vx -> Author of `True Capture`, where a lot of inspiration was drawn.
 - Kevrlet -> Author of `FixBailChance`, where a lot of inspiration was drawn.
 - SirNukes -> Author of `SirNukes Mod Support APIs`.
 - Smashicons -> Author of the image used as Thumbnail (https://www.flaticon.es/autores/smashicons)

## Changelog
### 0.4.0
 - Reworked all the "RightClick -> Harass" code, not should work much better.
 - Externalized hard-coded texts to I18N files (English and Spanish).
### 0.3.0
 - Removed "Surrender!" dialog, replaced it by a more streamlined "RightClick -> Harass".
 - Added dependency to "SirNukes Mod Support APIs"
### 0.2.0
 - Forcing a pilot to bail out of their ship will negatively impact your relations with his/her faction.
### 0.1.0
 - Replaced NPCs saying the "Abandon ship!" when they bail by a more discrete, less annoying and more informative notification on the lower-right corner.
 - Expanded `hull%` calculations from `20%` to `75%`, which should make the effects of this mod more gradual.
### 0.0.0
 - Initial release!
 
