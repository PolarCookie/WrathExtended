# WrathExtended
Patch 3.4 and onwards, a thought experiment what could have been.  
Code is here https://github.com/PolarCookie/TrinityCore/tree/3.4.0+

# Patch 3.4
## Classes
### Warlock
+ **Pandemic** now applies crit ability to Curse of Agony, Drain Life and Drain Soul, applies crit buff to Seed of Corruption
> CoA, Drain Life and Drain Soul not critting is an asymmetry which severly hurts crit rating for affliction warlocks, where crit/spirit gear becomes garbage to be avoided. Same with the crit multiplier not being present on SoC.

+ **Seed of Corruption** now is a single target AoE DoT.
> I personally find the 3.3.5 SoC to be incredibly boring, all you do is spam or spam-tab and pray tanks can hold agro. It doesn't synergise nicely with anything in the warlock arsenal, except Shadowflame if you want to trigger them. It is a massive break from the usuall affliction rotation of managing DoTs and debuffs. It belongs to a spec designed around building up damage potential which is later triggered, not affliction which ramps up steady non-burst damage. This new version is a mirror to regular Corruption except that the damage is AoE. The envisioned AoE rotation will be SoC, run towards the enemies while spreading regular Corruption, Shadowflame (which will now trigger Everlasting Affliction) and then tab casting SB/haunt to keep up all dots.
+ **Glyph of Quick Decay** now affects Seed of Corruption.
+ **Everlasting Affliction** now refreshes Seed of Corruption and can be triggered by Shadowflame.
> Shadowflame triggering Everlasting Affliction is something I wish I had in many cases. Affliction AoE has been limited to either SoC, boring as previously mentioned, or tab casting Corruption on all targets which is a slow, tedious and difficult task to get right. No other class has any AoE rotation as intricate as affli multidotting on 4+ targets.
+ **Shadow Bite** is an On-Next-Auto-Attack type spell, like Heroic Strike.
> This is in preperation for later pet changes where all pets will get 100% haste, crit, penetration, hit/expertise ratings from their masters. It is not neccesary that Felhunter should do a physical melee attack, and it's asymmetrical as the melee attack suffers from armor and glancing blows.

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
A break from this happened with DKs; their diseases damage is only based on Attack Power. Continuing on this idea every spell for all classes will be changed to remove the base component and all talents modifying spells on total damage % will be changed to modify the coefficient instead.

This stems from a pet peeve of mine; I play Affliction Warlock very well, so well that I usually end up dominating damage done in T7 and T8. Some warlocks are not as talented, and I've seen a lot of them out there. Neither do they seem to even *want* to git gud and when you try to point out that they are playing the strongest spec in T7 wrong (i.e. they are literally at the bottom of the meters), the usually reply is "Ye?! well you just outgear me!!"  
Bitch, I'm doing 4 times your damage yet I don't have 4 times your gear, not even 2 times your spell power, you just suck.  
If all things were equal between two players, except having twice the power as the other guy, you still won't do twice his damage because of the base component to spells.

# Balance
Dps output will be balanced once all game mechanics have been finished.
