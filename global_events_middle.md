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

# Decline and Fall: Global Event Cards, Middle (c. AD 360-430)

7 event cards for the card generator. Events have no Handled or Unhandled side: the effect simply happens, to everyone, as soon as the card is drawn. Some are historical and some are generic (harvests, plague, weather).

Conventions: "Every province" effects apply in each province at once. "Weakest Roman garrison" means the frontier province with the lowest total Roman army Size (ties: the emperor chooses). Dates in the card type are for reference and can be dropped.

Run: `dotnet run --project DeclineAndFallCardGenerator -- global_events_middle.md`

## Event Cards

| card_name | card_type | card_id | flavor | effect | icon |
| --- | --- | --- | --- | --- | --- |
| Earthquake and Tidal Wave | Event · AD 365 | GM01 | The sea draws back from the harbors, and then it comes over the rooftops. | Effect: Every player loses 1 city cube in a coastal province. Add 1 unrest in every coastal province. | economic |
| The Barbarian Conspiracy | Event · AD 367 | GM02 | Picts, Scots, Saxons and Franks strike at once, and the frontier commanders are killed or captured. | Effect: Place Barbarians (Size 4) in each of the two frontier provinces with the weakest Roman garrisons. | military |
| The Coming of the Huns | Event · AD 375 | GM03 | A people nobody has met drives the Alans and Goths before it, and the river peoples begin to move. | Effect: Place Barbarians (Size 3) in each of the two frontier provinces with the weakest Roman garrisons. Add 1 unrest in every province. | military |
| Adrianople | Event · AD 378 | GM04 | The emperor will not wait for his nephew’s army, and two-thirds of the field force die in the heat. | Effect: Every Roman army chit loses 2 Size. Place Barbarians (Size 5) in the frontier province with the weakest Roman garrison. Every governor loses 1 legitimacy. | military |
| Bountiful Harvest | Event · Harvest | GM05 | The granaries are full for once, and the tax-collectors almost smile. | Effect: Every estate yields 1 more grain at the next Production. Remove 1 unrest from every province. | economic |
| The Rhine Frozen | Event · AD 406 | GM06 | On the last night of the year the river freezes, and Vandals, Alans and Suebi walk across. | Effect: Place Barbarians (Size 6) in the frontier province with the weakest Roman garrison, and Barbarians (Size 2) in each adjacent province. | military |
| The Gates Opened | Event · AD 410 | GM07 | Rome has stood unplundered for eight hundred years, and on the third night a gate is opened. | Effect: Remove 3 city cubes from Italia. Place Barbarians (Size 4) in Italia. Add 3 unrest in Italia. Every governor loses 1 legitimacy. | military |
