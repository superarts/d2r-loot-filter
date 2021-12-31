# Diablo II Resurrected Loot Filters

While [I don't feel very safe](https://www.reddit.com/r/Diablo/comments/qt208l/if_you_are_using_a_loot_filter_it_may_not_be_as/) using these mods, Blizzard doesn't seem to care about these QOL changes at all. So I'm making my own mod, with minimum changes to minimize the risk.

If you like my work, please [consider donate some fg](#donation).

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Contents

- [To be or not to be?](#to-be-or-not-to-be)
  - [Why you want to use it](#why-you-want-to-use-it)
  - [Why you don't want to use it](#why-you-dont-want-to-use-it)
- [How to install / load a mod](#how-to-install--load-a-mod)
  - [Installation](#installation)
    - [Geek?](#geek)
  - [Loading](#loading)
- [Mods](#mods)
  - [My loot filter](#my-loot-filter)
  - [My customization (deprecated)](#my-customization-deprecated)
  - [AlexisEvo/d2r-loot-filter](#alexisevod2r-loot-filter)
  - [SeonEngineer](#seonengineer)
- [Contribute](#contribute)
- [Donation](#donation)
- [Special Thanks](#special-thanks)
  - [Modders](#modders)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## To be or not to be?

**IMPORTANT: using a loot filter MAY get your account BANNED by Blizzard!**

### Why you want to use it

- According to some [discussion](https://www.reddit.com/r/Diablo/comments/qedwxg/d2r_loot_filter_not_bannable/), Blizzard Korean community is more encouraged to use `mpq` based loot filters.
- MPQ based mods are officially supported, and it uses Blizzard's own launcher. Battle.net doesn't reject the MPQ we are loading.
- No memory detection and injection are used, everything is visual change.
- The official loot display is terrible.

### Why you don't want to use it

- Loot filter in D2R in theory could allow you to click faster than players who don't use it, which puts you in an advanced situation.
- It's Blizzard. They always ban players. I got my Diablo 3 account banned for a stupid hellfire amulet exploit that I just tried for 5 minutes which literally hurt nobody at all. If you play their games, you are always at risk.
- If you live in China, you don't say bad things about Xi Jinping; if you play Blizzard's games, you don't mod your game. It's the same idea.

## How to install / load a mod

### Installation

- Clone this repo, or download as zip & extract it.
- Go to your d2r folder (try to find `Diablo 2 Resurrected` under a default location, `C:\Program Files\` or `C:\Program Files (x86)`).
- Create `mods\MOD_NAME` folders, e.g. `mods\superarts`.
- Copy an `mpq` folder, e.g. `superarts.mpq` to the folder you created above.

Now you should have some folder structures like `C:\Program Files (x86)\Diablo 2 Resurrected\mods\superarts\superarts.mpq` and a bunch of files inside it.

#### Geek?

- `cd 'C:/Program Files (x86)/Diablo 2 Resurrected'`
- `git clone git@github.com:superarts/d2r-loot-filter.git mods`

### Loading

- Go to Battle.net or Diablo 2 Resurrected launcher, go to D2R, and edit game settings (next to "Play" button).
- Add `-mod superarts -txt` as "command line argument".

After launching the game, all your settings are reset, including options, custom key bindings etc.

## Mods

### My loot filter

WIP: `superarts` loot filter

Goals:

- Only minimum changes to things I absolutely hate
- Less changes, less risk to get banned (although probably it wouldn't really matter)
- Include price guide

### My customization (deprecated and removed)

*I was planning to branch other's loot filters, but realized that I just want bare minimum changes myself so stopped using this approach. See section above for my personal filter.*

~~Different Git branches are used to manage my customization. Since I just started working on these, everything is subjected to change.~~

~~- `master`: original mods~~
~~- `end-game`: less potions, gems are less obvious.~~

### AlexisEvo/d2r-loot-filter

[Github link](https://github.com/AlexisEvo/d2r-loot-filter)

### SeonEngineer

[Github link](https://github.com/SeonEngineer/D2R)

## Contribute

Please raise PR and I'll review, comment, and merge.

## Donation

Please send `fg` to [superarts](https://forums.d2jsp.org/user.php?i=1258378), and leave a message if you want your ID to be listed in the "Special Thanks" section here.

## Special Thanks

- Thank you [meilk](https://forums.d2jsp.org/pm.php?c=3&m=413611298) for your support!

### Modders

- [Psikrotic](https://www.nexusmods.com/diablo2resurrected/users/39479425)
- [AlexisEvo](https://github.com/AlexisEvo)
