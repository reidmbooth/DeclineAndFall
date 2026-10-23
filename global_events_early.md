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

# Decline and Fall: Global Event Cards, Early (c. AD 300-360)

7 event cards for the card generator. Events have no Handled or Unhandled side: the effect simply happens, to everyone, as soon as the card is drawn. Some are historical and some are generic (harvests, plague, weather).

Conventions: "Every province" effects apply in each province at once. "Weakest Roman garrison" means the frontier province with the lowest total Roman army Size (ties: the emperor chooses). Dates in the card type are for reference and can be dropped.

Run: `dotnet run --project DeclineAndFallCardGenerator -- global_events_early.md`

## Event Cards

| card_name | card_type | card_id | flavor | effect | icon |
| --- | --- | --- | --- | --- | --- |
| The Tetrarchy Collapses | Event · AD 306 | GE01 | Four emperors, a dozen claimants, and every legion told that the purple is for sale. | Effect: Every Roman army chit loses 1 Size. Add 1 unrest in every province. | military |
| Poor Harvest | Event · Harvest | GE02 | A wet spring and a dry summer. | Effect: Every estate is Disrupted (grain) at the next Production. Add 1 unrest in every province. | economic |
| The New Rome | Event · AD 330 | GE03 | A new capital rises on the Bosporus, and the grain ships of Egypt turn east. | Effect: Every estate in Italia is Disrupted (grain) for the next two Productions. Add 2 unrest in Italia. | economic |
| Shapur Besieges Nisibis | Event · AD 338 | GE04 | The river is dammed, the wall falls, and the city rebuilds it by morning. | Effect: Place Barbarians (Size 4) in the frontier province with the weakest Roman garrison. Add 1 unrest there. | military |
| The Bloodbath at Mursa | Event · AD 351 | GE05 | Two Roman armies butcher each other, and the frontier pays the bill for a generation. | Effect: Every Roman army chit loses 2 Size. Every governor loses 1 legitimacy. | military |
| The Rhine Frontier Falls | Event · AD 355 | GE06 | Franks and Alamanni take forty towns on the Rhine while the emperors fight each other. | Effect: Place Barbarians (Size 5) in the frontier province with the weakest Roman garrison. Two city cubes there are removed. | military |
| Plague | Event · Pestilence | GE07 | Pestilence follows the grain ships up every river. | Effect: Every player loses 2 cubes of their choice (estates, cities or armies). Add 1 unrest in every province. | economic |
