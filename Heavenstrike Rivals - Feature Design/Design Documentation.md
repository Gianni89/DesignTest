# Tactical Training Daily Feature

## Overview

> Greetings Captains!
> 
> The Tactical Training Daily Feature allows players to take charge of a squad of rare and powerful units! Players will be given control of 20 random high level units which they can use to make their own super squad. Choose your units carefully, as your squad will match up against other captains participating in Tactical Training. Will your squad building creativity trump all challengers? Win multiple matches with your squad to earn rewards.

The Tactical Training Feature is a new PvP mode for the game that players can participate in once per day. Players will be assigned a random selection of units that they can use to make a squad, challenge other players and win rewards. If a player loses a battle, or wins 5 battles, their participation for the day is over, and they no longer have access to the squad they created. 


## Purpose

The purpose of the Tactical Training daily feature is for players to try and build novel and creative squads out of a random set of powerful units, in a self contained environment where there is no penalty for "incorrect" choices.

This system has advantages for new and veteran players alike:

- For top level players
	+ Experimenting with unit synergy
	+ Challenging their ability to discover potential squad builds
	+ Using newly discovered squad builds to push the meta in league and arena
	+ Creates a top level gameplay that exists outside of the meta 
	
- For mid level players
	+ An additional way to earn currency
	+ An exposure to new units they may then chase
	+ An exposure to top level/promoted units they may already own, encouraging investment into leveling
	+ A taste of competitive squad building of high level play

- For newer players
	+ Able to see and experience a wide variety of units
	+ Opportunity to learn origin of units they like (e.g. purchaseable/recruitable)
	+ Able to have a feel for high level units
	+ Opportunity to try PvP with a sense of "even playing field"

## Feature Flow

- A new banner will be created to advertise the Tactical Training feature
- Interacting with the banner will take players to the feature location on the game map
	+ A new pin icon will be created for the feature
	+ Interacting with the pin will open the feature [dialogue](#dialogue-windows)
- The dialogue will provide a brief summary of the feature
	+ It will show the potential [rewards](#rewards)
	+ It will also show the [cost](#cost)
- If players participate they will be taken through the recruitment animation
	+ A random selection of units will be [generated](#unit-generation)
	+ After revealing the units, players are taken to the squad selection screen
- The squad selection screen features a "Ready!" button
	+ Clicking the button will prompt a [dialogue window](#dialogue-windows)
	+ This will ask the player if they are ready to enter combat

### Combat Flow

- If players are defeated a defeated [dialogue window](#dialogue-windows) will appear
	+ Closing this window will return the player to the main game screen
	+ They are locked out of the feature for the remainder of the day
- If players win their battle the reward for that match is presented to them
	+ A [dialogue window](#dialogue-windows) will then appear
	+ The player is able to battle again or adjust their squad selection
- If a player wins 5 matches a victory [dialogue window](#dialogue-windows) will appear
	+ Closing this window will return the player to the main game screen
	+ They are locked out of the feature for the remainder of the day 


## Cost

PvP matches and missions cost tokens or charges which are automatically restored over time, or can be refilled by trading cores. A similar system wouldn't work for a feature that can only be participated in once per day. As such, a flat currency cost seems most viable with coins being a good candidate.

The cost of participation should not be a barrier for entry, even for newer players, but should also be a currency sink over time, given the feature is available daily. Given a weakest exchange of 250000 coins per core, 10000 coins daily cost feels sensible for the Tactical Training feature, keeping it perfectly viable to participate daily while maintaining f2p, but encouraging core purchasing for depleted coins and cores.


## Rewards

The reward structure should be comparable but not favourable to league and arena PvP.

Arena rewards players with units, coins and cores, while league offers sacred shields. As coins are the base cost of participation, sacred shields and cores are the best suited reward.

In league PvP, 10 sacred shields are awarded for a loss and 30 for a win, which will set the base reward for this feature. Finishing in the middle bracket of a players league group rewards between 3000-4500 sacred shields. Therefore a weekly maximum of 3500 sacred shields through Tactical Training, with a much lower average is appropriate.

In the "new features" forum [thread](http://heavenstrikerivalsforum.com/threads/new-features.147/) many players request additional ways to earn cores through regular gameplay. 

Tactical Training would be a good opportunity for this. Arena offers 1 core for 3 trophies and 2 cores for 8 trophies, and as such I have suggested 1 core for 4 wins and 2 cores for 5 wins. Assuming a 50% chance of winning a match this equates to roughly a 22% chance of gaining 1 core per week and an 11% chance of 2 cores per week from Tactical Training.

A proposed reward structure might then be:

| Wins | Sacred Shields | Cores |
| ---- | :------------: | ----: |
|  0   |       10       |   0   |
|  1   |       30       |   0   |
|  2   |       60       |   0   |
|  3   |      120       |   0   |
|  4   |      300       |   1   |
|  5   |      500       |   2   |

### Reward Sink

With an additional source of sacred shields and cores added to the game, it is worth looking at their sinks. 

Recruitment is a stable sink for cores, and the small inflation due to the Tactical Training feature should not disturb this. The inflation of sacred shields should also be small, but could however stand to be alleviated by making available additional units for purchase via sacred shields.

A tangential feature, requested by the community, is for captains to be customisable (through e.g. clothing, hats) which if developed could be purchasable for money or sacred shields.

## Unit Generation

Players that participate in the feature will be taken through the recruitment animation, where units are spawned into the courtyard for players to reveal. 

Players will be given a random selection of 20 units, from which they will be able to form their squad. The units should be max level, with max level unit skill.

The companion spreadsheet offers a prototype of this system. It will generate a random selection of units from the restricted database that has been constructed, detailing their class, race, unit skill and stats.

## Matchmaking

There are a few possible ways a matchmaking system might work; a suggested way would be to utilize a priority matchmaking system.

A simple version would try and match opponents with less than 3 wins together, and opponents with more than 3 wins together, relaxing the priority when there is a small player base. If there is also a bias towards matching people with for 4 wins against people with 3 wins, this in turn will reduce the total number of people achieving 5 wins. 

## Dialogue Windows

### Interacting with feature pin

Title - Daily Feature, Tactical Training

>Form a squad from a random selection of high level units and test you skills against other captains! Win a series of matches for better rewards.

### Clicking "Ready!" Inside Feature Squad Selection

Title - Daily Feature, Tactical Training

>You are about to begin Tactical Training combat! Ensure you are happy with your squad selection before proceeding, as defeat will lock this feature for the rest of the day. If you win a battle you will be able to make changes to your squad before beginning a new one.

### Winning a Battle

Title - Victory!

>Congratulations Captain! You have won (number) Tactical Training match(s)! You can make changes to your squad or face the next challenger!

### Wining 5 Battles

Title - Victory!

>Congratulations Captain! You have proven your worth and won 5 matches! Return tomorrow for a new squad and new challengers!

### Defeat In Battle

Title - Defeat

>Commiserations Captain! You were not victorious this time. Return tomorrow for a new squad and new challengers!
