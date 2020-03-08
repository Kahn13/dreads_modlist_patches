# Where to find the guide
The Github version (this version) of the guide is the first version to get updates but the Mod Picker version should mirror the Github version. The Github version has extended comments and users should at least read through the Github version of the guide.
- [Github version of the guide](https://github.com/dreadflopp/dreads_modlist_patches/blob/master/README.md)
- [Mod Picker version](https://modpicker.com/skyrimse/mod-lists/7275/details)
- [The guide section on STEP]()

# Introduction
This modlist a build for the [STEP: Core guide for Skyrim Special Edition](https://www.nexusmods.com/skyrimspecialedition/mods/31054). This means that you will have to install *STEP: Core for Skyrim Special Edition* first before following this guide. Almost everything in this build is optional, meaning you can use parts of it if that is what you want.

**The mods featured in this build are chosen to be immersive and realistic. Realistic in a fantasy setting means believable. The mods should feel like they expand or enhances vanilla Skyrim, like they could have been there from the beginning**

**This build is made to be easy to install. When you are done installing STEP Core, you should have enough knowledge to install this build.**
- No LOOT rules, every conflict is resolved with the patches. Run LOOT and you are done.
- No bashed patch. Every level list conflict is fixed in the patches.
- No merging of mods. Every patch is esl-flagged to make sure the plugin limit count is not reached.
- Advanced fomod installer for the patches. No need to actively choose patches, the fomod does the work for you.

Visit the [STEP forums](https://forum.step-project.com/topic/14603-dreads-step-se-core-addon/)  if you have any questions.

**With this modular STEP build you will get**
- New weapon textures
- New armors
- New weapons
- Realistic female body compatible with popular skin and armor mods
- Overhauled skills and perks
- Overhauled magic, races, standing stones, werewolves and vampires
- New, tougher bandits, dragons and enemies
- New NPC's and followers
- New experience system with slower leveling
- New class system
- New lands and quests
- New and altered towns and villages
- Lightweight survival mod, the survival mod from Bethesda Creation Club.
- Enhanced Lighting For ENB is replaced by Luminosity that has increased ambient lighting for those that think ELE is too dark.
- Bigger trees for truly immersive forrests
- …more

**The STEP guide is in beta and this mod list will remain in beta/WIP for as least as long as STEP is in beta. For now, consider this a work in progress.**

These patches replaces the STEP patch. It comes with a neat FOMOD installer that automatically chooses what to install. The patches consists of a huge bunch of esl-flagged plugins. Since they are esl-flagged you do not have to worry about the old plugin count limit. Keeping the patches separated in different plugins helps during development when adding, testing and replacing mods. This also makes both STEP: Core and this mod list mostly modular. There are a few exceptions:
- You need to use the Unofficial Skyrim Special Edition Patch
- Cloaks of Skyrim and Winter is coming should be used together or not at all for the patches to work.


Note that records from the Particle patch is not forwarded since the plugin is obsolete. ENB users should use [ENB Helper](https://www.nexusmods.com/skyrimspecialedition/mods/23174)

The patches are checked against the STEP patch to make sure everything that it patches is patched by these patches too.

**Acronyms that are used in the guide:**
CACO = Complete Alchemy & Cooking Overhaul\
USSEP = Unofficial Skyrim Special Edition Patch\
WACCF = Weapons, Armor, Clothing & Clutter Fixes\
CCOR = Complete Crafting Overhaul Remade\
CFTO = Carriage and Ferry Travel Overhaul\
SMIM = Static Mesh Improvement Mod\
ICAIO = Immersive Citizens – AI Overhaul\

# Instructions
1. Install STEP SE: Core but do not install the STEP patch.
2. Install xEdit https://www.nexusmods.com/skyrimspecialedition/mods/164 and add it as an executable in Mod Organizer.
3. Install my mod list and place the mods after the STEP guide, letting my listed mods overwrite the STEP guide and DynDOLOD resources. When you install mods, always install the main file and update files if you are not explicitly told not to.
4. Run LOOT.
5. Run DynDOLOD following the instructions from the STEP guide,
6. Run FNIS and check the box for TK Dodge / Ultimate combat if any of those mods are used. Instructions are in the STEP guide.
5. Build body and armor meshes using BodySlide following these simple instructions:
>1. Run BodySlide through Mod Organizer
>2. In the *Outfit/Body* dropdown menu, choose *CBBE NeverNude* (this will also prevent NSFW images).
>3. In the preset menu, choose what suits you. The preset you choose should end with the word ‘outfit’. I recommended the presets *Pear (outfit), Natural (outfit), CBBE Slim (outfit), UNP Natural (outfit), Thief (outfit)* or *Warrior (outfit)*.
>4. Tick the checkbox *Build Morphs*.
>5. Click the button *Build* to build the body.
>6. Click on the spyglass at the field Group filter and choose *Choose groups*.
>7. Check the following and click ok: *CBBE vanilla outfits, Frankly HD, Immersive Armors SSE CBBE, WACCF*.
>8. Click the button *Batch build…*
>9. Click *build* to build armor meshes.
>10. Make sure no physics options are checked. Check all Frankly options. Click *ok* and close BodySlide. The meshes that has been built are placed in Mod Organizers overwrite folder and can be moved to a new mod folder if you choose to.
6. Install the mod [Unlimited Bookshelves Patch Generator](http://https://www.nexusmods.com/skyrimspecialedition/mods/19160). Follow the instructions on the Nexus page to build an Unlimited Bookshelves patch.

# The actual mod list
## Character Appearance
*This section replaces the vanilla body with the CBBE body. The CBBE body is chosen because of its versatility. Recommended presets makes the body look realistic or vanilla-ish. Using a body replacer is the only way to make sure the female body is compatible both with skin texture replacers and with mods that add new armors to the game.*\
**Uninstall 'Vanilla Body with UNP Textures' and 'Tempered Skins for Females' if you want to use the CBBE body.
#### [Caliente’s Beautiful Bodies Enhancer -CBBE-](https://www.nexusmods.com/skyrimspecialedition/mods/198)
*NSFW warning*\
Install the main file, the update file and the optional file ‘CBBE ESL-flagged .esp’.
In the main installer, choose:
- Body Shape: Slim
- Underwear options: NeverNude
- Outfit options: Vanilla outfits
- SKEE (RaceMenu): RaceMenu Morphs
#### [BodySlide and Outfit Studio](https://www.nexusmods.com/skyrimspecialedition/mods/201)
Check the nexus page for the instructions to add this mod as an executable in Mod Organizer (in short, install as a normal mod and right click the executable in MO:s data tab. Choose add as executable).
#### [CBBE Presets Compendium](https://www.nexusmods.com/skyrimspecialedition/mods/11229)
*NSFW warning*\
Install the main file
#### [KS Hairdos SSE](http://www.nexusmods.com/skyrimspecialedition/mods/6817)
#### [Maevan2’s Mature Skin Texture for CBBE – UNP](https://www.nexusmods.com/skyrimspecialedition/mods/26017)
*NSFW warning*\
Use these CBBE-compatible skin textures instead of *Tempered Skin* if you use the CBBE body. If you don’t use this skin texture you will have to find other CBBE compatible skin textures or not use CBBE.
In the installer, choose what you want, for example: high, CBBE slim, medium, lips, complexions, young, mature.
#### [Salt and Wind – Rough Hair for KS Hairdos SE](http://www.nexusmods.com/skyrimspecialedition/mods/16582)
#### [TDN Equipable Horns SE](http://www.nexusmods.com/skyrimspecialedition/mods/9224)
Yes, some Bosmer have antlers.\
*"It is also common among the Bosmer to wear decorative antlers on their foreheads, although rarely, individuals with real, magically-grown antlers can also be encountered."* [source](https://en.uesp.net/wiki/Lore:Bosmer) \
Skip this mod if you do not intend to use horns or antlers for your character.

## Items – Armor, Clothing, Accessories & Weapons
*Remember to use both Cloaks of Skyrim and Winter is coming if you want new cloaks in the game.
#### [Bandolier - Bags and Pouches Classic](http://www.nexusmods.com/skyrimspecialedition/mods/2417)
#### [Cloaks of Skyrim](http://www.nexusmods.com/skyrimspecialedition/mods/6369)
Install the main version
#### [Cloaks of Skyrim Ultra HD SSE](http://www.nexusmods.com/skyrimspecialedition/mods/29258)
#### [Faction Crossbows SE](http://www.nexusmods.com/skyrimspecialedition/mods/4047)
#### [Heavy Armory - New Weapons](https://www.nexusmods.com/skyrimspecialedition/mods/6308)
#### [Immersive Armors](http://www.nexusmods.com/skyrimspecialedition/mods/3479)
#### [Immersive Armours - SSE CBBE BodySlide](https://www.nexusmods.com/skyrimspecialedition/mods/22382)
Install if you use Immersive Armors with CBBE.
#### [Immersive Weapons](https://www.nexusmods.com/skyrimspecialedition/mods/16788)
#### [Royal Armory - New Artifacts](http://www.nexusmods.com/skyrimspecialedition/mods/6994)
#### [Ruin's Edge](http://www.nexusmods.com/skyrimspecialedition/mods/12792)
#### [The Staff Of Sheogorath](http://www.nexusmods.com/skyrimspecialedition/mods/14468)
#### [Unique Uniques SE](https://www.nexusmods.com/skyrimspecialedition/mods/3334)
Install main file
#### [Winter Is Coming SSE - Cloaks](http://www.nexusmods.com/skyrimspecialedition/mods/4933)
Install the patch for Cloaks of Skyrim only if you are not using Complete Crafting Overhaul Remade.

## Items - Weapons Armor and Clothing - Cathedral Concept
*This whole section should be used together or not at all.*
*Disable the following STEP mods:*
- *LeanWolf's Better-Shaped Weapons (included in the mod)*
- *aMidianBorn Book of Silence*
- *aMidianBorn Blades Armor SSE Patch*
- *aMidianBorn imperial light and studded*
- *aMidianBorn stormcloak officer armour*

#### [Weapons Armor and Clothing - Cathedral Concept](https://www.nexusmods.com/skyrimspecialedition/mods/20199)
Choose CBBE in the installer if you use CBBE.
Hide or delete the file _CalienteTools\BodySlide\ShapeData\CBBE Vanilla\Body\Ebony.nif_ since this mesh is causing issues.
#### [RUSTIC CLOTHING - Special Edition](https://www.nexusmods.com/skyrimspecialedition/mods/4703)
This mod is installed with STEP. Simply place it here in the load order.
#### [Frankly HD Dragonbone and Dragonscale - Armor and Weapons HQ](https://www.nexusmods.com/skyrimspecialedition/mods/25110)
This mod is installed with STEP. Simply place it here in the load order.
#### [Frankly HD Thieves Guild Armors HQ](https://www.nexusmods.com/skyrimspecialedition/mods/19953)
This mod is installed with STEP. Simply place it here in the load order.
#### [Frankly HD Masque of Clavicus Vile](https://www.nexusmods.com/skyrimspecialedition/mods/28565)
#### [Frankly HD Imperial Armor and Weapons](https://www.nexusmods.com/skyrimspecialedition/mods/20848)
Install the Pants ans Sleeves patch and the Better-Shaped Weapons patch.
#### [Frankly HD Nightingale Armor and Weapons](https://www.nexusmods.com/skyrimspecialedition/mods/18560)
Install the CBBE patch and the Better-Shaped Weapons patch.
#### [Frankly HD Dawnguard Armor and Weapons](https://www.nexusmods.com/skyrimspecialedition/mods/19663)
Install the CBBE patch.
#### [Frankly HD Miraak](https://www.nexusmods.com/skyrimspecialedition/mods/19699)
Install the CBBE patch.
#### [Frankly HD Shrouded Armor](https://www.nexusmods.com/skyrimspecialedition/mods/18785)
#### [Improved Closedfaced Helmets](https://www.nexusmods.com/skyrim/mods/15927)
Download Improved Closefaced Helmets Patch v1 and choose SkyRealism Shiny in the installer. Install this as a new mod, making sure to not overwrite or merge it with the mod installed with STEP.

## Enemies
#### [Deadly Dragons](http://www.nexusmods.com/skyrimspecialedition/mods/23723)
Choose Loremonger version with patches for Diverse Dragons, Splender Dragons and Wyrmstooth.
#### [Diverse Dragons Collection SE](http://www.nexusmods.com/skyrimspecialedition/mods/695)
#### [OBIS SE - Organized Bandits In Skyrim Special Edition](http://www.nexusmods.com/skyrimspecialedition/mods/4145)
Install main file and OBIS SE Patrols addon.
#### [Skyrim Revamped - Complete Enemy Overhaul](http://www.nexusmods.com/skyrimspecialedition/mods/14598)
#### [Splendor – Dragon Variants SE](http://www.nexusmods.com/skyrimspecialedition/mods/9670)

## New characters - NPC's, followers and encounters
#### [Immersive Patrols SE](http://www.nexusmods.com/skyrimspecialedition/mods/718)
#### [Immersive World Encounters SE](https://www.nexusmods.com/skyrimspecialedition/mods/18330)
#### [INIGO](http://www.nexusmods.com/skyrimspecialedition/mods/1461)
#### [Interesting NPCs SE](https://www.nexusmods.com/skyrimspecialedition/mods/29194)
#### [Interesting NPCs (3DNPC) character Zora Fairchild's voice boosted](http://www.nexusmods.com/skyrimspecialedition/mods/16090)

## Gameplay - AI & Combat
#### [TK Dodge SE](https://www.nexusmods.com/skyrimspecialedition/mods/15309)
#### [Ultimate Combat SE](http://www.nexusmods.com/skyrimspecialedition/mods/17196)

## Gameplay - Immersion & Role-playing
#### [Campfire - Complete Camping System](http://www.nexusmods.com/skyrimspecialedition/mods/667)
Hide or delete the file _SKSE/Plugins/PapyrusUtil.dll_. It is outdated and we need to use the newer one from PapyrusUtil SE that is installed with STEP Core.
#### [Campfire and Frostfall - Unofficial SSE Update](http://www.nexusmods.com/skyrimspecialedition/mods/17925)
#### [Carriage and Ferry Travel Overhaul](http://www.nexusmods.com/skyrimspecialedition/mods/8379)
Install patches for Immersive Citizens - AI Overhaul and Dawnstar.
#### [Daedric Voices](https://www.nexusmods.com/skyrimspecialedition/mods/32090)
Install the main file and the Growl patch.
#### [ElSopa - Campfire HD SE](http://www.nexusmods.com/skyrimspecialedition/mods/24511)
#### [Lock Related Loot](http://www.nexusmods.com/skyrimspecialedition/mods/11342)
#### [Nether's Follower Framework](http://www.nexusmods.com/skyrimspecialedition/mods/18076)
Choose the following: 
- Followers avoid traps
- Interesting NPC support
- Relationship Dialogue Overhaul
- RDO Comments

## Gameplay - Quests & Stories
#### [The Brotherhood of Old - Open Beta - SSE](http://www.nexusmods.com/skyrimspecialedition/mods/15322)
#### [Clockwork (SSE)](http://www.nexusmods.com/skyrimspecialedition/mods/4155)
#### [Dawnguard and Clan Volkihar Epilogues](http://www.nexusmods.com/skyrimspecialedition/mods/12098)
#### [The Forgotten City](http://www.nexusmods.com/skyrimspecialedition/mods/1179)
#### [The Gray Cowl of Nocturnal SE](http://www.nexusmods.com/skyrimspecialedition/mods/4509)
#### [The Gray Cowl of Nocturnal SSE - HD pack](http://www.nexusmods.com/skyrimspecialedition/mods/7644)
#### [Gray Cowl of Nocturnal Alikr Flora Overhaul SE](http://www.nexusmods.com/skyrimspecialedition/mods/10141)
#### [The Gray Cowl of Nocturnal SE - Addons and Patches](http://www.nexusmods.com/skyrimspecialedition/mods/19724)
Install the WACCF patch. The USSEP-patch isn't needed if you use SMIM, CFTO or Realistic Water 2.
#### [Helgen Reborn](http://www.nexusmods.com/skyrimspecialedition/mods/5673)
#### [Moon and Star](http://www.nexusmods.com/skyrimspecialedition/mods/4301)
#### [Moonpath to Elsweyr SSE](http://www.nexusmods.com/skyrimspecialedition/mods/4341)

## Gameplay - Skills, Perks & Magic
*The mods in this section edits the skill trees and for that reason they are incompatible with other mods that does this. It is possible to make patches and merge skill trees but I prefer to stick to the mod authors vision and not mix different skill and perk mods with each other. If you use the mods in this section, uninstall **Complete Alchemy and Cooking Overhaul** and **Smithing Perks Overhaul** which are the two Skill and perk mods featured in the STEP guide. Users should also consider uninstalling Weapons Armor Clothing Clutter Fixes since it also edits perks. Some features of **WACCF** are replaced by **Adamant** so they should work together but I prefer to simply not use **WACCF**, which means that **Complete Crafting Overhaul Remade** has to be uninstalled to since it depends on **WACCF**. In the section following this one you will find mods that replaces functionallity lost when uninstalling **CACO** and **CCOR**.*
#### [Adamant - A Perk Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/30191)
Check the sticked post in the posts section to find the beta for 2.0
#### [Aetherius - A Race and Standing Stone Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/26686)
#### [Mysticism - A Magic Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/27839)
Install the main file and the Survival patch. Do not install the Audio Overhaul Skyrim patch.

## Gameplay - Replcaing CACO and CCOR
*If you have uninstalled Complete Alchemy and Cooking Overhaul and/or Complete Crafting Overhaul remade, use these replacement mods.*
#### [Ars Metallica - Smithing Enhancement](https://www.nexusmods.com/skyrimspecialedition/mods/321)
Replaces functionallity from CCOR.
#### [Ragdoll Paralysis Redux SE](https://www.nexusmods.com/skyrimspecialedition/mods/13575)
Replaces functionaillity from CACO.
#### [Wiseman303's Flora Fixes](https://www.nexusmods.com/skyrimspecialedition/mods/28197)
Replaces functionaillity from CACO. Install the main file and the patch for SMIM.

## Gameplay - Races, Classes & Shouts
#### [Class Overhaul Re-Imagined (SkyRem - Cori)](https://www.nexusmods.com/skyrimspecialedition/mods/24808)
#### [Experience](http://www.nexusmods.com/skyrimspecialedition/mods/17751)
Do not activate this mod yet. Waith until you have left the first cell of Alternate Start to avoid getting experience when different mods do their initial setup routines.
#### [Growl - Werebeasts of Skyrim](http://www.nexusmods.com/skyrimspecialedition/mods/31245)
#### [Sacrosanct - Vampires of Skyrim](http://www.nexusmods.com/skyrimspecialedition/mods/3928)
#### [Thunderchild - Epic Shouts and Immersion](http://www.nexusmods.com/skyrimspecialedition/mods/1460)

## Interface
#### [UIExtensions](https://www.nexusmods.com/skyrimspecialedition/mods/17561)
This is needed by Class Overhaul Re-Imagined.

## Locations
#### [Bells of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/10495)
Install the patch for Immersive Citizens - AI overhaul.
#### [Falskaar](http://www.nexusmods.com/skyrimspecialedition/mods/2057)
#### [Immersive College of Winterhold](http://www.nexusmods.com/skyrimspecialedition/mods/17004)
Choose 
- desaturated book covers
- RLS SSE Patch
- Better Dynamic Snow Patch
- Skyrim Project Optimization SSE Patch.
#### [Immersive Dawnguard Dayspring Pass SE](http://www.nexusmods.com/skyrimspecialedition/mods/4126)
#### [Solitude Skyway](http://www.nexusmods.com/skyrimspecialedition/mods/8250)
#### [Windhelm Lighthouse](http://www.nexusmods.com/skyrimspecialedition/mods/8453)
#### [Wyrmstooth SSE](https://archive.org/details/wyrmstooth1.18SSE)

## Locations - Arthmoor's towns and villages
#### [Darkwater Crossing](https://www.nexusmods.com/skyrimspecialedition/mods/326)
#### [Dragon Bridge](https://www.nexusmods.com/skyrimspecialedition/mods/8683)
#### [Dawnstar](https://www.nexusmods.com/skyrimspecialedition/mods/13607)
#### [Falkreath](https://www.nexusmods.com/skyrimspecialedition/mods/21266)
#### [Karthwasten](https://www.nexusmods.com/skyrimspecialedition/mods/350)
#### [Ivarstead](https://www.nexusmods.com/skyrimspecialedition/mods/349)
#### [Keld-Nar](https://www.nexusmods.com/skyrimspecialedition/mods/14353)
#### [Kynesgrove](https://www.nexusmods.com/skyrimspecialedition/mods/351)
#### [Rorikstead](https://www.nexusmods.com/skyrimspecialedition/mods/16881)
#### [Shor's Stone](https://www.nexusmods.com/skyrimspecialedition/mods/354)
#### [Soljund's Sinkhole](https://www.nexusmods.com/skyrimspecialedition/mods/358)
#### [Telengard](https://www.nexusmods.com/skyrimspecialedition/mods/17423)
#### [The Fall of Granite Hill](https://www.nexusmods.com/skyrimspecialedition/mods/22512)
#### [Whistling Mine](https://www.nexusmods.com/skyrimspecialedition/mods/367)

## Audiovisual - Lighting & Weather 
#### [Luminosity Lighting Overhaul - The Cathedral Concept](https://www.nexusmods.com/skyrimspecialedition/mods/16830)
This mod is similar to *Enhanced Lighting For ENB* that is installed by STEP. Since they edit the same records they are incompatible. Uninstall *Enhanced Lighting For ENB*. Luminosity makes the ambient light brighter than *Enhanced Lighting For ENB* does. Dark dungeon and interior nerds should stick with *ELE*.

## Audiovisual - Trees
*To use the mods in this section, deactivate Enhanced Vanilla Trees from STEP SE: Core.*
#### [Realistic Aspen Trees SE](http://www.nexusmods.com/skyrimspecialedition/mods/4423)
Choose 2k or 4k. Choose LodGen billboards (doesn't really matter, they will be overwritten by the next mod)
#### [Simply Bigger Trees SE](http://www.nexusmods.com/skyrimspecialedition/mods/5281)
Install the Realistic Aspen trees version of this mod.
#### [HQ Tree Bark](http://www.nexusmods.com/skyrimspecialedition/mods/6556)
Choose the options you prefer. Install the Simply Bigger Trees patch.
#### [No More Hanging Moss](https://www.nexusmods.com/skyrimspecialedition/mods/16426)
Install _Hanging moss removal - partial - the moss around trees -_ mesh edits only. Without this mod you would get floating moss hanging from resized trees.

## STEP SE: Core Changes
*Some updates to STEP mods are required to make them compatible with other mods in this list*
#### [Embers HD](http://www.nexusmods.com/skyrimspecialedition/mods/14368)
Reinstall and add the Campfire patch.
#### [Realistic Water Two](http://www.nexusmods.com/skyrimspecialedition/mods/2182)
Reinstall and add patches for Falskaar and Wyrmstooth.
#### [Farmhouse Chimneys](http://www.nexusmods.com/skyrimspecialedition/mods/8766)
Reinstall and choose all relevant patches.
#### [FAR - Forgotten Argonian Roots](http://www.nexusmods.com/skyrimspecialedition/mods/1704)
Reinstall using the STEP instructions but choose CBBE body instead of default for females.
#### [Lanterns Of Skyrim II](https://www.nexusmods.com/skyrimspecialedition/mods/30817)
Reinstall using STEP options and patches for Arthmoor's villages.
#### [Enhanced Lighting for ENB (ELE) - Special Edition](https://www.nexusmods.com/skyrimspecialedition/mods/1377)
Install the patches for Helgen Reborn and Falskaar. No other patches are needed. Uninstall if you use *Luminosity*.
#### [Kryptopyr's Patch Hub](http://www.nexusmods.com/skyrimspecialedition/mods/19518)
Move this mod to my patches section. Refer to that section for install options.
#### [Landscape fixes for grass mods](https://www.nexusmods.com/skyrimspecialedition/mods/9005)
Reinstall and add patches for Helgen Reborn, Moon and Star and all Arthmoor's villages.

## Patches
#### [Falskaar - Addons and Patches](http://www.nexusmods.com/skyrimspecialedition/mods/19454)
Choose 
- Bug Fixes
- Boat Location Patch
- Fast Travel Addon
- Unique Region Names Addon
#### [Immersive College of Winterhold - Not so fast Mage Guild Patch](https://www.nexusmods.com/skyrimspecialedition/mods/18731)
#### [Interesting NPC's Imperious Patch](http://www.nexusmods.com/skyrimspecialedition/mods/29271)
#### [Kryptopyr's Patch Hub](http://www.nexusmods.com/skyrimspecialedition/mods/19518)
The fomod installer will identify which patches you need and select them automatically. Do not install the *WACCF - Survival Mode Patch*.
#### [Moonpath to Elsweyr Sky and Lightning fix](http://www.nexusmods.com/skyrimspecialedition/mods/18683)
#### [Unofficial Moonpath to Elsweyr Patch](http://www.nexusmods.com/skyrimspecialedition/mods/15882)
#### [Unofficial Skyrim Creation Club Content Patches](http://www.nexusmods.com/skyrimspecialedition/mods/18975)
Choose the Unofficial Skyrim Survival Patch.
#### [Weapons Armor Clothing and Clutter Fixes - CBBE Patch](https://www.nexusmods.com/skyrimspecialedition/mods/19176)
#### [QUASIPC - Qwinn's Unified Automated Self Installing Patch Compendium](http://www.nexusmods.com/skyrimspecialedition/mods/18369)
Install the *Interesting NPCs - CACO patch* if you use *Complete Alchemy and Cooking Overhaul*.
#### [Dread's modlist patches](https://github.com/dreadflopp/dreads_modlist_patches)
To download, click the button Clone or download and choose download zip.
The fomod installer will automatically select all mods you use. Select the tweaks you want to use.