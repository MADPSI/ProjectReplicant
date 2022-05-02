# Project: Replicant
* WIP Warning: This mod is still very much in development and may suffer from unexpected issues, and may undergo significant changes without notice. 
* Note: The mod does not strictly require, but benefits from *Dark Injection* (https://davoonline.com/sporemodder/rob55rod/DarkInjection/) being installed.

**Replicant** is a large-scale Parts Mod that adds copies of all the existing Creature Parts (including Creepy & Cure if it happens to be installed) with modifications made to them.

## In General
All "Replicas" are entirely free, both in terms of DNA and Complexity Score. They are also massively scalable and, in the case that the Stacking component is installed, stackable on every type of part including each other, with the obvious exception of non-rigid limbs. Because they exist as part of separate categories, they do not get added to the pool of available parts for unlocking in Creature Stage. As a bonus, the mod also features all Cell Parts and Grox Parts, the latter of which have had extensive modifications made to them, including adding symmetry and a handful of additional morphs. Dr Pepper's Bot Parts have not been included as to avoid potential unforseen issues, with the game itself and legal.

Also of note, the category system the mod uses is similar to the one in Dark Injection, wherein dropdown Subcategories that contain their own sets of pages are now available to avoid cluttering the Categories bar, similar in principle to the category system in place in the normal game's Painting categories. Force Save is *not* required for these parts.

Lastly, all of the parts are readily available at the start of the Creature Stage, which while it may cause a few balancing issues, a more viable solution has yet to present itself.

## Animating, Textureless Parts
"ATPs" (Blue) are parts that keep their animations and abilities, but have had their textures entirely removed. To be more precise, they try to, where applicable, copy the skin texture of the Creature's body, though some paints are not able to paint on parts regardless of the parts' own textures. An example of that being the Scars Detail paint from Creepy & Cute. Due to the considerable resources required, too many of these parts will result in very slow painting times.

Note: Many parts were obviously not designed to be used in this fashion and some suffer from texture irregularities such as Ambient Occlusion (painted-shadow) dilution and shading abnormalities depending on their positioning relative to the body. They also retain all of their abilities at their original levels, which may cause certain balancing issues, therefor putting it down to the discretion of the user whether or not to use them.

## Rigid, Textured Parts
"RTPs" (Yellow) are the primary focus of this mod's entire existence. They are identical to the existing parts, but all animations have been, where applicable, transformed into user-controlled morphs activated by arrow-handles* (Morph Handles), and a handful have had new morphs added to expand the available number to maximise customisation potential. If Dark Injection or any other mod that enables Nudge Handles (cube-shaped handles that only move the part on a single axis, generally into or out from the skin) in the Creature Editor are installed, most parts in this category have them, though due to a limitation within the game itself, there can only be one Morph Handle explicitly marked as a Nudge Handle, meaning that there are some parts that have multiple Nudge Handles for multiple movement axes (that being the plural of axis, pronounced "ax-ees") despite it not being obvious due to only one of them being a cube.

Additionally, many parts have been modified to now accept skin particle painting, which means they will properly display match the skin in areas where the parts are meant to contact the skin, instead of being merely painted the same colour. This is most noticeable on the Cassoworry wings in the Detail subcategory.

Note: Despite being one of the more touched on topics, Mouth parts and some Eye parts have been a major issue due to unexpected problems with the tools used in the process. Therefor, no additional morphs have been added to these parts, including the manual opening and closing of Mouths, with the exception of the Pincer type of mouth. Attempts are being made to remedy the situation, but most have hit roadblocks. Ultimately, the decision to release a version of this mod without these mouths was made out of necessity of not keeping people waiting for too long to the point where it would become irrelevant. If anyone is willing to help remedy the situation with the mouths and eyes, please enquire with **emd4600** regarding the *SporeModder-Blender-Addons* either via the Spore Modding Community Discord Server (link available here: https://davoonline.com/phpBB3/viewtopic.php?f=1&t=6393or) or his project page for the addons on GitHub (https://github.com/emd4600/SporeModder-Blender-Addons).

## Rigid, Textureless Parts
"RTxPs" (Green) are exactly like the RTPs, naturally, but have had their textures removed, as with ATPs. Also like ATPs, texture oddities may appear unexpectedly, but testing has shown them to be minimal in occurrence. They should also still be used sparingly to avoid long painting times.

Note: As with the two previous categories, there has been a few issues with these parts too. In addition to the problems plaguing certain mouth and eye RTPs, an error in compiling the mod means that only a handful of parts have had their Part-mode textures removed in order to properly distinguish them from other parts. Further testing of this issue is needed to establish the exact cause, but for now the inconsistency is the worst part of the issue, crashes being very rare among these parts.

Misc
The mod is distributed in .sporemod format for the express purpose of making an easily-toggleable stacking mechanic, and will likely also be needed in the future as the mod expands. When first installed with the ModAPI Easy Installer (Available as part of the ModAPI Launcher Kit, available here: http://davoonline.com/sporemodder/rob55rod/ModAPI/Public/), the mod will open an installer wizard with the Stacking option pre-set to On. This setting can then be changed by using the ModAPI Easy Uninstaller and changing the settings of the mod by clicking the Gear next to its entry in the list of mods, as with Dark Injection. This can only be done before opening the game or after closing it, not during runtime.

If Stacking is disabled, the parts revert back to being placeable only on the main body and limbs of the Creature, useful for nesting parts in certain creations, and while perhaps a hassle to have to restart the game very so often, the best currently available option.

## Special Thanks
### Splitwirez (rob55rod).
Additional resources and technical assistance.

### Rebecca "DarkEdgeTV".
Bug Testing, exposition, showcasing, original mod request.

### Sneaky Zucchini (Paranoid Modder).
Bug Testing and showcasing.

#### Drakrylos.
Bug Testing, showcasing, catering.

### TERRORSEKT (Doom / Lich / THI / Doomsoul / Cuddlemuffin).
Bug Testing, showcasing, emotional support.

### You.
Your patience and understanding.

### Iron Maiden.
Motivation. UP THE F@#KING IRONS!
https://www.youtube.com/watch?v=WxnN05vOuSM

## Change Log
### 0.14.0
* Moved hosting to GitHub.
* Significant recompiling and cleanup done, admittedly not much change or new content.
* Fixed an issue preventing certain parts from being savable.
* Made all parts available from the start of Creature Stage.

### 0.5.0
* Initial release.
* Added Rigid, Rigid Textureless and Animating Textureless parts of all parts excepting most mouths (see above).
* Added optional Stacking component.
