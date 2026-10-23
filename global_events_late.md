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
  - id: flavor
    x: 25
    y: 255
    width: 700
    height: 100
    fontFamily: Arial
    fontSize: 26
    color: '#BBBBBB'
    horizontalAlignment: Left
    verticalAlignment: Center
    wordWrap: true
  - id: effect
    x: 25
    y: 370
    width: 700
    height: 600
    fontFamily: Arial
    fontSize: 34
    color: '#EEEEEE'
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

# Decline and Fall: Global Event Cards, Late (c. AD 430-500)

8 event cards for the card generator. Events have no Handled or Unhandled side: the effect simply happens, to everyone, as soon as the card is drawn. Some are historical and some are generic (harvests, plague, weather).

Conventions: "Every province" effects apply in each province at once. "Weakest Roman garrison" means the frontier province with the lowest total Roman army Size (ties: the emperor chooses). Dates in the card type are for reference and can be dropped.

Run: `dotnet run --project DeclineAndFallCardGenerator -- global_events_late.md`

## Event Cards

| card_name | card_type | card_id | flavor | effect | icon |
| --- | --- | --- | --- | --- | --- |
| The Granary Lost | Event · AD 439 | GL01 | Carthage falls without a siege, and the African grain fleets sail no more for Rome. | Effect: Every player pays 3 grain at Upkeep. Every estate is Disrupted (grain) for the next two Productions. | economic |
| Attila Crosses the Rhine | Event · AD 451 | GL02 | Huns, Gepids and Ostrogoths sweep into Gaul, and the old enemies of Rome must unite to stop them. | Effect: Place Barbarians (Size 6) in the frontier province with the weakest Roman garrison. Two city cubes there are removed. | military |
| Aetius Murdered | Event · AD 454 | GL03 | The emperor stabs his only general with his own hand, and the army remembers who it served. | Effect: Every Roman army chit loses 2 Size. Every governor loses 1 legitimacy. | sociopolitical |
| The Sack of Rome | Event · AD 455 | GL04 | Vandal ships come up the Tiber, and for fourteen days the city is stripped to the rafters. | Effect: Remove 3 city cubes from Italia. The imperial treasury loses 4 money. Add 3 unrest in Italia. | military |
| Hard Winter | Event · Weather | GL05 | The rivers freeze, the roads close and the fodder runs out. | Effect: Every estate is Disrupted (grain) at the next Production. Armies cannot Move or Attack in the next Military phase. | economic |
| Prices Climb | Event · Economy | GL06 | A day’s wage buys last year’s bread, and the merchants demand payment in gold. | Effect: Every estate yields 1 less money (minimum 0) for the next two Productions. Every player pays 2 money at Upkeep. | economic |
| The Armada Fails | Event · AD 468 | GL07 | Eleven hundred ships and a king’s ransom in gold burn in a single night of fireships. | Effect: Every player pays 3 money at Upkeep. Place Barbarians (Size 4) in the coastal province with the weakest Roman garrison. | military |
| The Emperor Deposed | Event · AD 476 | GL08 | The boy emperor is pensioned off, and the regalia are sent east with a polite note. | Effect: Every governor loses 2 legitimacy. Add 1 unrest in every province. | sociopolitical |
