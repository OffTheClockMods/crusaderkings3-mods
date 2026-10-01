# Crusader Kings III Mods by Off the Clock

Source code of the Off the Clock mods for **Crusader Kings III**: Paradox script mods (game rules, no loader needed), PC.

## The mods

| Mod | What it does | Version | Download |
|---|---|---|---|
| **Cheaper Titles - Title Creation Cost Rule** (`Src/CheaperTitles`) | Cheaper titles for Crusader Kings III 1.20: creating duchies, kingdoms and empires costs up to 90% less, for you only or for every ruler, on the Game Rules screen. Or 50% more for a harder game. One new game rule, nothing else changed, so it survives updates. No DLC needed. | 1.0.0 | not released yet |
| **Domain Limit and Vassal Limit Rules** (`Src/DomainVassalLimit`) | Domain limit mod for Crusader Kings III 1.20: raise your domain limit and vassal limit from the Game Rules screen, from +2 up to +1000 (no practical limit), for you only or for every ruler. Two new game rules, nothing else changed: no events, no decisions, no vanilla files replaced, so it survives game updates. No DLC needed. | 1.0.0 | not released yet |
| **Faster Armies - Speed, Supply, Embarking** (`Src/FasterArmies`) | Army movement speed mod for Crusader Kings III 1.20: armies march up to three times faster, carry bigger supply limits and board ships for less gold (or free), for you only or for every ruler, on the Game Rules screen. Three new game rules, nothing else changed, so it survives updates. No DLC needed. | 1.0.0 | not released yet |
| **Faster Construction and Cheaper Buildings** (`Src/FasterConstruction`) | Faster construction for Crusader Kings III 1.20: buildings, new holdings and estate buildings finish up to 90% sooner and cost up to 90% less, for you only or for every ruler. Two new rules on the Game Rules screen, nothing else changed: no events, no building files replaced, so it works with building mods and survives game updates. No DLC needed. | 1.0.0 | not released yet |
| **Faster County Control and Development** (`Src/CountyDevelopment`) | Faster county control for Crusader Kings III 1.20: conquered counties settle in months instead of years, and development grows up to six times faster in your domain, for you only or for every ruler, on the Game Rules screen. Two new game rules, nothing else changed, so it survives updates. No DLC needed. | 1.0.0 | not released yet |
| **Faster Travel - Travel Speed and Safety** (`Src/FasterTravel`) | Faster travel for Crusader Kings III 1.20: your character travels up to +500% faster to feasts, hunts, pilgrimages and tournaments, and the roads can be made safer, for you only or for every ruler. Two new rules on the Game Rules screen, nothing else changed: no events, no vanilla files replaced, so it survives game updates. Armies are not affected. No DLC needed. | 1.0.0 | not released yet |
| **Gold, Prestige and Piety Multipliers** (`Src/IncomeMultipliers`) | Gold multiplier for Crusader Kings III 1.20: choose your monthly gold income, prestige gain and piety gain from x0.5 (harder) to x10, for you only or for every ruler, on the Game Rules screen. No console, no cheat menu. Three new game rules, nothing else changed, so it survives game updates. No DLC needed. | 1.0.0 | not released yet |
| **Knight Limit and Men-at-Arms Rules** (`Src/KnightMAALimits`) | Knight limit mod for Crusader Kings III 1.20: field more knights, recruit more men-at-arms regiments and make regiments bigger, for you only or for every ruler, on the Game Rules screen. Three new game rules, no unit or building files replaced, so it works with men-at-arms mods and survives updates. No DLC needed. | 1.0.0 | not released yet |
| **Less Stress - Stress Gain and Loss Rules** (`Src/LessStress`) | Less stress for Crusader Kings III 1.20: gain up to 75% less stress and lose it up to five times faster, for you only or for every ruler, on the Game Rules screen. Or make stress harsher. Two new game rules, no trait or event files replaced, so it works with other mods and survives updates. No DLC needed. | 1.0.0 | not released yet |
| **Lifestyle XP Multiplier** (`Src/LifestyleXP`) | Lifestyle XP multiplier for Crusader Kings III 1.20: choose how fast lifestyle experience comes, from x0.5 (slower) to x25, for you only or for every ruler, on the Game Rules screen. Faster perks without console commands or cheat traits. One new game rule, nothing else changed: no events, no vanilla files replaced, so it survives game updates. No DLC needed. | 1.0.0 | not released yet |
| **Longer Life and Better Health** (`Src/LongerLife`) | Longer life for Crusader Kings III 1.20: more health and a longer life expectancy for your ruler, for you only or for every ruler, on the Game Rules screen. Or a harsher -1 health. Two new game rules, nothing else changed, so it works with other mods and survives updates. No DLC needed. | 1.0.0 | not released yet |
| **Loyal Vassals - Vassal Opinion Rule** (`Src/LoyalVassals`) | Vassal opinion mod for Crusader Kings III 1.20: vassals like their liege up to +100 more, so factions and revolts get rarer, for your vassals only or for every liege, on the Game Rules screen. Or -20 for a harder game. One new game rule, nothing else changed, so it survives updates. No DLC needed. | 1.0.0 | not released yet |
| **More Children - Fertility Rule** (`Src/MoreChildren`) | Fertility mod for Crusader Kings III 1.20: have children more often (+10% to +100% fertility) or less often (-25%), for you only or for every character, on the Game Rules screen. One new game rule, no trait or event files replaced, so it works with other mods and survives updates. No DLC needed. | 1.0.0 | not released yet |
| **Short Reign Penalty and Tyranny Rules** (`Src/ShortReignTyranny`) | Short reign penalty mod for Crusader Kings III 1.20: the opinion penalty after a new ruler takes over ends up to 90% sooner, and harsh acts cause up to 90% less tyranny, for you only or for every ruler, on the Game Rules screen. Or make both harsher. Two new game rules, nothing else changed. No DLC needed. | 1.0.0 | not released yet |

Download the mods from the pages above. This repository is the source code, so you can see exactly what each mod does.

## Install and build

Nothing to compile: each mod is Paradox script (game rules, modifiers, localisation). Players should install from the
mod pages above. To run one from this source, copy `Src/<Mod>/` to
`Documents\Paradox Interactive\Crusader Kings III\mod\<Mod>\` and point a `<Mod>.mod` file next to it at that
folder (see `descriptor.mod`), then enable it in the launcher. Every setting is a game rule you pick when you start a
campaign; the defaults are the game's own values.

## What the mods do and don't do

- **Only what the mod page says.** Single player; nothing affects other players or online modes.
- **Settings at the game's own values by default**, with wide ranges and a short note beside each setting.
- **Honest side effects**: each mod page and README says what it changes (saves, achievements, cheat flags).

## Bugs and ideas

Open an [issue](https://github.com/OffTheClockMods/crusaderkings3-mods/issues). Please include the mod and version, the game version, what you did and what happened, and
the log lines that mention the mod.

## Licence

[MIT](LICENSE). You may learn from, reuse and adapt this code; keep the copyright notice. A friendly request (not a
licence term): please don't re-upload our mods. Link to our pages instead, so players always get the current version.

Written with AI coding help (Claude). Every release passes our offline tests and an automated in-game check before
it is published; we also play-test the mods by hand.

Crusader Kings III is a trademark of its owner (Paradox Interactive). This project is not affiliated with or endorsed by them.
