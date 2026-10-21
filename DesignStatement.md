# Decline and Fall

A political and economic wargame for 3-5 players. Playtime: 2-3 hours per scenario, with 3 scenarios. (Full game 6-9 hours)

## Central Tension

What made Rome fall? In this game, families desire to 'win' in the late Roman empire by having the most legitimacy (victory points). A collapsed Rome can spell doom for its most ardent benefactors: **[TODO: finish this sentence, the original ended at "a failed Rome ."]**

## End Game Conditions

| End game condition | What it means |
| --- | --- |
| Rome survives | Rome did not collapse! Simply add up any victory points for the last round, whoever has most wins. Emperor decides tie breaks. |
| Rome splinters | Too many players (1 in a 3 player, 2 in a 4/5 player) seceded from Rome for at least five rounds. Add up any victory points, including bonuses for separate kingdoms. |
| Rome falls | **Barbarians** have invaded too much of Rome. Players lose legitimacy depending on position, with the emperor losing most. |

**Open:** the exact threshold for "Rome falls" (for example, a number of estate cards and/or cities currently held by barbarians). Barbarian-held estate cards sit in a visible area next to the main board, so the number of cards there is the number the table can count at a glance.

## Barbarians

Barbarians are the external pressure on the empire. There is no separate barbarian track. They are both a **strength on the map** (barbarian army chits in a province) and a force that can **settle estates** (taking estate cards into the barbarian area). They enter the game in exactly two ways, and Rome's collapse is measured by the estate cards (and cities) they hold.

### Sources of barbarian pressure

| Source | When | Who handles it | Role |
| --- | --- | --- | --- |
| **Global events** | Phase 7, Imperial Court and Deals | The whole table (players argue over who responds) | Pacing backbone for each scenario |
| **Provincial crisis cards** | Phase 3, Event rolls (triggered by a governor's bad roll) | The governor of that province | Local variance. Prepared governors absorb it, unprepared governors suffer. |

### What barbarians do

- **Exist as a strength on the map.** Barbarian army chits in a province represent barbarian strength there. Each chit is a distinct source (the Picts, the Sassanids, and so on) with its own strength. Global events and crisis cards place them. Armies can fight them (see Armies and Combat), and defeating them earns points (legitimacy).
- **Settle estates.** When barbarians settle an estate, its card leaves its owner (or the neutral stack) and is placed in the **barbarian area next to the main board**, where everyone can see it. A settled estate card produces for no one. This reduces resource generation for Rome and moves the game toward the "Rome falls" ending.
- **Expand if left alone.** Barbarians that survive a round without being attacked grow and settle more (see Expansion below). Ignoring a problem makes it bigger, so the cost of inaction grows every round.
- **Can be conquered.** Players who defeat barbarians in Military actions earn points (legitimacy). *(Proposed: retaking a settled estate means defeating the barbarian strength in its province, then taking the card and placing a cube of your color on its map spot.)* A settled estate is both a drain on Rome and a bounty for players.

### Expansion

*Proposed, details still open:*

- At **Upkeep (phase 8)**, barbarians in a province that were **not attacked** during this round's Military phase **settle one estate** in that province. The card moves to the barbarian area next to the main board. Once a province has no estates left to settle, the barbarians move into a neighboring province.
- Barbarians that are left alone may also **gain reinforcements** (more barbarian chits, or a stronger source), so they grow stronger as well as wider. *(Open: how much.)*
- Barbarians placed by a **global event in phase 7** do not settle or grow that same round. They have had no chance to be answered yet, so players get a full round of warning.
- Spread should be **deterministic or near-deterministic** (for example, the player or governor of the affected province chooses which estate falls, or a fixed priority such as cities last). That keeps the board readable and lets players predict collapse.
- Players can **stop** spread by attacking. Defeating the barbarian chits in a province stops them from settling there.

### Barbarians and the end of the game

- Rome falls when the number of estate cards (and cities) held by barbarians passes a threshold (to be defined). Barbarian chits alone do not cause a fall. They matter because they settle estates.
- If Rome falls and Rome splinters would also trigger, **Rome falls takes precedence.** *(Proposed, not yet confirmed.)*

### Open questions on barbarians

1. ~~**Persistence:**~~ **Resolved:** barbarians spread if left alone. Still open: exact spread rules, spread rate, and whether cities can be taken the same way as estates.
2. **Snowball risk:** unchecked spread compounds. Is there a cap per round, or something that slows it (a strong garrison, a governor who prepared)?
3. **Pacing:** will the global event deck have early, middle, and late stacks so each scenario has its own arc?
4. **Governor incentives:** a governor could underprepare to let barbarians in and then conquer them for points. Is that an intended tension, or should the failing governor lose legitimacy when an estate falls on their watch?
5. **Floor and ceiling:** what guarantees that collapse is possible but not unavoidable?
6. ~~**Combat:**~~ **Proposed:** see Armies and Combat. Still open: who rolls for barbarians, and the exact numbers.
7. **Settling threshold:** how much barbarian strength does it take to settle an estate, and can a single chit settle one? Does a larger force settle more at once?
8. **Strength vs. settling:** if a barbarian chit is removed after it settles an estate, the barbarians are weak but hard to dislodge. If it stays, the province is occupied by force. Which is intended?
9. **Cities:** can barbarians take cities, or only estates? A city lost would take away legitimacy, which is a different kind of damage.
10. **Naming:** the governor action **Settle barbarians** and the barbarian ability to **settle estates** use the same word. Consider renaming one (for example, the governor action could become "Make treaty" or "Foederati").

## Armies and Combat

### Army chits

All armies are chits on the map.

| Army | Who controls it | Control cube |
| --- | --- | --- |
| **Private army** (Roman) | The family that raised it | **Yes.** A cube of the controller's color sits on the chit. Control can change hands. |
| **Office army** (East or West) | Whoever holds that commander's office | **No.** Control passes with the office. |
| **Barbarian army** | No one (the barbarians) | **No,** unless hired as **foederati**. A hired barbarian chit gets a cube of the hiring player's color and acts as that player's private army. |

Barbarian chits are unique per source, so each barbarian people has its own strength. For example, the Sassanids are stronger than the Picts.

### Army qualities

*Proposed.* Each army chit prints two numbers.

- **Size:** the number of dice it rolls in combat. *(Proposed: this is also the number of population cubes it represents.)*
- **Quality:** the number each die must meet or beat to score a **hit**.

| Quality | A die hits on | Typical armies |
| --- | --- | --- |
| **Levy** | 6 | Raiders, hastily raised private armies |
| **Regular** | 5+ | Frontier troops, most private armies |
| **Veteran** | 4+ | East and West field armies, Goths and Franks |
| **Elite** | 3+ | Palace troops, Sassanid heavy cavalry |

*Illustrative barbarian chits (to be tuned): Picts, Size 2, Levy. Franks, Size 3, Regular. Goths, Size 3, Veteran. Sassanids, Size 4, Elite.*

Size is quantity and Quality is how well each soldier fights, so a small elite army can match a big levy.

### Declaring a battle

1. **The attacker declares a defender** (a player, or the barbarians in a province) and which of their armies attack.
2. **Undeclared participants choose a side.** Every other player with an army in that province may **join the attacker, join the defender, or pass.** *(Proposed: all players choose in secret and reveal at once, so no one gains by waiting.)*
3. Both sides roll.

### Resolving a battle

*Proposed: one round of combat per battle.*

1. **Roll.** Every army chit on both sides rolls dice equal to its Size at the same time. Each die that meets its chit's Quality is a **hit**.
2. **Assign hits.** Each hit reduces the Size of one enemy chit by 1. The side taking hits chooses where they go, and each chit's controller decides for their own chit. *(Proposed: barbarians assign hits to their highest-Quality chit first.)* A chit reduced to Size 0 is destroyed.
3. **Winner.** The side that inflicted more hits wins. **Ties go to the defender.**
4. **Retreat.** Surviving losers retreat to an adjacent province. *(Open: what if there is none?)*

### Aftermath

- **Beating barbarians** earns legitimacy. *(Proposed: each barbarian chit is worth points equal to its printed Size, shared among the winning side's participants.)*
- **Beating a player** lets the attacker take the estate card at stake and place a cube of their color on its map spot.
- **Foederati:** a barbarian chit hired by a player gets that player's control cube and then fights as their army.

### Open questions on combat

1. **Who rolls for barbarians?** Options: the table rolls for them with fixed rules, or the player to the attacker's left does. They should make no decisions.
2. **Joining from nearby:** can armies in an adjacent province join a battle, or only armies already in the province?
3. **Damage:** are reduced chits tracked with markers, or flipped to a damaged side? Does damage heal at Upkeep, or only by paying?
4. **Destroyed private armies:** does the controller lose the population cubes the chit represented?
5. **Office armies:** who pays their upkeep, and can they attack players? How does that interact with the emperor's funding and usurpation?
6. **Hiring foederati:** which action does it? The governor action **Settle barbarians** could be that action, which would also fix its naming clash with barbarians settling estates. What stops the hired chit from defecting if it isn't paid?
7. **Numbers:** one round or several? Are Size and Quality tiers right? These should be tested before they are fixed.
8. **Defender advantage:** is "ties go to the defender" enough, or should fortifications and terrain matter?

## Economy

### Cubes are population

A cube represents population. Each family's cubes are in one of three places:

- **On an estate**, where the cube works the land and the estate produces.
- **In a city**, where the cube counts toward legitimacy (victory points).
- **In an army**, where the cube is a soldier and no longer produces anything. *(Proposed: an army chit's printed Size is the number of population cubes it represents. See Armies and Combat.)*

Moving a cube from one use to another is the central trade-off of the game. A new army costs income, and a stronger city costs both income and defense.

Other cubes in the game:

- **Unrest cubes** on governorships (see Unrest below).

### Resources

There are three resources:

| Resource | What it is for |
| --- | --- |
| **Grain** | Feeding and growing population. Paying for new cubes, and upkeep of 1 grain per 2 cubes at the end of each round. |
| **Money** | Gold. The currency of politics and the state. *(Proposed: Patronage, Donative, Audit province, imperial military funding, and army upkeep. Debase currency affects it.)* |
| **Resources** | General materials. *(Proposed: building and equipping, such as Develop province, Invest in city, and army upkeep.)* |

Each estate card produces **one type** (grain, money, or resources), printed on the card, so provinces have an identity (for example, grain provinces, mining provinces, and wealthy trade provinces). At Production, each player adds up the output of the estate cards in front of them and takes that many **resource chits** from the supply, which they keep on their player mat. Neutral estate cards, kept with the governor card, produce for the imperial treasury, which is a pile of resource chits.

### Estates

Estates are **cards**. Each estate card shows its resource type and yield, and each corresponds to a spot on the map in its province.

- **Neutral estates** are kept with the **governor card** for that province. This keeps accounting simple: the governor card holds everything that feeds the imperial treasury.
- **Owned estates:** when a player acquires an estate, they **take the card** and place a **cube of their color on its spot on the map** to show they own it. The card in front of the player gives the production details, and the cube on the map shows ownership at a glance.
- **Barbarian-held estates:** the card is moved to the **barbarian area next to the main board**, where it is clearly visible to everyone. It produces for no one. The size of this area at any moment shows how close Rome is to falling.

**Estate capacity** is the number of estate spots in a province that have been developed. Undeveloped spots are empty. *(Proposed: the map prints a fixed number of spots per province, and the Develop province action fills an empty spot with an estate card.)*

### New population

New cubes enter the game through an action that **costs grain** (see **Grow population** in Family actions). Population is not fixed, so a family can grow, but growth is paid for in grain and competes with every other use of grain.

*Open: how much grain a new cube costs, where the new cube is placed (estate, city, or army), whether there is a limit per round, and what happens when grain runs short (see questions below).*

## Unrest

Each governorship tracks unrest with cubes.

- Each time a province's roll in phase 3 **does not** trigger a crisis, an **unrest cube** is placed on that governorship.
- Unrest cubes make the **next crisis more likely** in that province. Quiet times build pressure, which is a good fit for the "decline" theme.
- Unrest can be removed by **Lavish population** (governor action). It can also be added by **Levy tax** (governor action).

*Open: how unrest changes the roll (a modifier per cube, or lowering the crisis threshold), whether a triggered crisis clears the cubes, and whether there is a cap.*

## Round skeleton

Barbarian touchpoints are marked with **(B)**.

1. **Family actions**
   - **Patronage:** spend resources to convert a neutral estate to you. Take its card from the neutral stack with the governor card and place a cube of your color on its map spot.
   - **Invest in city:** spend resources to increase your population in a Roman city, which earns legitimacy.
   - **Develop province:** increase the estate capacity of a province by adding a new estate card for an empty spot, which gives room for more estates and more working cubes. *Cost to be decided.*
   - **Grow population:** spend grain to add a new cube of yours. *Cost and placement to be decided.*
   - **Raise army:** convert population into an army that you control. *(Proposed: this moves cubes from estates or cities into the army, and may also cost resources.)*
   - **Declare secession:** break from Rome. This starts the five-round secession clock.
   - **Alliance:** make a binding agreement with another family. *Details to be decided.*
   - **Embezzle:** turn a province's resources (the output of its neutral estate cards) into your own. *Note: this action may be removed.*
2. **Governor actions (B)**: governors commit resources to prepare for crises before any roll.
   - **Handle crisis:** resolve a hidden event card by resolving its "handled" side.
   - **Lavish population:** spend resources to remove unrest cubes from your governorship.
   - **Levy tax:** gain resources for your province at the cost of adding unrest cubes.
   - **Settle barbarians:** come to terms with barbarians in your province. *Details to be decided (see open questions). The name may change, since barbarians can also settle estates.*
   - **Transfer resources:** turn your province's resources (the output of the neutral estate cards with your governor card) into your own. *Note: this action may be removed.*
3. **Event rolls (B)**: each governor rolls.
   - On a **bad roll**, a crisis card for that province is drawn and resolved. Crisis cards may place barbarian chits in the province.
   - On a **safe roll**, an **unrest cube** is placed on that governorship, making the next crisis more likely.
4. **Emperor actions**: the emperor distributes imperial funds to the military, now knowing which crises occurred.
   - **Audit province:** view the crises in a province by paying that province's governor 1 resource.
   - **Donative:** pay the legions extra to buy their loyalty. *Details to be decided.*
   - **Debase currency:** gain extra resources now, at a cost to be decided.
   - **Confiscate estate:** seize an estate card from a player, replacing their cube on the map spot. *Cost to be decided.*
5. **Military actions (B)**: armies may attack barbarian chits in a province and retake settled estates. Defeating barbarians earns points. Players may also conquer estates from each other.
   - **Attack:** attack barbarians in a province, or an estate held by another player (see Armies and Combat). The winner takes any estate card at stake and places a cube of their color on its map spot.
   - **Move army:** move an army to an adjacent province, or, for 1 resource per ocean crossed, further.
6. **Production (B)**: each estate card produces its printed resource (grain, money, or resources) for its owner, or for the imperial treasury if neutral. Barbarian-held estate cards produce nothing.
7. **Imperial Court and Deals (B)**: a global event is resolved, which may place or strengthen barbarians. Players also negotiate over who must respond, trade estates, and handle court business.
8. **Upkeep and Retirements (B)**:
   - **Population upkeep:** each player pays **1 grain for every 2 cubes** they employ, whether in cities, on estates, or in armies. *(Proposed: an army chit counts as cubes equal to its Size.)*
   - **Army upkeep:** armies require **additional costs of money and resources**, paid by the player who controls them. *Amounts to be decided.*
   - **Loyalty check (notice):** if an **East or West commander has too much loyalty** among their armies, the armies **proclaim the commander emperor**. Then one of two things happens:
     - the commander's player **attempts to conquer Rome**, or
     - the army **turns hostile** and attempts it **on its own**.
     *Notice: this is a placeholder. Loyalty is not yet defined (see open questions on actions).*
   - Barbarians that were not attacked settle estates and grow.
   - Offices rotate.

### Open questions on actions

1. **Embezzle and Transfer resources overlap.** Both turn province resources into the actor's own, and both are flagged as possibly removable. If one stays, which? A governor taking a cut is the more thematic of the two.
2. **Unrest mechanics:** how many cubes can pile up, and how much does each one raise the odds? Does a crisis clear the cubes, or only Lavish population?
3. **Levy tax:** I read "at the cost of cubes" as adding unrest cubes. Is that right, and how many cubes per use?
4. **Handle crisis vs. the Event roll:** a governor can resolve a hidden card's "handled" side in phase 2. Does that remove the card from the province's deck, and does it affect unrest?
5. **Settle barbarians:** one option is that it stops barbarians from settling more in your province, but any estates they already hold stay lost to Rome (or produce less). Does a deal remove their chits, and do estates they already hold still count toward "Rome falls"?
6. **Audit province:** the emperor audits after governors have acted and crises have rolled. Can it reveal cards a governor is still holding, or only what has happened?
7. **Move army and Attack:** who pays for movement, and can an army move and attack in the same Military phase?
8. **Patronage:** is the price flat or based on the estate card's yield? Can it convert estates owned by other players, or only neutral ones?
9. **Confiscate estate:** what stops the emperor from using it constantly (a legitimacy cost, or a limit per round)? Can it target secessionists?
10. **Grain shortage:** what happens when a player can't pay their grain upkeep (1 per 2 cubes)? Does an odd number of cubes round up or down? Options include losing cubes, adding unrest, or both. This is a natural way to make decline gradual.
11. **Raise army and Grow population:** do new cubes come from the supply, and is there a cap on total cubes per player or on the board?
12. **Embezzle and Transfer resources:** which resource do they move: grain, money, or resources? They would play very differently. Money is the most thematic target for a skimming governor.
13. **Which actions cost which resource?** Lavish population and Levy tax look like grain actions. Patronage, Donative, Audit province, and military funding look like money actions. Develop province, Invest in city, and Raise army may lean on resources. Debase currency affects money. Confirm each.
14. **Develop province:** what does it cost, and which resource? Does the new estate card go to the developer, or to the neutral stack with the governor card? Is there a maximum capacity per province? Can barbarian-occupied provinces be developed?
15. **Army upkeep terms:** how much money and how many resources per army? Also, how do imperial funds from the emperor offset a commander's army upkeep, and in which resource are they paid?
16. **Resource chits:** all resources are tracked with chits on the player mat, with printed icons and two denominations (proposed: 1 and 5). Is there a cap per resource (the number of chits in the box) to create scarcity? Are there enough small chits to make change?
17. **Loyalty and proclamation:** how is loyalty tracked (cubes on the office card, a track, or something else), what raises it (Donative, victories, unpaid armies), and what is the threshold for "too much"? Also: who chooses between the player conquering Rome and the army turning hostile? One reading is that the player chooses to lead the army, and if they decline, the army goes hostile. What does "conquering Rome" mean on the map (taking the capital, replacing the emperor, or something else)? What happens to the sitting emperor, and to the commander's office, if the attempt succeeds or fails?
18. **Declare secession:** what happens to the seceding family's estate cards, armies, and offices when they declare?
19. **Card and cube agreement:** ownership is now shown in two places (the card in front of the player and the cube on the map spot). Which is authoritative if they disagree?
20. **Estate cubes:** is the cube on an owned estate's map spot both the ownership marker and the population working it (and so counted for grain upkeep)? Or are workers separate from the ownership marker?
21. **Barbarian area:** when barbarians take an estate, is the owner's cube removed from the map spot? Should the empty spot be marked in some way? Also, each card needs to show which province it belongs to, so that spread and reconquest work. Should there be a marked limit on the barbarian area (the number of cards at which Rome falls)?
22. **Estate deck:** how many cards, and do they have special effects beyond type and yield? How are neutral estates dealt out at the start of each scenario?
23. **Governor card accounting:** what exactly does the governor card track? One reading is that it records what its neutral estates add to the imperial treasury each round. Confirm the intended bookkeeping.

### Why barbarians land where they do

- Barbarian chits placed in phase 7 cannot be answered until next round's Military phase, so everyone gets one round of warning.
- Crisis cards appear in phase 3, after governors have committed their preparation, so governors prepare blind.
- Settled estates are checked at Production, which is where the cost to Rome is felt (barbarian-held cards produce nothing).
- Spread happens at Upkeep, after players have had their Military phase to respond.

## Components

*Proposed component list. Quantities are to be decided once the card and cube counts are settled.*

### Board and mats

- **Main game board:** 10-12 provinces, each with city spots, estate spots (matched to estate cards), adjacency, and ocean crossings. Includes a round track and a place for the imperial treasury.
- **Barbarian area:** a space next to the main board for barbarian-held estate cards, with a marked line where Rome falls.
- **Player mats:** one per family. Each mat holds the player's resource chits (grain, money, and resources zones), their reserve of population cubes, their estate cards, and any army chits not yet placed on the map.

### Cards

- **Governor cards:** one per province. Each holds the province's neutral estate stack, its unrest cubes, and its crisis cards.
- **Estate cards:** show a resource type, a yield, and the province they belong to.
- **Crisis cards:** per province, with a "handled" side and an unprepared side.
- **Global event deck:** early, middle, and late stacks, resolved at the Imperial Court.
- **Office cards:** Emperor, Commander of the East, and Commander of the West.

### Cubes and chits

*Army chits are a different size or shape from resource chits, so the two can't be confused.*

- **Population cubes:** one color per player.
- **Resource chits:** three types, one each for grain, money, and resources, with a printed icon for each type. *(Proposed: two denominations, 1 and 5.)*
- **Private army chits:** Roman armies raised by families. Each shows a Size and a Quality.
- **Office army chits:** the East and West armies, controlled by the holders of those offices.
- **Barbarian army chits:** one chit per barbarian source (Picts, Goths, Franks, Huns, Sassanids, and so on), each with its own Size and Quality. Barbarian-held estates are shown by moving their cards to the barbarian area, so barbarian chits and the barbarian area do different jobs.
- **Unrest cubes:** placed on governorships.
- **Control cubes:** a cube of a player's color placed on a private army chit (or a hired foederati chit) to show who controls it.

### Other

- **Dice:** for governor crisis rolls.
- **Markers:** a round marker and secession clock markers.
- **Rulebook, three scenario sheets (the eras), and a player aid** with the round skeleton and action list.

### Open questions on components

1. **Army chits and cubes:** proposed that a chit's printed Size equals the population cubes it represents. Confirm, and decide whether the cubes stay on the mat or sit on the chit.
2. ~~**Black cubes:**~~ **Replaced:** barbarians are now barbarian army chits. Black cubes can be dropped from the component list unless a new use appears.
3. **Cube colors:** five player colors, unrest, and black is still a lot of cubes to tell apart. Which should be different shapes or sizes?
4. **Card counts:** how many estate cards and crisis cards per province? This decides prototype printing cost.
