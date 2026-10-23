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
  - id: for
    x: 25
    y: 370
    width: 700
    height: 290
    fontFamily: Arial
    fontSize: 30
    color: '#BFE3FF'
    horizontalAlignment: Left
    verticalAlignment: Top
    wordWrap: true
  - id: against
    x: 25
    y: 670
    width: 700
    height: 310
    fontFamily: Arial
    fontSize: 30
    color: '#FFD39A'
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

# Decline and Fall: Global Law Cards, Middle (c. AD 360-430)

7 law cards for the card generator. Laws are put to the vote in the horse-trading phase. If the law carries, resolve the For side. If it fails, resolve the Against side. Both sides have a cost, so there is always something to trade over.

Conventions: "Every province" effects apply in each province at once. "Weakest Roman garrison" means the frontier province with the lowest total Roman army Size (ties: the emperor chooses). Dates in the card type are for reference and can be dropped.

Run: `dotnet run --project DeclineAndFallCardGenerator -- global_laws_middle.md`

## Law Cards

| card_name | card_type | card_id | flavor | for | against | icon |
| --- | --- | --- | --- | --- | --- | --- |
| The Treaty of Jovian | Treaty · AD 363 | LM01 | The emperor is dead in the desert, and his successor will sign anything to get the army home. | For: The peace is signed. Remove one city cube (surrendered) from the frontier province with the weakest Roman garrison. Every governor loses 1 legitimacy. | Against: The retreat becomes a rout. Each Roman army chit loses 2 Size. Place Barbarians (Size 3) in the frontier province with the weakest Roman garrison. | military |
| The Patronage Laws | Law · AD 368 | LM02 | Great men shelter whole villages from the tax-collector, and the emperor forbids it. | For: Patronage is forbidden. The imperial treasury gains 4 money. No Patronage next round. Every player with an estate loses 1 legitimacy. | Against: Patronage flourishes. Every player with an estate gains 2 money. The imperial treasury loses 4 money. Add 1 unrest in every province. | sociopolitical |
| Gold for Recruits | Law · AD 375 | LM03 | Landowners offer coin in place of sons, and the recruiting officers find it easier to count. | For: Gold replaces men. The imperial treasury gains 4 money. No Roman army chit may gain Size next round. | Against: The levy of men stands. Every player with an estate pays 2 grain at Upkeep. Add 1 unrest in every province. | economic |
| Orthodoxy by Edict | Law · AD 380 | LM04 | All peoples are commanded to hold one creed, and every other congregation is declared a conspiracy. | For: One creed is enforced. Every governor gains 1 legitimacy. Add 1 unrest in every province. | Against: Rival creeds stand. Every governor loses 1 legitimacy (the bishops are furious). | sociopolitical |
| The Gothic Settlement | Treaty · AD 382 | LM05 | The emperor cannot beat the Goths, so he offers them land to live on and swords to carry. | For: The Goths are settled as foederati. Every player with an estate pays 2 grain (rations). The emperor takes a Barbarians chit (Size 3) under their control (upkeep applies). | Against: The war goes on. Place Barbarians (Size 5) in the frontier province with the weakest Roman garrison. Add 2 unrest there. | military |
| The Temples Closed | Law · AD 391 | LM06 | Monks pull down the great temple, and the emperor forbids sacrifice under any name. | For: The temples are closed and their treasures seized. Every player gains 2 materials. Add 1 unrest in every province. | Against: The old rites go on. Every governor loses 1 legitimacy (the bishops are furious). | sociopolitical |
| The Ransom of Rome | Treaty · AD 408 | LM07 | The Goths camp at the walls and name their price in gold, silver, silk and pepper by the pound. | For: The ransom is paid. Every player pays 2 money or loses 1 city cube. | Against: The senate refuses. Place Barbarians (Size 4) in Italia. Two city cubes in Italia are removed. Add 2 unrest in Italia. | military |
