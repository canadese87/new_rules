# Saves

Many Saves in DC20 target one of a creature's 4 Attributes Saves (Might, Agility, Charisma, or Intelligence).

## **Attribute Saves**

When a creature is subjected to an effect, they make the an Attribute Save to determine whether or not they're able to resist the effect. The Attribute used to make the Save is determined by the effect (or the GM).

### Making an Attribute Save

The creature rolls a d20, adds its given Attribute, and adds its Combat Mastery. If the result of the Attribute Save is equal to or higher than the Contested Check, the Attribute Save is successful.

#### Attribute Save Formula

```
D20 + Attribute + Combat Mastery
```

> **Example (Might Save):** *A level 2 Barbarian that attempts to resist being pushed against their will would make a Might Save to prevent themselves from moving.Their Might is 3 and their Combat Mastery (1/2 level, rounded up) is 1, so their total bonus to the Save is a 4. They would roll a d20 and add* **4** *to their Might Save.* 

> **Example (Agility Save):** *A level 5 Rogue that attempts to jump to safety when the ground beneath their feet collapses would make an Agility Save to secure its footing on solid ground. Their Agility is 4 and their Combat Mastery (1/2 level, rounded up) is 3, so their total bonus to the Save is a 7. They would roll a d20 and add* **7** *to their Agility Save.*

> **Example (Charisma Save):** *A level 10 Bard that attempts to resist being mind controlled would make a Charisma Save to retain control over their own actions. Their Charisma is 5 and their Combat Mastery (1/2 level, rounded up) is 5, so their total bonus to the Save is a 10. They would roll a d20 and add* **10** *to their Charisma Save.*

> **Example (Intelligence Save):** *A level 16 Wizard that attempts to break free of illusions that grip their senses would make an Intelligence Save to discern what's real and what isn't. Their Intelligence is 6 and their Combat Mastery (1/2 level, rounded up) is 8, so their total bonus to the Save is a 14. They would roll a d20 and add* **14** *to their Intelligence Save.*


### **Special Saves**

#### Death Saves

When a creature makes a Death Save, it rolls a d20. If the result is 10 or higher it succeeds on its Death Save. See ["Death's Door" on page 35](#page-34-1) for more information on Death Saves.

#### Save Categories

Some Saves are organized into categories, such as Physical Saves, Mental Saves, and Death Saves.

**Physical Saves**: When an effect targets your overall physical abilities, you make a Physical Save. Your Physical Save bonus is equal to your Might Save bonus or Agility Save bonus, whichever is higher.

> **Example:** *A creature that attempts to resist gaining*  **Exhaustion** *from a Spell that withers its body would make a Physical Save to avoid suffering any effects.*

**Mental Saves**: When an effect targets your overall mental abilities, you make a Mental Save. Your Mental Save bonus is equal to your Charisma Save bonus or Intelligence Save bonus, whichever is higher.

> **Example:** *A creature that attempts to resist being teleported against its will would make a Mental Save to remain in the same location.*

### **Save DC**

Your Save DC represents the difficulty a creature would have to resist your static effects (such as Traps) and ongoing effects (such as Spells). Every creature has a Save DC, which is equal to 10 + its Prime Modifier + its Combat Mastery.

#### Save DC Formula

```
10 + Prime Modifier + Combat Mastery
```

**Repeated Saves**: When a creature fails a Save against an effect that has the Repeated Save statement, it can repeat its Save at the end of each of its turns. When that happens, the creature repeats its Save against a Save DC (instead of the original opposing Check).

> **Example:** *A Giant Snake targets a Barbarian with a Melee Attack that causes the target to become* **Restrained***. The Giant Snake makes an Attack Check that's Contested by the Barbarian's Physical Save. If the Barbarian fails its Save against the effect it becomes* **Restrained***. However, the Barbarian can repeat its Save at the end of each of its turns to free itself from being* **Restrained***. When it repeats its Save it does so against the Giant Snake's* **Save DC***.*

## Dynamic Attack Saves

Some game features (such as a Maneuvers, Techniques, Spells, etc.) both deal damage and impose an effect on its target. This triggers what is called a Dynamic Attack Save.

The provoking creature makes an Attack Check (or Spell Check) at the same time that the target makes its Save. The provoking creature's Check is compared against the target's Defense to determine if the target takes damage, and the target's Save is compared against the provoking creature's Save DC to determine if the target is subjected to the effect.

#### Dynamic Attack Save Outcomes

A Dynamic Attack Save can result in 1 of 4 outcomes:

- **Attack Hit & Save Failure:** The target takes damage and is subjected to the effect.
- **Attack Miss & Save Failure:** The target does not take damage but is subjected to the effect.
- **Attack Hit & Save Success:** The target takes damage but is not subjected to the effect.
- **Attack Miss & Save Success:** The target does not take damage and is not subjected to the effect.

> **DC Tip:** *There are many game features that both deal damage and impose an effect on its target. When this happens, an Attack Check or Spell Check is ALWAYS made to determine DAMAGE while a Save is ALWAYS made against the EFFECT. This opens up many very interesting interactions on what the outcome will be and keeps things moving quickly because both the Attacker and the Target make these rolls at the same time (similar to how Contested Checks work). With Dynamic Attack Saves, you don't have to wait for the Attack Check to hit, then have the target make a Save, they both happen at the same time.*

## Check vs Defense, Save, or DC

### Check vs Defense (Damage Only)

Actions that attempt to deal damage, requires you to make an Attack Check against the target's Defense to determine whether or not the Attack hits the target. This type of Action is called an **Attack** (see ["Attacks" on page 33](#page-32-1) for more information). The Action's description will state whether the Attack Check is made against the target's PD or AD (see ["Defenses" on page 34](#page-33-1) for more information). If the result of the Attack Check is equal to or greater than the target's Defense, then the Attack hits.

### Check vs Save (Effect Only)

Actions that attempt to impose an effect on a creature (such as a Condition) require you to make a Check (such as a Martial Check or Spell Check) against the target's Save. If the result of the Check is greater than the target's Save, the target becomes subjected to the effect. Depending on the **Failure Statements** of the Save, failing the Save by 5 or more may impose additional penalties on the target (see ["Degrees of Failure" on page 32](#page-31-1) for more information).

### Check vs DC

Actions that target you or your allies require you to make a Check (such as a Martial Check or Spell Check) against the Action's own DC to determine success or failure. Depending on the **Success Statements** of the Action, exceeding the DC by 5 or more may grant additional benefits (see ["Degrees of Success" on page 32](#page-31-2) for more information).

### Dynamic Attack Save (Damage & Effect)

Some Actions attempt to deal damage and impose a Condition on the target (see ["Dynamic Attack Saves" on](#page-27-1) [page 28](#page-27-1) for more information). These Actions require you to make an Attack Check against the target's Defense, and require the target to make a Save against your Save DC. The Attack determines if the Action deals damage to the target, and the target's Save determines if they're subjected to the effects of the Action.

## Managing Multiples

### Making Multiple Saves

Some Actions force the target to make a Save against your Save DC to avoid suffering a stated effect. If a creature is forced to make a Save against multiple effects that are a part of the same Action, the target only makes 1 Save of each type that's imposed by the Action.

> **Example:** *A Sorcerer casts a powerful Spell against an enemy that includes 3 different types of effects that require Saves. 2 of the effects require a Mental Save each, and 1 effect requires a Charisma Save. The target makes 1 Mental Save for both of the Mental Save effects, and 1 Charisma Save for the other effect.*

### Targeting Multiple Creatures

If an Action you perform targets more than 1 creature, or includes more than 1 in an Area of Effect (such as an Arc, Cone, Cylinder, Line, or Sphere), then you make 1 Check (such as an Attack Check, Martial Check, or Spell Check) against all creatures.

> **Example:** *If a PC makes an Attack that targets an area which includes 4 creatures, the PC would make 1 Attack Check and compare it to the Defense of each creature in the area.*

### Competing Effects

If you try to impose an effect on a target already under a similar one (such as opposing telekinesis or mind control), the GM may call for a contested Check between you and the effect's source (such as an opposing spellcaster or an enchanted object).

> *DC Tip: The GM decides when two effects are similar enough to compete with each other, so they decide when a contest is necessary.*

**Contest**: Make a contested Spell Check against the opposing source. If your effect already requires a Spell Check, use that result for the contest. **Success:** Your effect takes hold as the existing effect ends. **Failure or Tie:** Your effect fails, and the existing effect remains.

> **Example:** *A Vampire has charmed a noble with its mind control. A Spellcaster casts a a similar mind controlling Spell, attempting to wrest the noble's mind away from the vampire's control. The Spell Check the Spellcaster makes to cast their Spell is contested against a Spell Check the Vampire makes. If the result of the Spellcaster's Check is higher than the Vampire's Check, then the noble is now under the Spellcaster's mind control instead of the Vampire's.*

## Advantage & Disadvantage

When a creature has Advantage (ADV) on a Check or Save, it rolls two **d20** and takes the highest number rolled across both dice. If the creature has Disadvantage (DisADV) instead, it takes the lowest number across both dice.

> **Example:** *A creature has ADV on a Check. Normally it would roll a single d20 when making the Check, but because it has ADV it rolls two d20 instead and takes the highest number rolled.*

### **Gaining Advantage**

When a creature makes a Check or Save in Combat, it can spend 1 or more **AP** to gain ADV on its Check or Save per AP spent.

> **Example:** *A Barbarian chooses to make an Attack with a Greatmaul against a creature. The Barbarian can spend* **1 AP** *to grant themselves ADV on their Attack Check.*

> *DC Tip: DCs are designed primarily to be used outside of Combat. Since creatures can spend AP to gain ADV in Combat, the GM* **can** *replace the normal DC with the Encounter DC to reflect the difficulty of attempting the task during Combat. See the ["Starting Combat" on page 115](#page-114-1) for more information.*

### **Stacking ADV or DisADV**

Sometimes a creature might have multiple sources of ADV (or DisADV) on a single Check or Save.

**ADV X**: If a creature has multiple instances of ADV on a Check or Save, it has **ADV X** where X represents the number of additional dice the creature rolls when making the Check or Save. The creature rolls 1 additional d20 for each ADV it has on the Check or Save, and takes the highest number across all dice.

> **Example:** *A creature has ADV 2 on a Check. It rolls a d20 plus 2 additional d20 (3 total dice) and takes the highest number rolled across all of the dice.*

**DisADV X**: If a creature has multiple instances of DisADV on a Check or Save, it has **DisADV X** where X represents the number of additional dice the creature rolls when making the Check or Save. The creature rolls 1 additional d20 for each DisADV it has on the Check or Save, and takes the lowest number across all dice.

> **Example:** *A creature has DisADV 3 on a Check. It rolls a d20 plus 3 additional d20 (4 total dice) and takes the lowest number rolled across all of the dice.*

> **DC Tip:** *ADV 1 and DisADV 1 is the same thing as "regular" ADV and DisADV. When rolling a d20 to make a Check or Save, the 1 just represents the 1 additional d20 you're rolling, which is what happens with regular ADV and DisADV. Most of the time they'll simply be referred to as ADV and DisADV.*

### **Combining ADV & DisADV**

If a creature has both ADV and DisADV at the same time, each instance cancels out. If they all cancel out, the creature makes a standard d20 roll as usual. If there are any remaining ADV or DisADV, then it makes the roll with whatever ADV (or DisADV) is left over.

> **Example 1:** *If a creature had both ADV and DisADV then that would become a standard roll of a single d20. If you had DisADV 3 and also had ADV, then one of the ADV would cancel out one of the DisADV and you would be left with DisADV 2.*

> **Example 2:** *If a creature has both DisADV 3 and and ADV 2 on a Check, two of the ADV cancel out two of the DisADV, leaving only one DisADV remaining. The Check is then made with DisADV 1, which is just regular DisADV (rolling 2 dice and taking the lower number).*

> **DC Tip:** *Basically just subtract any ADV or DisADV from each other and see what you are left with, and if the answer is ever 0, then you just make a standard d20 roll.*

### **Variable ADV & DisADV**

Gaining ADV and DisADV on Checks made against other creatures is very common. Sometimes you might have to make a Check against a group of creatures where you have ADV or DisADV on the Check against some of the targets but not all of them. When that happens, follow these steps below:

- **1.** Make a Check against all targets you don't have ADV or DisADV against by rolling a single d20 and adding any relevant bonuses you have on the Check against the targets.
- **2.** For any additional targets you have ADV or DisADV against, roll a second d20 and compare it to the first d20 you already rolled. For all targets you have ADV against, choose the higher number rolled, and for DisADV choose the lower number rolled.
- **3.** If you have ADV/DisADV 2 or higher against any additional targets, repeat Step 2 for each additional dice you have to roll until you resolve the outcome of your Check against all targets.

> **Example:** *A Wizard targets 3 creatures with a Fireball Spell. It doesn't have ADV against the first target (rolls 1d20), has ADV against the second target (rolls 2d20), and ADV 2 against the third target (rolls 3d20). The Wizard rolls a d20 and uses it to determine the outcome of its Spell Check against the first target. It then rolls another d20 and compares it to the first d20 (total of 2d20s) to determine the outcome of its Spell Check against the second target. It then rolls another d20 and compares it to the first 2 d20s (total of 3d20s) to determine the outcome of its Spell Check against the third target.*

## Multiple Check Penalty

During Combat, each time a creature makes the same Check before the end of its turn, they suffer stacking DisADV on that type of Check, such as specific Flat Attribute Checks (Flat Might, Flat Agility, Flat Charisma, Flat Intelligence), Attack Checks, Spell Checks, and specific Skill Checks (Stealth, Athletics, Influence, etc.), and specific Trade Checks (Theatre, Blacksmithing, Leatherworking, etc.). This penalty only applies to Checks made during the creature's turn, and doesn't apply to Reactions taken on another creature's turn (unless otherwise stated).

- **1st Attempt:** Normal roll.
- **2nd Attempt:** DisADV 1 (roll 2 dice and take the lowest result).
- **3rd Attempt:** DisADV 2 (roll 3 dice and take the lowest result).
- **4th Attempt:** DisADV 3 (roll 4 dice and take the lowest result).

> **Example:** *If a creature casts a Spell by making a Spell Check, its first attempt would be a normal roll, but subsequent Spell Checks would have stacking DisADV (as shown above).*

> **DC Tip:** *The Multiple Check Penalty does not apply outside of Combat.*

**Multiple Action Penalties**: Some Actions have penalties when you take it multiple times, such as the Help Action. These penalties count as the Multiple Check Penalty for the purposes of game mechanics that apply to Multiple Check Penalties.

## Check & Save Outcomes

### **Critical Success & Failure**

When a creature rolls a **20** on a d20, the Check or Save gains a Critical Success. When a creature rolls a **1** on a d20, the Check or Save suffers a Critical Failure. A Critical Success or Critical Failure can affect the outcome in different ways, as determined by the type of Check or Save being made.

#### Attack, Martial, and Spell Checks

##### Critical Success

**Damage**: When a creature gains a Critical Success on an Attack, Martial, or Spell Check that deals damage, the Attack is considered a **Critical Hit** (automatically hits and deals **+2** damage).

**Effect**: When a creature gains a Critical Success on an Attack, Martial, or Spell Check that doesn't deal damage, the Check automatically succeeds even if the result would normally fail.

##### Critical Failure

When a creature gains a Critical Failure on an Attack, Martial, or Spell Check, it becomes **Exposed** against the next Attack made against it before the start of its next turn. They also suffer additional penalties depending on if the Check deals damage or not.

> *DC Tip: For Critical Failures, the GM could change the Condition to* **Hindered** *(your next Attack Check has DisADV) instead of* **Exposed** *at their discretion.*

**Damage**: When a creature suffers a Critical Failure on an Attack, Martial, or Spell Check that deals damage, the Attack automatically misses even if the result would normally hit.

**Effect**: When a creature gains a Critical Failure on an Attack, Martial, or Spell Check that doesn't deal damage, the Check automatically fails even if the result would normally succeed.

### Saves, Skill Checks, & Trade Checks

#### Critical Success

When a creature gains a Critical Success on a Save, Skill Check, or Trade Check, the Check or Save automatically succeeds even if the result would normally fail.

#### Critical Failure

When a creature suffers a Critical Failure on a Save, Skill Check, or Trade Check, the Check or Save automatically fails even if the result would normally succeed.

> **DC Tip:** *The GM should avoid asking PCs to make Checks where success shouldn't be possible. If a PC ties a heavy chain around a building, it shouldn't be possible for them to succeed on a Might Check to drag the building. Conversely, the GM should avoid asking PCs to make Checks where failure shouldn't be possible, like asking a PC to make a Might Check pick up a pebble. Unless the circumstances introduce the possibility of success or failure, try to refrain from asking for Checks for activities that are impossible to succeed or fail. Mistakes are going to happen and GMs might ask for a roll when they shouldn't have. The final outcome of a Critical Success or Critical Failure are up to the GM, and PCs should respect that.*

#### Contested Critical Outcomes

When multiple creatures gain a Critical Success in a contest (or all creatures suffer a Critical Failure), the creature with the highest total result wins the contest.

### **Degrees of Success & Failure**

#### Degrees of Success

If a creature succeeds on a Check or Save by 5 or more, they may gain additional benefits beyond those of a normal success. The Check or Save will include a success statement, such as **Success**, **Success (5)**, **Success (10)**, or **Success (each 5)**.

##### Success

If the success statement says **Success** then the creature gains the listed benefits if the result of its Check or Save is equal to or higher than the opposing DC, Check, or Save.

##### Success (each 5)

If a success statement says **Success (each 5)** then the creature gains the listed benefits for every 5 the result of its Check or Save is above the opposing DC, Check, or Save. Unless stated otherwise, the creature can gain the additional benefits multiple times.

> **Example:** *A Spell pushes a target back 3 Spaces on a successful Spell Check, but also includes the following success statement: "***Success (each 5)***: +1 Space." That means that each 5 points the Spell Check is above the opposing DC, Check, or Save, the target is pushed 1 additional Space.*

##### Success (5) & Success (10)

If a success statement says **Success (5)** then the creature gains the listed benefits when they succeed by 5 or more above the opposing DC, Check, or Save. Moreover, if the success statement says **Success (10)** then they also gain the listed benefits when they succeed by 10 or more above the opposing DC, Check, or Save. This can continue on to **Success (15)** and further.

> **Example:** *A Spell increases a creature's Speed by 1 on a successful Spell Check, but has the following success statements: "***Success (5):** *Ignore Difficult Terrain," and "***Success (10):** *Immune to* **Slowed***." That means that the creature's Speed is increased by 1 and ignores Difficult Terrain if its Spell Check is 5 above the Spell's DC, and the creature is also immune to the* **Slowed** *Condition if its Spell Check is 10 above the Spell's DC.*

#### Degrees of Failure

If a creature fails on a Check or Save by 5 or more, they may suffer additional penalties beyond those of a normal failure. The Check or Save will include a failure statement, such as **Failure**, **Failure (5)**, **Failure (10)**, or **Failure (each 5)**.

##### Failure

If a failure statement says **Failure** then the creature suffers the listed penalties if the result of its Check or Save is below than the opposing DC, Check, or Save.

##### Failure (each 5)

If a failure statement says **Failure (each 5)** then the creature suffers the listed penalties for every 5 the result of its Check or Save is below the opposing DC, Check, or Save. Unless stated otherwise, the creature can suffer the additional penalties multiple times.

> **Example:** *A trap deals* **4** *Fire damage to a target on a failed Save, but also includes the following failure statement: "***Failure (each 5)***: +1 damage." That means that each 5 points the Save is below the Trap's Save DC, the target takes an additional* **+1** *Fire damage.*

##### Failure (5) & Failure (10)

If a failure statement says **Failure (5)** then the creature suffers the listed penalties when they fail by 5 or more below the opposing DC, Check, or Save. Moreover, if the failure statement says **Failure (10)** then they also suffer the listed penalties when they fail by 10 or more below the opposing DC, Check, or Save. This can continue on to **Failure (15)** and further.

> **Example:** *A Curse imposes the* **Blinded** *Condition on a failed Save, but has the following failure statements: "***Failure (5): Deafened,***" and "***Failure (10): Doomed***." That means that the creature is both* **Blinded** *and* **Deafened** *if its Save is 5 below the Save DC, and the creature is also* **Doomed 1** *if its Save is 10 below the Save DC.*
