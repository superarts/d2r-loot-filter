# Diablo II Resurrected Loot Filters

This repo contains modified versions of d2r filters. Go to the original websites to download original versions.

IMPORTANT: I decide to stop using this mods [because I don't feel safe](https://www.reddit.com/r/Diablo/comments/qt208l/if_you_are_using_a_loot_filter_it_may_not_be_as/). If you want to display text for full potions and disable clipped / flawed / normal gems text, please check out my ["end-game" branch](https://github.com/superarts/d2r-loot-filter/tree/end-game) in this repo, if you decide to take the risk.

If you like my input on this matter, please [consider donate some fg](#donation).

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
  - [My customization](#my-customization)
  - [givemhell](#givemhell)
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
- Create `mods\MOD_NAME` folders, e.g. `mods\givemhell`.
- Copy an `mpq` folder, e.g. `givemhell.mpq` to the folder you created above.

Now you should have some folder structures like `C:\Program Files (x86)\Diablo 2 Resurrected\mods\givemhell\givemhell.mpq` and a bunch of files inside it.

#### Geek?

- `cd 'C:/Program Files (x86)/Diablo 2 Resurrected'`
- `git clone git@github.com:superarts/d2r-loot-filter.git mods`

### Loading

- Go to Battle.net or Diablo 2 Resurrected launcher, go to D2R, and edit game settings (next to "Play" button).
- Add `-mod givemhell -txt` as "command line argument".

After launching the game, all your settings are reset, including options, custom key bindings etc.

## Mods

### My customization

Different Git branches are used to manage my customization. Since I just started working on these, everything is subjected to change.

- `master`: original mods
- `end-game`: less potions, gems are less obvious.

### givemhell

Original version: [NexusMods](https://www.nexusmods.com/diablo2resurrected/mods/102?tab=description)

## Contribute

Please raise PR and I'll review, comment, and merge.

## Donation

Please send `fg` to [superarts](https://forums.d2jsp.org/user.php?i=1258378), and leave a message if you want your ID to be listed in the "Special Thanks" section here.

## Special Thanks

### Modders

- [Psikrotic](https://www.nexusmods.com/diablo2resurrected/users/39479425)
