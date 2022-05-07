# Lost Ark Daily Activity Farming

## Overview
Lost Ark honing materials are earned through a variety of in-game activites.
While these activities may be repeated each day, rewards are only given a set number of times.
The types of rewards are fixed, but the amount are stochastic due to RNG in the game.

This analysis is an attempt to quantify expected rewards for a few scenarios:
1. Daily Chaos Dungeons with Aura of Resonance
1. Daily Guardian Raids
1. Infinite grind Chaos Dungeons

Activity Details:
- Chaos Dungeons may be performed twice daily for peak rewards (w/ AoR)
- Following AoR runs, Chaos Dungeons may be repeated infinitely for smaller drop rewards, exchangable currencies, and XP cards
- Guardian Raids may be done twice per day for loot obtained once boss is defeated, failed attempts do not count against this limit

## Goals
Primary questions to be answered:
1. What is the expected return from daily Chaos Dungeons w/ AoR (normal and rested)
1. What is the expected return from daily Guardian Raids (normal and rested)
1. What is the expected return from infinite grind Chaos Dungeon runs

Secondary objectives:
- Determine if doing the third floor of infinite grind Chaos Dungeons is "worth it"
    - Some LA players recommend skipping the third floor is more time-efficient
- Determine if and by how much rewards differ depending on Chaos Dungeon and Guardian Raid "difficulty"
    - As gear score increases new "levels" of daily activities unlock.
    - Lower-level ones are "easier" following stat increases from gear upgrades.
    - Currently it is unclear whether a "harder" one (max unlocked) gives more rewards than an "easier" one.
    - Some LA players recommend doing CD infinite grind on the lowest level of the current tier.

## Methods
- Chaos Dungeons all solo, Guardian Raids with a team
- While CD-IG analysis is for "time efficiency" runs will not be timed due to varying clear speeds of different classes. Quantifying rewards by floor will provide a sufficient metric for determining whether doing floor 3 is "worth".

- Chaos Dungeons with Resonance
    - Clear each level to a reasonable degree (finish large packs after portal, not exhaustively)
    - Record total gains of honing materials from drops, bonus rewards, and disenchanted gear drops
    - Disenchant all dropped gear minus Tripod upgrade drops (these are relatively rare and shouldn't affect the outcomes much)

- CD-IG
    - Clear each level to a reasonable degree (finish large packs after portal, not exhaustively)
    - Record rewards after each floor 


## Data Recording
A data ingestion UI will be built to aid in recording data to reduce errors.
- [Link to repo](https://github.com/justinmooney/lost-ark-data-recorder)
- After an initial data gathering phase I found that sometimes I forgot to clear rewards from inventory prior to a run or record certain rewards.