# Sonic: Lock & Load - Changelog

This changelog aims to provide a mostly accurate and verbose overview of all
changes made to Sonic: Lock & Load.

## v1.4.1 "Vibrant Horizons" (upcoming)

## v1.4 "Horizons" (2023-11-26)

## v1.3.3 "Crystal Resurgence"

## v1.3.2 "Revised Resurgence"

## v1.3.1 "Attested Resurgence"

## v1.3 "Resurgence"

## Where are versions v1.1 and v1.2?

**v1.1 and v1.2 were incorrectly named.** They have since been retroactively
changed to v1.0.1 and v1.0.2 to align with proper semantic versioning.

Officially, v1.3 is the next version after v1.0.2. I'm not changing it to v1.1
because that would offset all later versions, and I can't be asked to deal with
the headache that's going to bring.

## v1.0.2 "Unabridged Chaos"

## v1.0.1 "Amended Chaos"

## v1.0 "Chaos"

## v0.9 "Dark"

## v0.8 "Rose"

## v0.7 "Ascension"

## v0.6 "Eclipse"

## v0.5 "Knight"

## v0.4 "Speedforce"

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
