# Botw Stats:
A mod that restores all Champion and Amiibo weapons back to their Botw damage values.
Except bows as they actually weren't nerfed at all (I think), other than the Dusk Bow (Twilight Bow) not shooting light arrows anymore.
Haven't changed anything with shields

## Table of Contents

- [Versions](#versions)
- [Champion and Amiibo Weapons](#championandamiiboweapons)
   - [Champions](#champions)
   - [Amiibos](#amiibos)
- [Installation](#installation)
  - [Switch](#switch)
  - [Yuzu](#yuzu)
  - [Ryujinx](#ryujinx)
- [Compatibility](#compatibility)
- [Changes](#changes)
   - [BotwStatsNormal](#botwstatsnormal)
   - [BotwStatsInfDur](#botwstatsinfdur)

## Versions

- Buffed normal durability version named `BotwStatsNormal` for those who only want the damage increase
- Buffed unbreakable version named `BotwStatsInfDur` for those who want to just destroy Hyrule

## Champion and Amiibo Weapons

### Champions

- Scimitar of the Seven
- Boulder Breaker
- Lightscale Trident
- Great Eagle Bow

### Amiibos

- White Sword of the Sky (Goddess Sword)
- Sword of the Hero (Sword??)
- Sea-Breeze Boomerang
- Dusk Bow (Twilight Bow)
- Dusk Claymore (Sword of the Six Sages)
- Biggoron's Sword
- Fierce Deity Sword

## Installation

### Switch

Your Switch must be hacked/modded to install this mod, and you must be running
Atmosphere 1.5.4 or later. Copy the `romfs` folder into the
`/atmosphere/contents/0100F2C0115B6000` folder on your SD card. It should look
like `/atmosphere/contents/0100F2C0115B6000/romfs`.

### Yuzu

Open Yuzu. Right-click Tears of the Kingdom > Open Mod Data Location. Copy the
`BotwStatsNormal` or `BotwStatsInfDur` folder into that folder. It should look like
`load/0100F2C0115B6000/BotwStatsNormal/romfs` or `load/0100F2C0115B6000/BotwStatsInfDur/romfs`.

### Ryujinx

Open Ryujinx. Right-click Tears of the Kingdom > Open Mods Directory. Copy the
`BotwStatsNormal` or `BotwStatsInfDur` folder into that folder. It should look like
`mods/contents/0100F2C0115B6000/BotwStatsNormal/romfs` or `mods/contents/0100F2C0115B6000/BotwStatsInfDur/romfs`.

## Compatibility

This mod was tested with Tears of the Kingdom v1.1.1 . Probably won't work with v1.0.0 but should work with v1.1.0 and v1.1.2

This mod is not compatible with any mod that alters any of the following files:
### BotwStatsNormal
- `romfs/Pack/Actor/Weapon_Sword_052.pack.zs`.
- `romfs/Pack/Actor/Weapon_Sword_057.pack.zs`.
- `romfs/Pack/Actor/Weapon_Sword_058.pack.zs`.
- `romfs/Pack/Actor/Weapon_Sword_059.pack.zs`.
- `romfs/Pack/Actor/Weapon_Lsword_054.pack.zs`.
- `romfs/Pack/Actor/Weapon_Lsword_057.pack.zs`.
- `romfs/Pack/Actor/Weapon_Lsword_059.pack.zs`.
- `romfs/Pack/Actor/Weapon_Lsword_060.pack.zs`.
- `romfs/Pack/Actor/Weapon_Spear_050.pack.zs`.
- `romfs/RSDB/PouchActorInfo.Product.110.rstbl.byml.zs`.
### BotwStatsInfDur
- `romfs/Pack/Actor/Weapon_Bow_028.pack.zs`.
- `romfs/Pack/Actor/Weapon_Bow_072.pack.zs`.
- `romfs/Pack/Actor/Weapon_Sword_052.pack.zs`.
- `romfs/Pack/Actor/Weapon_Sword_057.pack.zs`.
- `romfs/Pack/Actor/Weapon_Sword_058.pack.zs`.
- `romfs/Pack/Actor/Weapon_Sword_059.pack.zs`.
- `romfs/Pack/Actor/Weapon_Lsword_054.pack.zs`.
- `romfs/Pack/Actor/Weapon_Lsword_057.pack.zs`.
- `romfs/Pack/Actor/Weapon_Lsword_059.pack.zs`.
- `romfs/Pack/Actor/Weapon_Lsword_060.pack.zs`.
- `romfs/Pack/Actor/Weapon_Spear_050.pack.zs`.
- `romfs/RSDB/PouchActorInfo.Product.110.rstbl.byml.zs`.

## Changes
### BotwStatsNormal

#### Longswords:
- Boulder Breaker - 60
- Dusk Claymore (Sword of the Six Sages) - 48
- Biggoron's Sword - 50
- Fierce Diety Sword - 60

#### Swords
- Scimitar of the Seven - 32
- White Sword of the Sky (Goddess Sword) - 28
- Sword of the Hero (Sword??) - 22
- Sea-Breeze Boomerang (It's a sword in the game files) - 20

#### Spears
- Lightscale Trident - 22

### Bows
- Dusk Bow (Twilight Bow - Shoots straight like in Botw

### BotwStatsInfDur
- Swords, Longswords, and Spears have their buffed damage
- Dusk Bow Shoots straight
- Swords, Longswords, Spears, and Bows Are unbreakable
