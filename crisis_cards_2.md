---
backgroundImagePath: ./Backgrounds/Crisis.png
textFields:
  - id: card_name
    x: 265
    y: 15
    width: 470
    height: 110
    fontFamily: Arial
    fontSize: 44
    color: '#000000'
    horizontalAlignment: Left
    verticalAlignment: Center
    wordWrap: true
  - id: card_type
    x: 265
    y: 130
    width: 470
    height: 60
    fontFamily: Arial
    fontSize: 24
    color: '#CCCCCC'
    horizontalAlignment: Left
    verticalAlignment: Center
    wordWrap: true
  - id: card_id
    x: 265
    y: 200
    width: 470
    height: 45
    fontFamily: Arial
    fontSize: 24
    color: '#CCCCCC'
    horizontalAlignment: Left
    verticalAlignment: Center
    wordWrap: false
  - id: where
    x: 25
    y: 255
    width: 700
    height: 60
    fontFamily: Arial
    fontSize: 24
    color: '#CCCCCC'
    horizontalAlignment: Left
    verticalAlignment: Center
    wordWrap: true
  - id: flavor
    x: 25
    y: 320
    width: 700
    height: 80
    fontFamily: Arial
    fontSize: 26
    color: '#BBBBBB'
    horizontalAlignment: Left
    verticalAlignment: Center
    wordWrap: true
  - id: handled
    x: 25
    y: 410
    width: 700
    height: 230
    fontFamily: Arial
    fontSize: 30
    color: '#EEEEEE'
    horizontalAlignment: Left
    verticalAlignment: Top
    wordWrap: true
  - id: unhandled
    x: 25
    y: 650
    width: 700
    height: 330
    fontFamily: Arial
    fontSize: 30
    color: '#FF8888'
    horizontalAlignment: Left
    verticalAlignment: Top
    wordWrap: true
iconOverlays:
  - id: icon
    imagePath: "Icons/Crisis-Combat-250px.png"
    x: 0
    y: 0
    width: 250
    height: 250
---

# Decline and Fall: Crisis Cards

70 crisis cards (22 military, 24 economic, 24 sociopolitical) for the card generator. Every card can strike any province.

Conventions: "Barbarians" means the barbarian people whose lands lie nearest the province in question. Severity I costs 4 to handle (Army Size 2+), Severity II costs 5 to 6 (Army Size 3+), Severity III costs 8 to 9 (Army Size 5+).

Run: `dotnet run --project DeclineAndFallCardGenerator -- crisis_cards.md`

## Crisis Cards

| card_name | card_type | card_id | where | flavor | handled | unhandled | icon |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Barbarian Raiders | Invasion · Severity I | M01 | Where: Any province | Small warbands slip across the frontier at dusk. | Handled: Pay 4 materials, or Army option (Size 2+). Raiders turned back. | Unhandled: Place Barbarians (Size 3). One estate Disrupted at the next Production. Add 1 unrest. | military |
| Barbarian Raiders | Invasion · Severity I | M02 | Where: Any province | They come for cattle, grain and captives, and leave burning barns. | Handled: Pay 4 grain (provisions to buy them off), or Army option (Size 2+). | Unhandled: Place Barbarians (Size 3). The estate with the highest grain yield is Ruined. | military |
| Barbarian Raiders | Invasion · Severity I | M03 | Where: Any province | The watchtowers are held by one old soldier apiece. | Handled: Pay 4 money (pay the border scouts), or Army option (Size 2+). | Unhandled: Place Barbarians (Size 3). The governor loses 2 legitimacy. Add 1 unrest. | military |
| The Frontier Unmanned | Invasion · Severity II | M04 | Where: Any province | The garrison went unpaid and went home to farm. | Handled: Pay 6 materials and 2 money (back pay), or Army option (Size 3+). Frontier restored. | Unhandled: Place Barbarians (Size 4). One estate Ruined. The governor loses 1 legitimacy. | military |
| Barbarian Incursion | Invasion · Severity II | M05 | Where: Any province | Whole districts burn while the garrison waits for orders. | Handled: Pay 6 materials (fortified towns, field levies), or Army option (Size 3+). | Unhandled: Place Barbarians (Size 4). One estate Ruined and one city cube removed (governor’s choice). | military |
| Barbarian Incursion | Invasion · Severity II | M06 | Where: Any province | A crossing nobody was watching. | Handled: Pay 6 materials (emergency levies), or Army option (Size 3+). | Unhandled: Place Barbarians (Size 4). Every player with cubes in the province loses 2 of them (their choice). | military |
| Barbarian Incursion | Invasion · Severity II | M07 | Where: Any province | The chieftains name their price in gold and in hostages. | Handled: Pay 6 money (subsidies and hostages), or Army option (Size 3+). | Unhandled: Place Barbarians (Size 4). Add 2 unrest. One estate Ruined. | military |
| The Winter Crossing | Invasion · Severity III | M08 | Where: Any province | Winter ice bridges the frontier river and whole peoples pour across. | Handled: Pay 9 materials (emergency levies, fortified crossings), or Army option (Size 5+). Contained, not averted: Place Barbarians (Size 2). | Unhandled: Place Barbarians (Size 6). One estate Settled immediately and one Ruined. The governor loses 2 legitimacy. | military |
| The Great Horde | Invasion · Severity III | M09 | Where: Any province | Scouts report a column of wagons that takes three days to pass. | Handled: Pay 9 materials (every wall manned, every ford staked), or Army option (Size 5+). Contained, not averted: Place Barbarians (Size 2). | Unhandled: Place Barbarians (Size 6). One estate Settled immediately. Two city cubes removed. Add 2 unrest. | military |
| Tribe on the Move | Migration · Severity II | M10 | Where: Any province | A whole people with wagons and herds asks for land, or takes it. | Handled (treaty): Pay 6 grain to feed them and settle them on marginal land. Add 1 unrest. | Unhandled: Place Barbarians (Size 4). One estate Ruined. If it is not defeated by Upkeep, it Settles an estate and a Size 1 band enters the adjacent province nearest Italia (no band follows if this is Italia). | military |
| Refugees at the River | Migration · Severity II | M11 | Where: Any province | Thousands beg admission, fleeing something worse behind them. | Handled (treaty): Pay 6 grain. They are admitted, and the governor may take a Barbarians chit (Size 1) as foederati under their control cube (upkeep applies). | Unhandled: Starving crowds break through. Place Barbarians (Size 3) and add 2 unrest. If not defeated by Upkeep, it Settles an estate and a Size 1 band migrates as in M10. | military |
| Refugees Cheated | Migration · Severity II | M12 | Where: Any province | The officers sell the starving newcomers dog meat in exchange for slaves. | Handled (treaty): Pay 4 grain and 3 money (honest rations, officials replaced). They are admitted. Add 1 unrest. | Unhandled: The newcomers rise in fury. Place Barbarians (Size 4). One estate Ruined. Add 2 unrest. The governor loses 2 legitimacy. | military |
| Raiders from the Sea | Invasion · Severity II | M13 | Where: Any coastal province (redraw if inland) | Longships strike the coastal villas. | Handled: Pay 6 materials (shore forts, patrol ships), or Army option (Size 3+). | Unhandled: Place Barbarians (Size 3). Two estates Ruined. | military |
| Raiders from the Sea | Invasion · Severity II | M14 | Where: Any coastal province (redraw if inland) | Sails on the horizon, and the war galleys are laid up. | Handled: Pay 6 materials (war galleys), or Army option (Size 3+). | Unhandled: Place Barbarians (Size 3). One estate Ruined and one city cube removed. Add 1 unrest. | military |
| The Armada | Invasion · Severity III | M15 | Where: Any coastal province (redraw if inland) | Hundreds of hulls, and every harbor is suddenly a target. | Handled: Pay 9 materials (hasty fleets, harbor chains), or Army option (Size 5+). Contained, not averted: Place Barbarians (Size 2). | Unhandled: Place Barbarians (Size 5). Two estates Ruined and one city cube removed. The governor loses 2 legitimacy. | military |
| Heavy Cavalry Raid | Invasion · Severity II | M16 | Where: Any province | Armored horsemen strike deep and withdraw with captives. | Handled: Pay 6 materials, or Army option (Size 3+). | Unhandled: Place Barbarians (Size 4). One estate Ruined. The governor loses 1 legitimacy. Add 1 unrest. | military |
| The Great Offensive | Invasion · Severity III | M17 | Where: Any province | The frontier fortresses are tested all at once. | Handled: Pay 9 materials (fortress lines manned, passes held), or Army option (Size 5+). Contained, not averted: Place Barbarians (Size 2). | Unhandled: Place Barbarians (Size 6). One estate Settled immediately and one Ruined. The governor loses 2 legitimacy. | military |
| The City Besieged | Invasion · Severity III | M18 | Where: Any province | The gates are shut, the granaries counted, and the enemy camped at the walls. | Handled: Pay 5 money and 4 grain (ransom and provisions), or Army option (Size 5+). | Unhandled: Place Barbarians (Size 5). Two city cubes removed. Every player with cubes in a city of the province pays 2 money or loses another city cube. Add 2 unrest. | military |
| Federates Revolt | Rebellion · Severity II | M19 | Where: Any province | Allies on the payroll discover how few soldiers stand against them. | Handled: Pay 6 money (arrears and a grant of land), or Army option (Size 3+). | Unhandled: Place Barbarians (Size 4). Each army chit in the province loses 1 Size. One estate Ruined. | military |
| The Field Army Destroyed | Defeat · Severity III | M20 | Where: Any province (redraw if no Roman army is in the province) | The emperor’s army marched out in the summer heat and did not come back. | Handled: Pay 6 materials and 3 money (new arms, new recruits). | Unhandled: Every Roman army chit in the province is destroyed. Place Barbarians (Size 4). The governor loses 3 legitimacy. Add 2 unrest. | military |
| Tribal Revolt | Rebellion · Severity II | M21 | Where: Any province | A client prince and his clans conclude that Rome is no longer worth the tribute. | Handled: Pay 6 money (renewed subsidies and fresh hostages), or Army option (Size 3+). | Unhandled: Place Barbarians (Size 4). Add 2 unrest. One estate Ruined. | military |
| Fortress Betrayed | Invasion · Severity II | M22 | Where: Any province | A gate is opened from inside, and a garrison dies in its sleep. | Handled: Pay 6 materials (relieving columns, replacement garrison), or Army option (Size 3+). | Unhandled: Place Barbarians (Size 4). Two city cubes removed. The governor loses 2 legitimacy. | military |
| Poor Harvest | Economic · Severity I | E01 | Where: Any province | A wet spring and a dry summer. | Handled: Pay 4 grain (open the reserve granaries). | Unhandled: Every estate in the province is Disrupted (grain) at the next Production. Add 1 unrest. | economic |
| Poor Harvest | Economic · Severity I | E02 | Where: Any province | Blight on the wheat and rust on the vines. | Handled: Pay 4 grain (seed corn from the reserves). | Unhandled: Every estate in the province is Disrupted (grain) at the next Production, and the highest-grain estate is Ruined. | economic |
| Famine Prices | Economic · Severity II | E03 | Where: Any province | Hoarders sit on the grain and the price doubles. | Handled: Pay 6 grain (price caps, state purchases). | Unhandled: At Upkeep, every player with cubes in the province pays 3 extra grain. Add 2 unrest. | economic |
| The Price Edict | Economic · Severity II | E04 | Where: Any province | The emperor fixes the price. The grain vanishes from the market. | Handled: Pay 5 grain and 2 money (requisitions, informers, bribes). | Unhandled: Every estate in the province is Disrupted (grain) at the next Production. Add 2 unrest. The governor loses 1 legitimacy. | economic |
| The Flood Fails | Economic · Severity III | E05 | Where: Any province | The river comes late, then not at all. | Handled: Pay 8 grain (relief convoys, tax remission). The two highest-grain estates are still Disrupted (grain) at the next Production. | Unhandled: Every estate is Disrupted (grain) for the next three Productions. Add 3 unrest. | economic |
| Locusts | Economic · Severity II | E06 | Where: Any province | The swarm darkens the sky and strips the fields to the stalk. | Handled: Pay 6 grain (emergency imports, bounties on the larvae). | Unhandled: Every estate is Disrupted (grain) for the next two Productions. One estate Ruined. Add 1 unrest. | economic |
| Plague | Economic · Severity III | E07 | Where: Any province | Pestilence follows the grain ships up every river. | Handled: Pay 6 grain and 3 money (quarantine, physicians, burial pits). Add 1 unrest. | Unhandled: Every player with cubes in the province loses 3 of them (their choice of estates, cities or armies). Neutral estates are Disrupted at the next Production. Add 2 unrest. | economic |
| Plague | Economic · Severity III | E08 | Where: Any province | Two thousand die in a single day, and the carts cannot keep pace. | Handled: Pay 5 grain and 4 money (burial pits, physicians, a city sealed). | Unhandled: Every player with cubes in the province loses 2 city cubes there. Every estate in the province is Disrupted at the next Production. Add 2 unrest. | economic |
| Fever in the Harbor | Economic · Severity II | E09 | Where: Any province | A strange sickness starts among the dockworkers and does not stay there. | Handled: Pay 6 grain and 2 money (the port closed, the sick segregated). | Unhandled: Each player with cubes in the province loses 2 of them (their choice). The governor loses 1 legitimacy. Add 1 unrest. | economic |
| Mine Collapse | Economic · Severity II | E10 | Where: Any province | The galleries were never properly shored. | Handled: Pay 6 materials (shoring, new shafts, rescue crews). | Unhandled: The estate with the highest materials yield is Ruined, and the next highest is Disrupted (materials) for two Productions. | economic |
| Debased Coinage | Economic · Severity II | E11 | Where: Any province | Merchants refuse the new silver and demand goods. | Handled: Pay 6 money (recoinage, bullion reserves). | Unhandled: Every estate in the province yields 1 less money (minimum 0) for the next two Productions. Add 1 unrest. | economic |
| Runaway Prices | Economic · Severity III | E12 | Where: Any province | A day’s wage buys last year’s bread. Everyone hoards and no one sells. | Handled: Pay 9 money (a sound coinage, a bonus to the troops). | Unhandled: Every estate in the province yields 2 less money (minimum 0) for the next two Productions. Every player with cubes there pays 2 money at Upkeep. Add 2 unrest. | economic |
| Caravans Diverted | Economic · Severity II | E13 | Where: Any province | A rival warlord offers the traders a better road. | Handled: Pay 5 money (tolls and bribes). | Unhandled: The two estates with the highest money yield are Disrupted (money) for the next three Productions. | economic |
| Corrupt Tax Collectors | Economic · Severity I | E14 | Where: Any province | The revenue goes out the door and never comes home. | Handled: Pay 4 money (audit and replace the collectors). | Unhandled: Neutral estates in the province are Disrupted at the next Production. The imperial treasury loses 3 money. | economic |
| Bandits on the Roads | Economic · Severity II | E15 | Where: Any province | Nothing moves without an armed escort. | Handled: Pay 6 materials (patrols, road forts). | Unhandled: Next round, no Patronage or Develop province in this province. The estate with the highest materials yield is Disrupted (materials) for two Productions. Add 1 unrest. | economic |
| Brigands in the Hills | Economic · Severity II | E16 | Where: Any province | Brigands hold the passes and sell safe conduct by the mile. | Handled: Pay 5 money (ransoms, hired guards), or Army option (Size 3+). | Unhandled: Two estates are Disrupted at the next Production. Each player with cubes in the province pays 2 money or loses 1 cube. Add 1 unrest. | economic |
| Earthquake | Economic · Severity II | E17 | Where: Any province | Aqueducts crack and whole quarters fall. | Handled: Pay 5 materials and 2 money (emergency rebuilding). | Unhandled: One estate Ruined, and two city cubes in the province are removed (governor’s choice). Add 1 unrest. | economic |
| The Sea Withdraws | Economic · Severity III | E18 | Where: Any coastal province (redraw if inland) | The harbor drains, the fish flop on the mud, and then the wave comes in. | Handled: Pay 8 materials and 2 money (rescue, clearance, rebuilding). | Unhandled: Two estates Ruined and three city cubes removed (governor’s choice). The governor loses 1 legitimacy. Add 2 unrest. | economic |
| Army Pay Arrears | Economic · Severity II | E19 | Where: Any province | The paymaster’s chests arrived empty. | Handled: Pay 6 money. | Unhandled: Each Roman army chit in the province loses 2 Size to desertion. If no armies are there, the governor loses 2 legitimacy instead. | economic |
| Pirates Seize the Cargo | Economic · Severity II | E20 | Where: Any coastal province (redraw if inland) | The grain and bullion ships never reach harbor. | Handled: Pay 6 materials (patrol galleys). | Unhandled: Each player with an estate in the province pays 4 money or has one of their estates there Disrupted (their choice). If there are neutral estates, the imperial treasury loses 3 money. | economic |
| Fire in the City | Economic · Severity II | E21 | Where: Any province | A blaze in the oil stores jumps from roof to roof. | Handled: Pay 5 materials and 2 money (firefighting gangs, tents and relief). | Unhandled: Two city cubes in the province are removed (governor’s choice) and one estate is Ruined. Add 1 unrest. | economic |
| The River in Flood | Economic · Severity II | E22 | Where: Any province | The river takes the warehouses, the mills and the bridge. | Handled: Pay 5 materials and 1 grain (levees, salvage). | Unhandled: The highest-grain estate is Ruined and every other estate is Disrupted (grain) at the next Production. | economic |
| The Grain Fleet Held Back | Economic · Severity III | E23 | Where: Any province | A rebel count keeps the harbor shut, and the city eats less each week. | Handled: Pay 6 grain and 3 money (a purchased peace, a fleet sent out). | Unhandled: Every player with cubes in the province pays 4 grain at Upkeep. Every estate is Disrupted (grain) at the next Production. Add 3 unrest. | economic |
| Abandoned Fields | Economic · Severity II | E24 | Where: Any province | Land lies fallow where no one can pay the tax and no one will stay. | Handled: Pay 5 money and 2 grain (remit the arrears, resettle the tenants). | Unhandled: One estate Ruined. Every other estate yields 1 less grain for the next two Productions. Add 1 unrest. | economic |
| Bread Riots | Sociopolitical · Severity I | S01 | Where: Any province | The dole is late and the crowd has noticed. | Handled: Pay 4 grain (emergency dole). | Unhandled: Add 2 unrest. The governor loses 2 legitimacy. | sociopolitical |
| Bread Riots | Sociopolitical · Severity II | S02 | Where: Any province | The crowd blames the minister for the empty granaries. | Handled: Pay 4 grain and 2 money (a scapegoat sacrificed, the dole restored). | Unhandled: Add 2 unrest. The governor loses 2 legitimacy. One city cube is removed. | sociopolitical |
| Tax Revolt | Sociopolitical · Severity II | S03 | Where: Any province | Villages refuse the collectors and barricade the road. | Handled: Pay 6 money (remit the arrears). | Unhandled: Add 3 unrest. No Levy tax in this province next round. One estate Disrupted. | sociopolitical |
| Revolt of the Client Queen | Sociopolitical · Severity III | S04 | Where: Any province | Humiliated by the tax-men, she calls the tribes to burn the colonies. | Handled: Pay 8 money (restitution, a new settlement), or Army option (Size 5+). | Unhandled: Add 3 unrest. Two city cubes removed. One estate Ruined. The governor loses 2 legitimacy. | sociopolitical |
| Governor Accused of Corruption | Sociopolitical · Severity II | S05 | Where: Any province | Petitioners are on their way to the emperor. | Handled: Pay 6 money (the witnesses are persuaded). | Unhandled: The governor loses 4 legitimacy. The emperor may Audit this province for free next round. Add 1 unrest. | sociopolitical |
| Governor Accused of Corruption | Sociopolitical · Severity II | S06 | Where: Any province | A delegation arrives in Rome with a list of grievances and a sack of receipts. | Handled: Pay 6 money (the delegation is bought off or lost on the road). | Unhandled: The governor loses 3 legitimacy. Add 2 unrest. The emperor may Audit this province for free next round. | sociopolitical |
| Strongman Proclaimed | Sociopolitical · Severity III | S07 | Where: Any province | A local commander is hailed by his men and the crowd takes up the cry. | Handled: Pay 8 money (donatives to the local troops). Add 1 unrest. | Unhandled: Add 4 unrest. The governor loses 3 legitimacy. One estate Disrupted. | sociopolitical |
| Purple from a Temple Banner | Sociopolitical · Severity III | S08 | Where: Any province | The cloak is torn from a banner, but the soldiers cheer him anyway. | Handled: Pay 6 money and 3 materials (donatives, a general sent to reason with him). | Unhandled: Add 3 unrest. The governor loses 4 legitimacy. Each army chit in the province loses 1 Size. | sociopolitical |
| Heresy Riots | Sociopolitical · Severity II | S09 | Where: Any province | Rival congregations fight for the great church. | Handled: Pay 6 money (a synod, with gifts for the bishops). | Unhandled: Add 3 unrest. Two city cubes in the province are removed (governor’s choice). | sociopolitical |
| Holy War in the Streets | Sociopolitical · Severity II | S10 | Where: Any province | Monks pull down a temple while the old families watch and remember. | Handled: Pay 5 money (compensation for the temple, a stern letter to the bishop). | Unhandled: Add 2 unrest. One city cube removed. One estate Ruined. The governor loses 1 legitimacy. | sociopolitical |
| Garrison Mutiny | Sociopolitical · Severity II | S11 | Where: Any province (redraw if no Roman army is in the province) | The soldiers have stopped taking orders. | Handled: Pay 6 money (donative). | Unhandled: Add 3 unrest. Each army chit in the province loses 1 Size. Armies in the province cannot Move or Attack in this round’s Military phase. | sociopolitical |
| The Legions Demand Discharge | Sociopolitical · Severity III | S12 | Where: Any province (redraw if no Roman army is in the province) | Sixteen years is enough, the whole camp chants, and the officers are in chains. | Handled: Pay 8 money (discharge bonuses, land grants). | Unhandled: Add 3 unrest. Each army chit in the province loses 2 Size. Armies in the province cannot Move or Attack in this round’s Military phase. | sociopolitical |
| Great Families Feud | Sociopolitical · Severity II | S13 | Where: Any province | Two houses, one magistracy, and daggers at the banquet. | Handled: Pay 6 money (arbitration and marriage gifts). | Unhandled: Every player with an estate in the province loses 2 legitimacy. Add 2 unrest. | sociopolitical |
| Beggars at the Gates | Sociopolitical · Severity I | S14 | Where: Any province | The countryside empties into the cities. | Handled: Pay 4 grain. | Unhandled: Add 2 unrest. Each player with cubes in a city of the province pays 2 grain or loses 1 city cube. | sociopolitical |
| Peasant Uprising | Sociopolitical · Severity III | S15 | Where: Any province | Ruined farmers burn the villa records and take the hills. | Handled: Pay 8 grain and 2 money (land concessions). Add 1 unrest. | Unhandled: Add 4 unrest. Every player with estate cubes in the province loses 2 of them, and one estate is Ruined. | sociopolitical |
| Bandit Kings | Sociopolitical · Severity III | S16 | Where: Any province | Rebel chiefs rule the countryside and call themselves its defenders. | Handled: Pay 6 materials and 3 money (a punitive column, an amnesty), or Army option (Size 5+). | Unhandled: Add 3 unrest. Every estate in the province is Disrupted at the next Production. Two estates Ruined. | sociopolitical |
| Elites Withdraw Support | Sociopolitical · Severity II | S17 | Where: Any province | The curiales flee their civic duties and the province stops running. | Handled: Pay 6 money (tax exemptions for the curiales). | Unhandled: Add 2 unrest. No Levy tax in this province next round. The governor may take only one governor action next round. | sociopolitical |
| Chariot Faction Riots | Sociopolitical · Severity III | S18 | Where: Any province | Blues and Greens turn the races into a battle. | Handled: Pay 8 money (games and spectacles). Add 1 unrest. | Unhandled: Add 3 unrest. Three city cubes in the province are removed (governor distributes). The governor loses 3 legitimacy. | sociopolitical |
| The Riot of the Statues | Sociopolitical · Severity II | S19 | Where: Any province | The mob topples the emperor’s statues, then realizes what it has done. | Handled: Pay 6 money (an embassy begging pardon, the ringleaders surrendered). | Unhandled: Add 3 unrest. The governor loses 3 legitimacy. Two city cubes removed. | sociopolitical |
| Petition for Autonomy | Sociopolitical · Severity II | S20 | Where: Any province | The provincial assembly asks why it should obey a distant court. | Handled: Pay 6 money (privileges and offices for the assembly). | Unhandled: Add 3 unrest. The governor loses 2 legitimacy. No Levy tax in this province next round. | sociopolitical |
| Informers at Work | Sociopolitical · Severity II | S21 | Where: Any province | The courts fill with charges of treason, and half of them are true. | Handled: Pay 6 money (a few accusers silenced, a few accused released). | Unhandled: The governor loses 3 legitimacy. Every player with an estate in the province loses 1 legitimacy. Add 1 unrest. | sociopolitical |
| Zealots on the Roads | Sociopolitical · Severity II | S22 | Where: Any province | Wandering bands of fanatics beat landlords and burn their ledgers. | Handled: Pay 6 money (rewards, an amnesty), or Army option (Size 3+). | Unhandled: Add 2 unrest. Two estates Disrupted at the next Production and one Ruined. | sociopolitical |
| The Dead Emperor Lives | Sociopolitical · Severity I | S23 | Where: Any province | A pretender claims to be the emperor who died, and the crowds believe him. | Handled: Pay 4 money (the impostor exposed, or bought). | Unhandled: Add 2 unrest. The governor loses 2 legitimacy. One estate Disrupted. | sociopolitical |
| The Hippodrome Massacre | Sociopolitical · Severity III | S24 | Where: Any province | The troops are loosed on the crowd, and the bishops will not forgive it. | Handled: Pay 8 money (public penance, restitution to the families). | Unhandled: Add 4 unrest. The governor loses 4 legitimacy. Two city cubes in the province are removed. | sociopolitical |
