# WrathExtended
Patch 3.4 and onwards, a thought experiment what could have been.  
Code is here https://github.com/PolarCookie/TrinityCore/tree/3.4.0+  

Keywords; Class Diversification, Item/Stat homogenization!

# Design Philosophy (in no particular order)
1) If A counters B, then B can not counter A, you need a C to counter A and B might counter C.
2) Stats need to matter, you can't have a situation where ~35% of a class' total damage output is unaffected by critical chance as is the general case for Affliction Warlocks.
3) Make gear matter more by removing all passive stat modifiers from talent trees, also buffing stats from gear to compensate.
4) Make buffs more unique and rare, not everyone has one.
5) Make dots more unique and rare, not everyone has one.
6) The aim of this project is not to make WotLK with some tweaks but to make as many corrections to the underlying fundamental problems of the game. To Redesign it from scratch as much as possible.
7) the overspecialization of talents will be changed; you shouldn't need to put more than 31 points into your main talent tree leaving 20 points free elsewhere (the ratio is important, not the real numbers).
8) Classes will have less abilities and do more with them
9) Tanks will not be able to hold agro on dps in heavy AoE.
10) Parry will be removed, it's redundant as avoidance when dodge exists and it's only purpose then is to randomly kill the tank which is not very interesting. By default of this decision tank single target threat will increase and we'll balance it down accordingly.
11) If a mechanic is in the game, I as a player should be able to build around it in some way, if I can't interact with a game mechanic, it should not exist. Level based partial resists and glancing blows are to be removed from the game because of this.
12) We're assuming people have good ping, many CC abilities will be heavily nerfed; no more 10 sec stuns or 8 sec silences.

# Classes (in no particular order)
## Shaman
### Totems
Each shaman will now only use 1 totem at a time; in Vanilla and TBC each class buff was group wide and fairly unique but in WotLK all buffs are now raid wide and heavily homogenized. This leads to a situation where the only totem that matters is Wrath of Air as every other are either negligible weak (lol Healing Stream Totem), situational (Earthbind totem, resistance totems) or redundant (the rest of them).
### Elemental Spirits
Elemental guardians will be unchained from totems and work as a regular guardian cooldown (like Shadow Fiend or mage Water elemental). They will share cooldown. Fire Elemental Spirit will be for dps, Earth Elemental Spirit as a semi tank and shield buff, Air Elemental Spirit will do moderate damage and knock everyone randomly around the place with strong gust of winds; it will be used to break and disrupt enemy groups in pvp, Water Elemental Spirit will be assisting in Healing.
### Restoration
I want resto shaman to be the smart proc healer, to build into the mechanic of Chain Healing. This will be done through buffing Healing Stream Totem significantly. This will conflict with the 1 totem rule by design.
While the total HPS will be less than other classes, resto shamans will be needed to ease the overall burden, along with disc priests, on the other healers by being able to rapidly reach more targets than the others can.
### Enhancement
I don't have any thoughts at this point
### Elemental
Will stay mostly the same, but Totem of Wrath will now function as Demonic Pact which will be removed.

## Priest
### Holy
Renew will be removed, in favour of making rdruid the more unique HoT healer. 
### Discipline
The Legion Disc Priest was fun but the wrong way to take that class, it should be focused into the "shield" healer. It needs something more to do than just clicking PW:S through the raid, but not much. In general all absorb effects will be changed to <100% damage absorbed for a total of X; this is to synergize better with other healers and to give disc the niche of being the healer that smooths out rough edges but not completely invalidate bringing another raid healer.  
Applying PW:S, or a different shield spell, raid wide should be made quicker, by lowering the GCD to 1 second baseline.
### Shadow
I think it was a mistake to have the light/shadow duality in priests, it would have been better to make a holy damage dps spec and leave the shadow dot caster to affliction warlocks. Short of that Spriests will return to the TBC model of gaining mana based on damage done, vampiric embrace will be removed as healing is reserved for healers.

## Paladin
### Holy
Beacon of Light is getting the axe! It completely breaks the healing game in fundamental ways. Healers should apply healing where their focus is, in general all random "smart" healing procs will be removed (except for rshaman), thus if healers collectively lose focus on a prime target that's taking damage he's going to die! A good example of why BoL is broken is Gurtogg Bloodboil in Black Temple; he will first stack a damaging debuff on tanks, then switch to a phase where he targets a random raid member who needs all the healers focus to stay alive, except that the tanks are still taking damage from the stacked debuff! If all the healers switch to the focused raid member the tanks will die from the debuff, but if you bring 2 hpalas and each set their beacon to the tank the focus phase is now trivial!

### Protection
Argent Defender is removed; it's to OP, Divine Guardian/Sacrifice is expanded upon, Sacred Shield is removed; if you want a shield bring a disc priest. Prot Paladin will stay as the best AoE tanks but AoE tank threat in general will be nerfed. In general I want more active mitigation from tanks so both cooldown and duration of Holy Shield is reduced to 6 seconds.

### Retribution
It's ok I guess?

## Warrior
Warriors are supposed to be a high mobility melee fighter, charge will be useable in any stance and in combat but hamstring and piercing howl will be removed. One major change is that switching stances will not change rage at all, this design decision never made sense to me. I want to experiement with reducing rage cost on all warrior abilities by 50%, you can rage starve yourself to easially and I want to look into this.

### Protection
I miss active mitigation for tanks, TBC Protection Warrior being my favorite tank to play. Threat is a joke in WotLK unless the tank is garbage (and I've seen a WotLK Prot Warrior refuse to use Heroic Strike, and he did fine for the *most* part), this is in part that tanks only produce threat with the rare occasional defensive ability. Having to juggle threat and defense takes mind space which gives tanks their meaningful edge to seperate good from bad.  

Shield Block will return to the Vanilla/TBC version of +75% block chance for 2 hits, 6 sec duration on 5 sec cooldown.

Sword And Board will lose it's random proc chance, this is my biggest gripe with Wrath Protection Warrior that ruins the spec for me, even tho I consider Warbringer to be the single best talent Blizzard ever made. I just don't like the random interruption of *flow* which I highly adore TBC Protection Warrior for.  

Shockwave will be removed, Thunder Clap will reduce melee attack speed by max 10% talented and demoralizing shout will reduce damage by 5%

I want to add a talent to Protection Warrior letting block value mitigate spell damage.

### Fury
WotLK fury gameplay is decent and will remain but some balancing will be done, especially wrt ARP

### Arms
Bladestorm will be removed, instead some mechanic will reduce the cooldown on normal whirlwind.

## Druid
### Feral dps
Other than being a very restricted talent build feral gameplay is mostly fine as is, but it's trying to spin to many plates giving inconsistent results. At least 1 ability from the rotation will be removed and shred will be able to hit from any angle (why this change was given to mutilate but not shred has always been a mystery to me).

### Feral tank
Savage defense didn't work out very well imo, in the spirit of active mitagation i'd rather have an ability that increases your healing taken while it's up; Bears should be big meat shields taking huge hits but also soaking a lot of healing.

### Restoration
In the beginning there was Rejuvenation and Regrowth, then Lifebloom in TBC and Wild Growth in WotLK. How many HoTs does a spec really need? Wild Growth server a purpose in being the rapid raid wide healing but Lifebloom never contributed anything other than being an extra button and horribly imbalanced in pvp.
In the spirit of doing more with less RDruids will focus on Rejuv (HoT), Nourish (casted healing with bonus on HoT'ed targets), Swiftmend (instant healing on HoT'ed targets) and Wild Growth (multitarget HoT). The rest will be phased out if not completly removed.

### Balance
Moonkins biggest issue is the inconsistency due to Eclipse, will be considered.

## Death Knight
Let me start by saying that Blood as the tank spec was a mistake from the beginning, FROST IS THE REAL TANK SPEC!  
Both specs suffer by playing more or less like their dps counterparts, except for the added rune strikes.  

Frost I want to give a Frost Barrier ability, its main active mitigation will casing itself in ice and absorbing damage.

Blood in general has one major issue and that is self healing; the holy trinity is tank, dps and healer, or durability, damage and healing. Balance would suggest pick 2 of 3, Blood is greedy and takes all 3!  


## Warlock
### Affliction
+ **Pandemic** now applies crit ability to Curse of Agony, Drain Life and Drain Soul.
> CoA, Drain Life and Drain Soul not critting is an asymmetry which severly hurts crit rating for affliction warlocks, where crit/spirit gear becomes garbage to be avoided.

+ **Seed of Corruption** now is now removed in favour of focusing on corruption.
> I personally find the 3.3.5 SoC to be incredibly boring, all you do is spam or spam-tab and pray tanks can hold agro. It doesn't synergise nicely with anything in the warlock arsenal, except Shadowflame if you want to trigger them. It is a massive break from the usual affliction rotation of managing DoTs and debuffs. It belongs to a spec designed around building up damage potential which is later triggered, not affliction which ramps up steady non-burst damage. 

+ **Everlasting Affliction** can be triggered by Shadowflame.
> Shadowflame triggering Everlasting Affliction is something I wish I had in many cases. Affliction AoE has been limited to either SoC, boring as previously mentioned, or tab casting Corruption on all targets which is a slow, tedious and difficult task to get right. No other class has any AoE rotation as intricate as affli multidotting on 4+ targets.
+ **Shadow Bite** is an On-Next-Auto-Attack type spell, like Heroic Strike.
> This is in preperation for later pet changes where all pets will get 100% haste, crit, penetration, hit/expertise ratings from their masters. It is not neccesary that Felhunter should do a physical melee attack, and it's asymmetrical as the melee attack suffers from armor and glancing blows.

### Demonology
Demonic Pact is removed, I dunno what to do with this spec tbh?

### Destruction
Molten Core and Decimation are now Destruction Talents, the former procs on Immolate. Chaos Bolt is removed.

## Mage
### Arcane
Fine as is

### Frost
Water Elemental is now a Shaman spell, sorry guys!

### Fire
Living Bomb is now the new Seed of Corruption, it fits better thematically for Fire to be creating bombs and blowing them up.

## Rogue
In the spirit of not allowing anyone to counter their counter I'm removing all stuns, slows and Cloak of Shadow from Rogues, but in exchange Vanish has a 20 sec cooldown (subtlety gets 10). The Spirit of Rogue combat is to pick your fights and escape before you get killed, you ambush people, fight 10 seconds, and run away, repeat. Being able to stunlock someone for up to 10 seconds is first of highly unbalanced, unfair and unfun (for the other guy)! All stuns in general are being heavily nerfed to max 2-3 seconds as people's pings are much better now and we're designing a game with that in mind. Cloak of Shadow was the answer to the issue that rogues vanishing were being countered by DoTs, because DoTs could break stealth. Now Stealth will now only be broken by spell hits and DoT ticks will not break it, the rogue still has to deal with soon dying however.
Rogue will keep Gouge and Blind as these will break if you continue damaging the target.

The Rogue specs are mostly fine as is w.r.t. gameplay but they will be rebalanced with the design philosophy.

# Future work
## Stat system
### Level based stats
Primary stats gained each level will be removed, you will gain your stats from gear. Base hp/mana is being kept for the time being but under consideration.
### Crit chance
Racial and int/agi based crit chance will be removed, leaving only crit chance from rating which comes from gear.

### Strength, Agility and Spirit
What is Strength, Agility and Spirit? It depends a lot on which class you pick. In general Strength and Agility ends up being just varying degrees of Attack Power, but Agility is also Critical Chance and Armor, and Strength is also Block Value and Parry (only for DK). Spirit is a total mess, it started out as the OOC regeneration stat, but not fighting is boring so blizzard tried to push it into classes where it didn't belong. First it was %-spirit-to-mp5 (when the mp5 stat was already a thing) and %-spirit-to-power for Priest and Druids. In Wrath it snuck its way to dps speccs as Blizzard wanted to make healer/caster gear interchangable without giving up Spirit. The curious thing about Wrath itemization is how many items for dps classes have spirit on them in T7 and T8, and by T10 Blizzard gave up on the whole idea and gave all caster dps Crit/Haste/Hit on all tier sets.  
The idea of a class-unique stat eventually turned into Mastery, but I never liked the idea of Mastery either.  
*Classes should be differentiated with spells and talents, all stats should be equal across all classes*  
These 3 stats are to be removed and replaced by pure stats doing 1 job and 1 job only.  

### Attack Power
As a consequence of the latter point, Attack Power will now be normalized with Spell Power.

### Penetration
WotLK saw great unification in the stat system; haste/spell hast, crit/spell crit and hit/spell hit were all unified into a single secondary statistic, as the TBC model was severely harming hybrid spec.
However one stat left out was Penetration, it morphed into the %-based armor penetration and spell penetration was done nothing with.
This is the biggest reason why magic based dps dominate early tiers while physical dps catch up hard in T10 as ARP is a increased returns kind of stat.

On the other hand magic users have no penetration for PvE, but bosses still have 15 magic resistance based on level that a Player can't do anything about.  
*If I can't affect or interact with a mechanic it should not be in the game!*  
I want to unify armor and spell resistance, so that all players for all kinds of damage can stack penetration.

### Pets
All pets will gain 100% of the owners Powers, Penetration, Haste, Critical and Hit/Expertise rating.  
Pets will not gain any buffs, but inherit any buffs cast on the player, pets are considered an extension to the player character.

## Spell Scaling
Since the beginning all spells worked on the model of `damage = base + coefficient * power`
This equation quickly becomes convoluted with modifying talents to either total damage or coefficient.  
See https://web.archive.org/web/20100807225410/http://elitistjerks.com/f80/t37900-dots_you_affliction_warlock_thread/, search for "DPS and DPCT spell by spell".  
A break from this happened with DKs; their diseases' damage is only based on Attack Power. Continuing on this idea every spell for all classes will be changed to remove the base component and all talents modifying spells on total damage % will be changed to modify the coefficient instead.

This stems from a pet peeve of mine; I play Affliction Warlock very well, so well that I usually end up dominating damage done in T7 and T8. Some warlocks are not as talented, and I've seen a lot of them out there. Neither do they seem to even *want* to git gud and when you try to point out that they are playing the strongest spec in T7 wrong (i.e. they are literally at the bottom of the meters), the usually reply is "Ye?! well you just outgear me!!"  
Bitch, I'm doing 4 times your damage yet I don't have 4 times your gear, not even 2 times your spell power, you just suck.  
If all things were equal between two players, except having twice the power as the other guy, you still won't do twice his damage because of the base component to spells.

# Items
You will only be able to equip 1 (ONE) trinket, I want this slot to be the highly discussed slot what to bring, you're going to have to make a hard choice.  

Secondary weapons/relics/tomes/totems will be removed; I'm more in favour of class specific trinkets.
Casters won't have Wands, Warriors won't be able to equip bows and Hunters won't have melee weapons, and so forth.
Wands were crutches around badly designed gameplay and are never used for anything in WotlK except level 5-29(ish) leveling, they are boring stat sticks!

## Trinkets
10sec/45cooldown on spell cast chance trinkets are all over the place in Wotlk, as a caster I have 4 procs to watch for (2 trinkets, tailoring cloak enchant and Eradication). I can't control when any of them happen, I can't line them up in any consistent meaningful way and I can't do much with them when it happens. Only on Drain Soul execute do I consider recasting when something procs.  

I want to create an npc which offers semi Reforging capabilities, for now only limited to trinkets such that the special effect can be tuned between random proc with cooldown, on use with cooldown or flat constant damage.  

Implemented as a priced quest rewarding something like this
https://imgur.com/a/414eID4  

Either this or removing DoT snapshotting.  

# Balance
Dps output will be balanced once all game mechanics have been finished.

# Raid Size and in General
The default raid size will be 30 people, 10 man will probably be scrapped.  
25 people was fine for TBC because class buffs were only group wide, so if a key support class wasn't there one day only 4 guys got shafted. With class buffs being raid wide losing a key support class is devastating, therefore the ideal raid comp needs to be balanced around having 2 of every support class for redundancy in case either player has something come up IRL, and it happens sometimes. Having only 25 raid members is very little room for this idea.  
On the flip side I want to reduce the number of support classes, or de-homogenize them; the support they bring is unique and can't be gained elsewhere, f.ex. only shadow priests will be a mana battery like in the good old days. https://www.dalaran-wow.com/forums/community/general-discussion/topic/2149/the-comprehensive-list-of-raid-buffs-debuffs none of this bullshit.  
I'm not a hardliner for the "hybrid tax", but some classes will not be designed with a pure competitive dps spec in mind.
