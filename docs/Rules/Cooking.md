# Cooking

## Preparing a "Homecooked" Meal

**Tl;DR**

1. Meal Preparer declares they want to make a meal and the ingredients they want to use
2. DM determines DC of the preparation and the `Bonus Effect Type` based on the meal
3. Meal Preparer rolls a `Wisdom (Survival)` check for the meal preparation
4. DM describes the preparation outcome to all players, making clear the Quality (Appearance)
5. Consumers make a decision to eat the meal (optionally rolling to resist effects) and Bonus Effect is applied

### Meal Preparation

PCs can spend time during a short rest or other down-time to prepare a meal.  The amount of food produced, the time needed, the difficulty, the potential `Bonus Effect Type`, and the ingredients/equpiment required are handled on a per-preparation basis by the DM.  The PC does not need to be at home to prepare a meal in this way.  To prepare the meal, the Preparer can make a `preparationRoll` using a `Wisdom (Survival)` Check to prepare the meal.

### Meal Consumption

Once a meal is prepared in this way, a PC is able to eat the meal at the end of the Short Rest, immediately before they roll hit dice to recover health.  Before eating the prepared meal, PCs are able to perceive the food with their senses and get a idea of the quality.  They may use this knowledge to make a choice as to whether they will eat the meal or not. (In general, the consumer is **fully aware** whether eating the meal will cause them harm and they are not obligated to do so).

#### Consuming Harmful Meals

If the PC willingly chooses to consume a prepared meal that will cause them harm, they can make a `DC 15 - preparationRoll` CON Saving Throw to resist the harmful effects. 

> For example: on a preparation roll of `5`,  the CON Saving Throw to resist the effect is `15-5` = `10 CON` Save

#### Meal Bonus Effects

Eating a prepared meal grants one of the following bonuses based on the type of meal created.  The bonus is determined by the value of a Survival Check relative to the DC (determined by difficulty) of the meal.  For example, when making a meal that has a difficulty of `DC 10`  and the PC rolls a `14`, then the row for `0-4 over DC` determines the bonus.

| Bonus Effect Type         | Occurence | Effect                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| ------------------------- | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Short Rest Hit Dice Bonus | Common    | Eating during a short rest grants a bonus to each hit dice rolled                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| Temporary HP              | Common    | Gain temporary HP based on the roll                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Inspiration               | Uncommon  | Gain Inspiration (or Disadvantage on next attacks) for the duration.  PC can expend Inspiration to add 1 die of the specified type to an Attack Roll, Saving Throw, or Ability Check of their choice (once).                                                                                                                                                                                                                                                                                                                                                         |
| Skill Check Bonus         | Rare      | Gain a bonus to a specific Skill Check for the duration.  Preparer needs to specifically be attempting to create a meal with this bonus and they are aware of the difficulty in creating a cullinary masterpiece of this caliber.  The DC should be considerably higher and the meal will require ingredients that are fitting for the desired Skill (ex: a bonus to Perception may require ingredients like Cat Eyes) |

### Meal Bonus Effect Table

| Check relative to DC | Quality      | Short Rest Hit Dice Bonus | Temp HP             | Inspiration           | Skill Check Bonus |
| -------------------- | ------------ | ------------------------- | ------------------- | --------------------- | ----------------- |
| 10+ over DC          | Perfect      | +3                        | `5 + roll - DC`     | `1d8`, 1h             | +4, 2h            |
| 5-9 over DC          | High quality | +2                        | `5 + roll - DC`     | `1d6`, 30m            | +3, 1h            |
| 0-4 over DC          | Decent       | +1                        | `5 + roll - DC` tHP | `1d4`, 30m            | +2, 30m           |
| 1-4 under DC         | Flawed       | no effect                 | no effect           | no effect             | no effect         |
| 5-9 under DC         | Concerning   | -1                        | `roll - DC` dmg     | Disadv on next atk    | -1 Save, 30m      |
| 10+ under DC         | Rancid       | -2                        | `roll - DC` dmg     | Disadv on next 2 atks | -2 Save. 1h       |

## Examples

| Meal DC | Preparation Roll | Quality    | Bonus Effect Type         | Outcome             |
| ------- | ---------------- | ---------- | ------------------------- | ------------------- |
| 10      | 14               | Decent     | Short Rest Hit Dice Bonus | `+1`                |
| 10      | 14               | Decent     | Temporary HP              | `5+14-10` = `9 tHP` |
| 10      | 5                | Concerning | Temporary HP              | `5-10` = `2 dmg`    |
| 10      | 14               | Decent     | Inspiration               | `1d4` for `30m`     |
| 10      | 14               | Decent     | Skill Check Bonus         | `+2` for `30m`      |
