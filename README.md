# Mudskip

This is a page consisting of my open source works, such as my (unfinished) ROM hack project(s) as well as several feature branches ported from those same projects for convinience.

***NONE OF MY WORKS WILL EVER BE USED FOR SALE OR PROFIT!***

# Table of Contents

- [Feature Branches](https://mudskipper13.github.io/#feature-branches)
  - [pokeemerald](https://mudskipper13.github.io/#pokeemerald)
    - [Outfit System](https://mudskipper13.github.io/#outfit-system)
    - [Custom Shop UI](https://mudskipper13.github.io/#custom-shop-ui)
  - [pokeemerald-expansion](https://mudskipper13.github.io/#pokeemerald-expansion)
    - [Outfit System: RHH Version](https://mudskipper13.github.io/#outfit-system-rhh-version)
    - [Custom Shop UI: RHH Version](https://mudskipper13.github.io/#custom-shop-ui-rhh-version)
- Others
  - Assets
    - Dark-mode Shop Menu (+ Scrolling BG)
    - RSE-style custom Kanto NPC sprites
- Personal projects
  - Pokémon FireFlower / SuperLeaf (In-development)
  - Pokémon Reddish / Greeny (On hiatus)

# Feature Branches

## pokeemerald

### Outfit System

Link: https://github.com/mudskipper13/pokeemerald/tree/outfits

Inspired by Slawter's Costume System, I've made my own spin on Outfit System. Aims to be simple to use, guide for adding new Outfits is in progress. Other feature included:

- A whole interface for changing outfit, accessible by item but can also be made to be accessible somewhere else.
- New macros for checking if the player owns / wears a certain Outfit, unlocking / locking Outfits, as well as a pokemart macro for selling Outfits.

### Custom Shop UI

Link: https://github.com/mudskipper13/pokeemerald/tree/feature/new-shop-ui

A completely new interface for the Shop UI with plenty of customizations. Features included:

- Show mugshot of the shop seller/owner depending on the owner's Object Event Graphics ID.
  - Each sellers can also have its own texture for the interface.
- Gen 7+ Premier Balls gift implemented.
- Support for Outfit System. Make sure to uncomment `#include "outfit_menu.h"` in `src/new_shop.c`, which is the file of this new interface lives in.

## pokeemerald-expansion

### _NOTE: These branches are identical to their pokeemerald counterparts, except that they have extra codes for compatibility with pokeemerald-expansion._

### Outfit System: RHH Version

Link: https://github.com/mudskipper13/pokeemerald/tree/outfits-rhh

### Custom Shop UI: RHH Version

Link: https://github.com/mudskipper13/pokeemerald/tree/feature/new-shop-ui-rhh



