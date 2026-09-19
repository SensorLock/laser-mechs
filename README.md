# Laser Mechs
**Laser Mechs** is inspired by Space Gits, but thematically styled on mech games with lasers and missiles.

> [!TIP]
> Laser Mechs is powered by Riot Dice, an open-source rules engine by Mike Hutchinson (https://planetsmashergames.com/riot-dice)._

## The Basics

### Models
Mechs are 6mm-scale armored robots piloted by a skilled warrior. They come in many sizes and armaments. The models should have a reasonable size base.

Models are defined by a set of Stats:
* **Size**: Small (size=1), medium (size=2), or large (size=3).
* **Cost**: The cost, in points, to add this model to your squad. All models cost 5*size points.
* **Move Dice**: Each model can roll up to 3d6 for movement.
* **Armor**: How many towers the mech has. Equal to the size value.

### Players
Players are referred to as Commanders. A model's commander is the player that is controlling them.

### Squads
The cost of a squad of mechs is the sum of the model costs.

Choose a point value for squad sizes. The standard game size is 30 points per player, but you can adjust that to match the number of models available or to increase the amount of chaos on the battlefield.

### Measuring
When measuring and checking lines between dice and models, you can measure from anywhere on the models' bases to anywhere on the dice. If it grazes either, it is in. You can premeasure during your activation.

## Heat
Each model has one or more personal dice tower of dice to represent the accumulated heat of movement and weapons. 

The number of towers for each model is initially equal to the armor value. They start with a single die, called the armor die, for each tower.

Some abilities will require a commander to put dice on a tower of their choosing, and some will require them to put dice on each tower attached to a mech.

When a model adds a dice to a tower, its commander adds a six-sided dice to this tower, placing it on top of the other dice in their tower to form a single stack of dice. 

The towers have to touch the model at all times. I.e. When you move a model, you have to move all their towers with them.

### Falling Dice
If any of the dice fall off a mech’s tower at any point, for any reason, that mech has shutdown. Lay the model down to represent this, and the dice from the towers are reset to just the armor dies for each tower.

If a commander causes one of their own towers to fall: that mech has shutdown. If that happens during a mech’s activation, their activation is over. 

If a commander causes anyone else’s tower to fall, through clumsiness or deliberate sabotage, that opposing mech had secret cooling tech: their tower dice are all reset to just armor dice, but they remain active.

If a rolled die causes a tower to fall, the commander that rolled that die has knocked that tower over. If a stray die from a tumbling tower causes another tower to fall, the commander that caused the initial cascade is the one that knocked that other tower over.

> [!WARNING]
> Don’t knock other player’s towers over. It's tactically unsound.

### Damage
When one of your models gets damaged, remove an armor dice and the tower above it.

If that was the last armor dice, the mech is destroyed.
If it has remaining armor dice, redistribute all the heat dice that were above the armor dice in that tower among the remaining towers.

## Weapons
Weapons are either Shooting, and used during Shoot Actions, or Melee, used during Fights.

### Shooting Weapons
Shooting Weapons have the following stats:

* **Range**: The maximum distance a bullet from this weapon will travel.
* **Bullet Dice**: The dice rolled when shooting with this weapon.
* **Weak/Big Damage**: The damage values that apply when this weapon hits another model.

### Fighting Weapons

Fighting Weapons have the following stats:

* **Thump Dice**: The dice rolled when thumping with this weapon.
* **Weak/Big Damage**: The damage values that apply when thumping another model with this weapon.

> [!TODO]
> Weapons table. Integrate into cost structure of squad.

## Set Up

### Table
Clear a play area roughly 3-foot by 3-foot and set up plenty of terrain. 

> [!TIP]
> _The table setup is something that you can freely experiment with, and potentially you wlil want to vary from scenario to scenario._

### Salvage
Each commander drops 6 Salvage Tokens onto the table from a decent height. 

Put one more Salvage Token in the middle as a tie-breaker. 

### Deployment
Randomly determine a First Player.

Starting with the First Player, take turns to place one model at a time anywhere in play, at least 4” from all Salvage Tokens and enemy models.

The First Player activates the first model.

### Start the Clock
Once all the models are deployed, start a timer for 30 minutes and start the game. 

## Activating Models
Take turns activating one model each, starting from the First Player.

There are no game rounds, just keep activating models until time is up or only force remains on the field of battle.

When it is your turn to activate a model, you choose one of your models and activate it.

When you activate a model, they do one or two different actions out of: Restart, Run, Shoot, Fire, or Steal. Shutdown models must Restart as their first action and can not Shoot.

You don’t have to activate your models in rounds, if you want to keep activating the same model turn after turn: that is allowed.

## Restart
Turn the mech off, then on again. Stand the model up. Somehow, this procedure discharges all the heat.

When a model stands up, put it anywhere at least touching the area where they were just lying. If you place them into contact with an enemy, the current activation ends and a fight breaks out.

The commander should double-check the armor dice are in place where they want and touching the base of the model.

## Run Action
When a model takes a Run Action, roll their Move Dice into the play area.

Resolve one or more Move Die at a time in any order.

When you resolve a Move Die you move your model directly towards that dice a number of inches equal to the value of that dice and then discard it. 

You have to move the model the full distance towards the Move Die if you can.

You do not have to use all your move dice, and can discard any of your Move Dice without resolving them.

As you move the model, make sure every tower of dice is touching them at all times. If any of the dice fall, the model has shutdown. (See "Heat".)

All mechs can resolve one move dice without adding Heat, but for each dice beyond the first resolved, add a number of heat dice to the model equal to the size of the model. This is done after resolving all dice in the Run action, and the commander can choose how to distribute those among the towers on that model.

> [!WARNING]
> That big mech can go zipping around the battlefield, but it's going to get very hot, very fast.

## Salvaging
Each commander has a collection of Salvage Tokens, called their Stash.

If you bump into a Salvage Token while moving, you stop moving and pick it up.

Salvage Tokens that you pick up go into your Stash.

## Shoot Action
> [!TODO]
> Lasers: high damage chance, directional, heat to all towers
> Missiles: scatter hits, heat to one tower
When a model takes a Shoot Action, it selects one of its shooting weapons and gathers a number and type of bullet dice indicated by the shooting weapon's stats.

Roll your bullet dice into the play area. 

Each bullet travels from the shooting model in a straight line directly towards one of the bullet dice a number of inches equal to the gun’s range, hitting the first thing in its path (ignoring dice and fallen models). 

If the thing that is hit is a model, compare the value of the bullet dice to the toughness of that model. If the rolled value meets or beats the toughness, the unlucky model suffers big damage from the gun. If the value is lower than the model’s toughness, they suffer weak damage.

## Fighting
> [!TODO]
> big damage removes a tower
If two opposing models end up in contact, the current activation ends and a fight breaks out.

When two models fight, their commanderes count 3, 2, 1… and then throw one of either 👊 Thump, 🖐️ Shove or 🤏 Pinch with their hands.

The active model resolves their effect first, then the passive model does. If it isn’t clear who the active model is, it is the model who’s movement (or who’s standing up) caused the fight to break out.

Once the throw is resolved, if the two models are still in contact (and both are still standing) they fight again, and continue to do so until they are separated or one falls.

### Thump
👊 Thump is a fist (like "rock" or "stone"). 

If a commander throws 👊 Thump, their model Thumps the other model, unless the other commander threw 🖐️ Shove.

To Thump: roll all your fighting weapons’ thump dice. Do big damage with each dice that equals or beats the other model’s toughness, and weak damage with the others.

### Shove
🖐️ Shove is a flat hand (like "paper").

If a commander throws 🖐️ shove, the other model is pushed back 3”, unless their commander threw 🤏 Pinch. 

The shoved model is moved by its commander, along with their tower. 

The shoved model is moved directly away from their opponent. 

If the shoved model is shoved into some terrain, they suffer 1 damage.

### Pinch
🤏 Pinch is the thumb and index finger extended and held together (like an "OK" sign, or "scissors" but using your thumb).

If a commander throws 🤏 Pinch, they take 1 Loot Token from the other model’s commander, unless the other commander throws 👊 thump.

> [!TIP]
> _When both commanderes throw Pinch, as they just swap a cap and nothing happens. This is a place that needs improvement, but I haven't improved it yet._

## Steal Action
If a model is in contact with a fallen enemy model, they can take a Steal Action to rip valuable tech off their mech. They take 1 Salvage Token from the fallen model’s commander.


## Call for Extraction
When it is your turn to activate, you can call for extraction instead.

When it is your turn to activate, if you have nothing left that you can activate, you have to extract.

When you extract: any of your models that are within 6” of an enemy model are replaced with a Salvage Token from your stash, then remove the rest of your models and you are out of the game.

## Game End & Victory
When the 30 minute timer is up, every commander gets one more activation.
Models can no longer take Restart Actions. (That means that overheated mechs stay shutdown).

The game also ends if only one commander still has mechs on the field of battle. 

At the end of the game, if there is only one remaining commander, they get to scoop up any in-play Tech Caches. 

The winner is the commander that captured the most Tech Caches.
