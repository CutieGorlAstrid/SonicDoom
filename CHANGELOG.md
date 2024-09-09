# Sonic: Lock & Load - Changelog

This changelog aims to provide a mostly accurate and verbose overview of all
changes made to Sonic: Lock & Load.

## v1.4.1 "Vibrant Horizons" (2024-09-09)

Sonic: Lock & Load v1.4.1 "Vibrant Horizons" is an update to the existing v1.4
"Horizons" update, providing refinements, polishes, a new and improved Style
System, a real scoring system, less tedious level layouts, an expanded lobby,
an all-new first level, and more.

* **Scoring System:** A new scoring system has supplanted the old system based
on defeated enemies. This new system will now track an actual score variable,
which is incremented by dealing damage and defeating enemies, multiplied by
your current Style Rank, and decremented by taking damage.
* **Checkpoints:** Checkpoints have been added to the levels, so if you lose all
your Rings after having already touched a checkpoint, you'll restart from that
checkpoint instead of restarting the entire level.
* **Style System:** The style system has been majorly rebalanced and tightly
integrated into the scoring system, with all new style bonuses in the vein of
ULTRAKILL.
* **Refined Levels:** Level 1, Vibrant Gardens, replacing Sunset Gardens from
v1.4, features a much brighter and more vibrant (ehhhh???) colour palette, and
it looks even *more* like Green Hill Zone than it ever did before.
Marble Madness and Oceanic Fortress have also seen minor improvements aimed at
reducing the tedium in the levels, though these levels still could do with more
of a facelift...
* **Smoother Gameplay:** The characters and weapons have been tweaked to provide
a more fun and cohesive experience - to list a few off, Classic Sonic can now
wall jump, Shadow can now parry melee attacks with the High Shovel, and Sonic
can now keep enemies in the air with the Accelerated Pistol, among a frick of a
lot more additions and improvements.
* **The Road to Nightfall:** Shadow has seen quite the improvement in v1.4.1 -
he has been given a new weapon, the Chaos Reaper, a crossbow/sniper/plasma
shotgun type thing, and the Dark Assaulter automatic shotgun has been removed
for the sake of cohesion, since it was redundant to give him a weapon that's
basically a combination of two of his existing weapons.
* **And Much, Much More:** Alongside everything mentioned so far, Sonic: Lock &
Load v1.4.1 "Vibrant Horizons" includes some much-needed improvements over
issues that were prevalent in v1.4 "Horizons". Whatever you're looking for in
this Sonic + DOOM + Devil May Cry hybrid, Vibrant Horizons is sure to make it
way, way better. (I hope.)

## v1.4 "Horizons" (2023-11-26)

Sonic: Lock & Load v1.4 “Horizons” is a major update, bringing new levels, new
techniques, refinements to the changes made in v1.3.3 and major changes to the
gameplay and Sonic: Lock & Load’s fundamentals.

* **New Levels:** Sunset Gardens, Marble Madness and Oceanic Fortress.
* **New Techniques:** Offhand command split into Offhand Attack and Offhand Ability, providing special abilities for each character. New Crouch Slide ability for all characters. The Slam Attack and Wall Jump can now be used by (mostly) everyone.
* **New Weapons:** New weapons and rebalanced and updated weapons for everyone. Shadow gets his infamous pump-action MP5.
* **Refinements:** Various changes to the gameplay and fixed and rebalanced behaviours and mechanics from v1.3.x. Super Forms have been rebalanced.
* **Improvements:** Movement changes, ULTRAKILL-style movement, rebalanced double jump and full speed is now always on. Difficulty levels have seen an overhaul.
* **Cyber Space Arena:** A new endless arena level where you can fight endlessly spawning enemies until you fail, inspired by Sonic Frontiers' Cyber Space.
* **And Other Things Also:** New title screen, new logo, new branding, new end-level ranking system, Discord Rich Presence support, DOOM II levels turned off by default, and so on.

## v1.3.3 "Crystal Resurgence"

TODO

## v1.3.2 "Revised Resurgence"

TODO

## v1.3.1 "Attested Resurgence"

TODO

## v1.3 "Resurgence"

TODO

## Where are versions v1.1 and v1.2?

**v1.1 and v1.2 were incorrectly named.** They have since been retroactively
changed to v1.0.1 and v1.0.2 to align with proper semantic versioning.

Officially, v1.3 is the next version after v1.0.2. I'm not changing it to v1.1
because that would offset all later versions, and I can't be asked to deal with
the headache that's going to bring.

## v1.0.2 "Unabridged Chaos"

TODO

## v1.0.1 "Amended Chaos"

TODO

## v1.0 "Chaos"

TODO

## v0.9 "Dark"

TODO

## v0.8 "Rose"

TODO

## v0.7 "Ascension"

TODO

## v0.6 "Eclipse"

TODO

## v0.5 "Knight"

TODO

## v0.4 "Speedforce"

TODO

## v0.3 "Model II"

v0.3 of Sonic the Hedgehog in DOOM actually provides some new additions and
features - namely, a new custom HUD, revamped melee combat and a brand new
tutorial, which never got finished until v1.0.

## v0.2 "Mega Drive"

v0.2 of Sonic the Hedgehog in DOOM focuses more on providing support for DOOM
II: Hell on Earth and fixing some of the weirdness that was present in v0.1.

It was released not long after v0.1 as a sort of hotfix, since I didn't really
pay much attention to how versioning works. It's gotten to the point where I
had to reorganise every single release.

### Changes from v0.1

These changes are formulated by manually going over commits between v0.1 and
v0.2.

* Sonic can now heal up to 999 Rings.
* The player display name "Sonic" has been expanded to say "Sonic the Hedgehog".
* Sonic's JumpZ (jump height) is now 10.0 instead of the usual DOOM jump height.
* "Sonic's Fist" is now "Boost/Drift". This changes the dynamic of the rapidly-punching
fist to the Boost from the mainline 3D Sonic games (although its implementation here
is more like the Boost in Sonic Unleashed Wii/PS2).
* Sonic starts with 300 Chaos Energy rather than 150.
* The order of the Speedy Shotgun and Chaos Blaster have been swapped.
* Removed the Chaos Rain.
* Ring pickups now inherit from CustomInventory instead of Health for custom
scripting.
* Chaos Energy now maxes out at 9999. For some reason.
* The "Ultra-Violence" difficulty has been moved to the end rather than being
at the top of the selection menu.
* Toned down the padding on the difficulties.
* More sounds and more other things.
* Changes to various graphics, sprites and music tracks.
* Changed the licence to the Unlicense.

## v0.1 "Genesis"

This is the first in-development release of Sonic the Hedgehog in DOOM.

This outlines the general structure of what would later become Sonic: Lock &
Load.

It's not very well-organised, even when you compare it to how not organised
S:L&L is nowadays. ZScript also didn't exist back then, and I never learnt
how to use ACS by this point, so this version is mainly written in DECORATE.

This is mainly built off of the pre-indev versions of Sonic the Hedgehog in
DOOM, which I made on my old iMac and forgot to back up, so those versions are
unfortunately lost to time.
