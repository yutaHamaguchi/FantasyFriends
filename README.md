## Fantasy Friends

### Game Design Document (GDD)

## Game Overview

### Target Platform
Android, iOS

### Business Model
Free-to-play (In-app purchases available)

## Game Summary

### Theme / Setting / Genre
"Fantasy Friends" is a realistic and visually stunning Tower Defense RPG developed using Unity. Players embark on a journey across the world with their pets, defending against attacks from enemy monsters. The game incorporates the FFXII Gambit Combat System to enhance the strategic gameplay.

### Target Users
The game is designed to cater to disabled individuals, providing them with an enjoyable and accessible action RPG experience. The implementation of the Gambit Combat System allows players to arrange actions at their own pace without the need to rush, making the game more inclusive and enjoyable for all players.

## Core Gameplay Mechanics

- Players control pets to attack enemies, rather than directly attacking themselves.
- Pets have multiple types, such as Attackers, Tanks, Ranged Attackers, and Utilities, each with distinct roles.
- Players can raise and utilize up to 5 pets simultaneously, starting with one pet at the beginning.
- Pets have levels, with a maximum level of 30. Players can strengthen and enhance their pets as they progress.
- Players possess skills, buffs, and debuffs to strengthen their pets and weaken enemies.

## Gambit Combat System

The game will feature the Gambit Combat System inspired by the FFXII Gambit System, as detailed in the blog post by [Immersive Nick](https://immersivenick.wordpress.com/2019/03/31/programming-the-ffxii-gambit-system/). This system allows players to set up pre-defined action patterns for their pets, adding depth and strategy to the gameplay. Players can create a series of conditions and corresponding actions for their pets, which will be executed automatically during battles. The Gambit Combat System will enable players to fine-tune their pets' behavior and develop personalized combat strategies.

## Online / Server Mechanics
The game will include a leaderboard feature using PlayFab basic functions. Players can compete for high scores and see how they rank compared to others in the game.

## Story and Gameplay

### Story
The game is set in a fantasy world where magic exists. The world is threatened by the invasion of evil monsters. Players encounter special places called "Fantasy Friends," where they meet pets with magical abilities. Together, they embark on a journey to counter the evil monsters and save the world through their adventures.

### Gameplay
Players select a pet and set off on their adventure, starting with one pet.
Pets automatically attack enemy monsters, while players control their actions.
Players can edit Gambit commands to set automatic actions for their pets and determine battle tactics.
Pets possess different types of skills and take actions according to their roles.
Players can level up their pets, allowing them to acquire new skills.
Victorious battles reward players with money and items, which can be used to strengthen pets and acquire new ones.

## User Interface / Screens

### Main Menu
Contains options for game startup, saving, loading, etc.

### Gameplay Screen
The primary screen where pets embark on adventures.

### Premium Currency Store
A store screen for purchasing premium currency through in-app purchases.

### Coin Store
A store screen for purchasing in-game currency, coins, through in-app purchases.

### Equipment Shop
A shop screen for purchasing new equipment and enhancing pet gear using in-game currency or premium currency.

### Settings Popup
A popup menu for changing game settings and adjusting volume.

### Daily Reward Popup
A popup menu for receiving and checking daily rewards.

### Game Over Screen
Displayed when the player fails in the game.

## Level

### Level Design
Each level features different enemy monsters and battlefields.
Players clear levels to receive rewards, progress the story, and face increasing difficulties that require strategic planning and pet enhancements.

### First Time Experience
New players can receive tutorials to learn basic rules and controls of the game.

## Economy

### In-Game Currency
There are two types of in-game currency: coins and premium currency.
Coins can be earned by clearing battles and completing missions.
Premium currency can be acquired through in-app purchases.

## Additional Asset Integration

The game will also integrate the "Action-RPG Starter Kit" from the Unity Asset Store, enhancing the gameplay and providing additional features and mechanics to enrich the player experience.

The above is the Game Design Document for "Fantasy Friends." Based on this overview, we will develop a realistic and visually stunning Tower Defense RPG using Unity that immerses players in a world of adventure and magic while incorporating the FFXII Gambit Combat System. The game aims to be inclusive and accessible to disabled players, allowing them to enjoy the action RPG experience at their own pace.


## gambit system commands


| target | command                        | action     | 
| ------ | ------------------------------ | ---------- | 
| Foe:   | party leader's target          | attack     | 
| Foe:   | not targeted by ally           | cast heal  | 
| Foe:   | targeting Vaan                 | defence    | 
| Foe:   | targeting Basch                | use potion | 
| Foe:   | highest HP                     |            | 
| Foe:   | highest MP                     |            | 
| Foe:   | highest level                  |            | 
| Foe:   | highest magick power           |            | 
| Foe:   | highest defense                |            | 
| Foe:   | HP > 10,000                    |            | 
| Foe:   | HP >1,000                      |            | 
| Foe:   | HP < 10,000                    |            | 
| Foe:   | HP < 1,000                     |            | 
| Foe:   | HP =70%                        |            | 
| Foe:   | status = Petrify               |            | 
| Foe:   | status = Doom                  |            | 
| Foe:   | status = Sap                   |            | 
| Foe:   | status = Immobilize            |            | 
| Foe:   | status = Shell                 |            | 
| Foe:   | status = Reflect               |            | 
| Foe:   | fire-weak                      |            | 
| Foe:   | water-weak                     |            | 
| Foe:   | fire-vulnerable                |            | 
| Foe:   | water-vulnerable               |            | 
| Foe:   | undead                         |            | 
| Foe:   | character status = Bravery     |            | 
| Foe:   | Character HP > 90%             |            | 
| Foe:   | Character HP > 10%             |            | 
| Foe:   | Character MP < 30%             |            | 
| Foe:   | Character HP > 50%             |            | 
| Foe:   | 3+ foes present                |            | 
| Foe:   | 3+ allies present              |            | 
| Foe:   | HP <50%                        |            | 
| Foe:   | Character HP <70%              |            | 
| Foe:   | nearest visible                |            | 
| Foe:   | targeting leader               |            | 
| Foe:   | targeting Ashe                 |            | 
| Foe:   | targeting Penelo               |            | 
| Foe:   | lowest HP                      |            | 
| Foe:   | lowest MP                      |            | 
| Foe:   | lowest level                   |            | 
| Foe:   | lowest magick power            |            | 
| Foe:   | highest magick resist          |            | 
| Foe:   | HP >5,000                      |            | 
| Foe:   | HP > 500                       |            | 
| Foe:   | HP < 5,000                     |            | 
| Foe:   | HP < 500                       |            | 
| Foe:   | HP =50%                        |            | 
| Foe:   | status = Stop                  |            | 
| Foe:   | status = Blind                 |            | 
| Foe:   | status = Oil                   |            | 
| Foe:   | status = Slow                  |            | 
| Foe:   | status = Haste                 |            | 
| Foe:   | status = Regen                 |            | 
| Foe:   | lightning weak                 |            | 
| Foe:   | wind-weak                      |            | 
| Foe:   | lightning-vulnerable           |            | 
| Foe:   | wind-vulnerable                |            | 
| Foe:   | flying                         |            | 
| Foe:   | character status = Faith       |            | 
| Foe:   | Character HP > 70%             |            | 
| Foe:   | Character MP < 90%             |            | 
| Foe:   | Character MP < 10%             |            | 
| Foe:   | Character HP > 30%             |            | 
| Foe:   | 4+ foes present                |            | 
| Foe:   | item AMT >10                   |            | 
| Foe:   | HP <30%                        |            | 
| Foe:   | Character HP <50%              |            | 
| Foe:   | any                            |            | 
| Foe:   | targeting self                 |            | 
| Foe:   | targeting Fran                 |            | 
| Foe:   | furthest                       |            | 
| Foe:   | highest max HP                 |            | 
| Foe:   | highest max MP                 |            | 
| Foe:   | highest strength               |            | 
| Foe:   | highest speed                  |            | 
| Foe:   | HP > 100,00                    |            | 
| Foe:   | HP >3,000                      |            | 
| Foe:   | HP <100,000                    |            | 
| Foe:   | HP < 3,000                     |            | 
| Foe:   | HP =100%                       |            | 
| Foe:   | HP =30%                        |            | 
| Foe:   | status = Sleep                 |            | 
| Foe:   | status = Poison                |            | 
| Foe:   | status = Reverse               |            | 
| Foe:   | status = Disease               |            | 
| Foe:   | status = Bravery               |            | 
| Foe:   | status = Berserk               |            | 
| Foe:   | ice-weak                       |            | 
| Foe:   | holy-weak                      |            | 
| Foe:   | ice-vulnerable                 |            | 
| Foe:   | holy-vulnerable                |            | 
| Foe:   | character status = Blind       |            | 
| Foe:   | character status = HP Critical |            | 
| Foe:   | Character HP > 50%             |            | 
| Foe:   | Character MP < 70%             |            | 
| Foe:   | Character HP > 90%             |            | 
| Foe:   | Character HP > 10%             |            | 
| Foe:   | 5+ foes present                |            | 
| Foe:   | HP <90%                        |            | 
| Foe:   | HP < 10%                       |            | 
| Foe:   | Character HP <30%              |            | 
| Foe:   | targeted by ally               |            | 
| Foe:   | targeting ally                 |            | 
| Foe:   | targeting Balthier             |            | 
| Foe:   | nearest                        |            | 
| Foe:   | lowest max HP                  |            | 
| Foe:   | lowest max MP                  |            | 
| Foe:   | lowest strength                |            | 
| Foe:   | lowest speed                   |            | 
| Foe:   | HP > 50,000                    |            | 
| Foe:   | HP > 2,000                     |            | 
| Foe:   | HP <50,000                     |            | 
| Foe:   | HP < 2,000                     |            | 
| Foe:   | HP =90%                        |            | 
| Foe:   | HP =10%                        |            | 
| Foe:   | status = Confuse               |            | 
| Foe:   | status = Silence               |            | 
| Foe:   | status = Disable               |            | 
| Foe:   | status = Protect               |            | 
| Foe:   | status = Faith                 |            | 
| Foe:   | status = HP Critical           |            | 
| Foe:   | earth-weak                     |            | 
| Foe:   | dark-weak                      |            | 
| Foe:   | earth-vulnerable               |            | 
| Foe:   | dark-vulnerable                |            | 
| Foe:   | character status = Silence     |            | 
| Foe:   | Character HP = 100%            |            | 
| Foe:   | Character HP > 30%             |            | 
| Foe:   | Character MP < 50%             |            | 
| Foe:   | Character HP > 70%             |            | 
| Foe:   | 2+ foes present                |            | 
| Foe:   | 2+ allies present              |            | 
| Foe:   | HP <70%                        |            | 
| Foe:   | Character HP <90%              |            | 
| Foe:   | Character HP <10%              |            | 
| Ally   | any                            |            | 
| Ally   | Fran                           |            | 
| Ally   | guest                          |            | 
| Ally   | lowest magick resist           |            | 
| Ally   | HP <70%                        |            | 
| Ally   | HP <30%                        |            | 
| Ally   | status = Stone                 |            | 
| Ally   | status = Confuse               |            | 
| Ally   | status = Silence               |            | 
| Ally   | status = Disable               |            | 
| Ally   | status = Lure                  |            | 
| Ally   | status = Bravery               |            | 
| Ally   | status = Regen                 |            | 
| Ally   | status = HP Critical           |            | 
| Ally   | 5+ foes present                |            | 
| Ally   | Ally MP <80%                   |            | 
| Ally   | Ally MP <40%                   |            | 
| Ally   | party leader                   |            | 
| Ally   | Balthier                       |            | 
| Ally   | lowest HP                      |            | 
| Ally   | HP <100%                       |            | 
| Ally   | HP <60%                        |            | 
| Ally   | HP <20%                        |            | 
| Ally   | status = Petrify               |            | 
| Ally   | status = Doom                  |            | 
| Ally   | status = Sap                   |            | 
| Ally   | status = Immobilize            |            | 
| Ally   | status = Protect               |            | 
| Ally   | status = Faith                 |            | 
| Ally   | status = Float                 |            | 
| Ally   | 2+ foes present                |            | 
| Ally   | item AMT >10                   |            | 
| Ally   | Ally MP <70%                   |            | 
| Ally   | Ally MP <30%                   |            | 
| Ally   | Vaan                           |            | 
| Ally   | Basch                          |            | 
| Ally   | strongest weapon               |            | 
| Ally   | HP <90%                        |            | 
| Ally   | HP < 50%                       |            | 
| Ally   | HP <10%                        |            | 
| Ally   | status = Stop                  |            | 
| Ally   | status = Blind                 |            | 
| Ally   | status = Oil                   |            | 
| Ally   | status = Slow                  |            | 
| Ally   | status = Shell                 |            | 
| Ally   | status = Reflect               |            | 
| Ally   | status= Berserk                |            | 
| Ally   | 3+ foes present                |            | 
| Ally   | Ally MP <100%                  |            | 
| Ally   | Ally MP <60%                   |            | 
| Ally   | Ally MP <20%                   |            | 
| Ally   | lowest defense                 |            | 
| Ally   | HP < 80%                       |            | 
| Ally   | HP < 40%                       |            | 
| Ally   | status = KO                    |            | 
| Ally   | status = Sleep                 |            | 
| Ally   | status = Poison                |            | 
| Ally   | status = Reverse               |            | 
| Ally   | status = Disease               |            | 
| Ally   | status = Haste                 |            | 
| Ally   | status = Invisible             |            | 
| Ally   | status = Bubble                |            | 
| Ally   | 4+ foes present                |            | 
| Ally   | Ally MP <90%                   |            | 
| Ally   | Ally MP <50%                   |            | 
| Ally   | Ally MP <10%                   |            | 
| Self : | Self Any                       |            | 
| Self : | HP <70%                        |            | 
| Self : | HP < 30%                       |            | 
| Self : | MP <90%                        |            | 
| Self : | MP<50%                         |            | 
| Self : | MP<10%                         |            | 
| Self : | status = Poison                |            | 
| Self : | status = Reverse               |            | 
| Self : | status = Lure                  |            | 
| Self : | status = Bravery               |            | 
| Self : | status = Regen                 |            | 
| Self : | 2+ foes present                |            | 
| Self : | targeted by foe                |            | 
| Self : | HP < 100%                      |            | 
| Self : | HP < 60%                       |            | 
| Self : | HP < 20%                       |            | 
| Self : | MP <80%                        |            | 
| Self : | MP<40%                         |            | 
| Self : | status = Petrify               |            | 
| Self : | status = Silence               |            | 
| Self : | status = Immobilize            |            | 
| Self : | status =Protect                |            | 
| Self : | status = Faith                 |            | 
| Self : | status = Float                 |            | 
| Self : | 3+ foes present                |            | 
| Self : | targeted by ally               |            | 
| Self : | HP <90%                        |            | 
| Self : | HP < 50%                       |            | 
| Self : | HP <10%                        |            | 
| Self : | MP<70%                         |            | 
| Self : | MP<30%                         |            | 
| Self : | status = Doom                  |            | 
| Self : | status = Sap                   |            | 
| Self : | status = Slow                  |            | 
| Self : | status = Shell                 |            | 
| Self : | status = Reflect               |            | 
| Self : | status = Bubble                |            | 
| Self : | 4+ foes present                |            | 
| Self : | item AMT > 10                  |            | 
| Self : | HP < 80%                       |            | 
| Self : | HP <40%                        |            | 
| Self : | MP <100%                       |            | 
| Self : | MP <60%                        |            | 
| Self : | MP<20%                         |            | 
| Self : | status = Blind                 |            | 
| Self : | status = Oil                   |            | 
| Self : | status = Disease               |            | 
| Self : | status = Haste                 |            | 
| Self : | status = Invisible             |            | 
| Self : | status = HP Critical           |            | 
| Self : | 5+ foes present                |            | 
