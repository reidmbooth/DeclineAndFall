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

# Decline and Fall: Global Law Cards, Early (c. AD 300-360)

7 law cards for the card generator. Laws are put to the vote in the horse-trading phase. If the law carries, resolve the For side. If it fails, resolve the Against side. Both sides have a cost, so there is always something to trade over.

Conventions: "Every province" effects apply in each province at once. "Weakest Roman garrison" means the frontier province with the lowest total Roman army Size (ties: the emperor chooses). Dates in the card type are for reference and can be dropped.

Run: `dotnet run --project DeclineAndFallCardGenerator -- global_laws_early.md`

## Law Cards

| card_name | card_type | card_id | flavor | for | against | icon |
| --- | --- | --- | --- | --- | --- | --- |
| The Great Census | Law · c. AD 300 | LE01 | Surveyors count every head and measure every field, and the old exemptions are void. | For: The census is taken. The imperial treasury gains 4 money. Every player with an estate pays 2 money at Upkeep. Add 1 unrest in every province. | Against: The exemptions stand. The imperial treasury loses 3 money to arrears. Every player with an estate gains 1 legitimacy. | economic |
| Edicts Against the Christians | Law · AD 303 | LE02 | The edicts order the churches razed, the scriptures burned and the clergy chained. | For: Church property is confiscated. Every player gains 2 money. Add 1 unrest in every province. | Against: The edicts are quietly shelved. Every governor loses 1 legitimacy (the hardliners at court are furious). | sociopolitical |
| Reform of the Coinage | Law · c. AD 310 | LE03 | Gold holds its weight, but the bronze the poor are paid in is worth less each year. | For: A sound gold coin is struck. Every player pays 2 money for bullion. Remove 1 unrest from every province. | Against: The bronze is debased again. Every estate yields 1 less money (minimum 0) for the next two Productions. Add 1 unrest in every province. | economic |
| The Edict of Milan | Law · AD 313 | LE04 | The churches are promised their confiscated property back, and the buyers hold the deeds. | For: Restitution is made. Every player with an estate pays 2 money. Remove 1 unrest from every province. | Against: The edict is not enforced. Every player with an estate gains 2 money. Add 1 unrest in every province. | sociopolitical |
| The Council of Nicaea | Council · AD 325 | LE05 | Bishops from every province converge on one city to decide what the Son is to the Father. | For: A single creed is imposed. Every player pays 2 money (the imperial post, the synod’s costs). Every governor gains 1 legitimacy. | Against: No creed is agreed. Add 1 unrest in every province. Every governor loses 1 legitimacy. | sociopolitical |
| Chains of Hereditary Service | Law · AD 332 | LE06 | Tenants are bound to the land, councilmen to the council, and a soldier’s son to the army. | For: The ranks are frozen. Every player with an estate pays 2 grain (registers and enforcement). Remove 1 unrest from every province. | Against: Tenants and councilmen flee. Add 1 unrest in every province. No Levy tax in any province next round. | sociopolitical |
| Treaty with the Goths | Treaty · AD 332 | LE07 | Constantine’s army has beaten them, and a treaty of friendship will keep them quiet. | For: A yearly subsidy is paid. The imperial treasury loses 3 money. The emperor takes a Barbarians chit (Size 2) as foederati under their control (upkeep applies). | Against: The Goths raid across the river. Place Barbarians (Size 4) in the frontier province with the weakest Roman garrison. | military |
