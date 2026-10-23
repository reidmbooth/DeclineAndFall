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

# Decline and Fall: Global Law Cards, Late (c. AD 430-500)

6 law cards for the card generator. Laws are put to the vote in the horse-trading phase. If the law carries, resolve the For side. If it fails, resolve the Against side. Both sides have a cost, so there is always something to trade over.

Conventions: "Every province" effects apply in each province at once. "Weakest Roman garrison" means the frontier province with the lowest total Roman army Size (ties: the emperor chooses). Dates in the card type are for reference and can be dropped.

Run: `dotnet run --project DeclineAndFallCardGenerator -- global_laws_late.md`

## Law Cards

| card_name | card_type | card_id | flavor | for | against | icon |
| --- | --- | --- | --- | --- | --- | --- |
| The Theodosian Code | Law · AD 438 | LL01 | A century of edicts is gathered into sixteen books, and no judge may plead ignorance. | For: The code is promulgated. Every player pays 2 money (copyists, a commission of jurists). Every governor gains 1 legitimacy. | Against: The tangle of edicts stands and every court is a lottery. Add 1 unrest in every province. | sociopolitical |
| The Law of Hospitality | Law · AD 443 | LL02 | The newcomers are quartered on Roman estates and take a third of the land. | For: Federates are quartered on the estates. Every player with an estate loses 1 estate cube (their choice). The emperor takes a Barbarians chit (Size 3) as foederati under their control (upkeep applies). | Against: The federates are unpaid and unsettled. Place Barbarians (Size 4) in the frontier province with the weakest Roman garrison. | military |
| Tribute to Attila | Treaty · AD 447 | LL03 | Attila names his price in gold by weight, and the treasury must find it in the provinces. | For: The gold is paid. Every player pays 3 money. No Barbarians chit larger than Size 3 may be placed next round. | Against: The embassy is sent away. Place Barbarians (Size 5) in the frontier province with the weakest Roman garrison. Add 1 unrest in every province. | economic |
| The Council of Chalcedon | Council · AD 451 | LL04 | Six hundred bishops gather to decide whether Christ has two natures or one. | For: The two-natures creed is imposed. Every governor gains 1 legitimacy. Add 2 unrest in two provinces of the emperor’s choice (riots in the monasteries). | Against: The council ends in deadlock. Every governor loses 1 legitimacy. Add 1 unrest in every province. | sociopolitical |
| Majorian’s Reforms | Law · AD 458 | LL05 | A new emperor attacks the corrupt tax-collectors and forbids the pulling down of ancient buildings for stone. | For: Arrears are cancelled and the collectors punished. Every governor gains 1 legitimacy. The imperial treasury loses 3 money. | Against: The collectors carry on. Every governor loses 1 legitimacy. Every player with an estate gains 2 money. | economic |
| The Abolition of the Chrysargyron | Law · AD 498 | LL06 | The hated tax on every craftsman and trader is abolished, and the tax records burn in the streets. | For: The tax is abolished. Remove 1 unrest from every province. The imperial treasury loses 4 money. | Against: The tax stays. The imperial treasury gains 3 money. Add 1 unrest in every province. | economic |
