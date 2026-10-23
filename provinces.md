---
backgroundImagePath: Backgrounds/Governorship.png
textFields:
  - id: card_name
    x: 260
    y: 20
    width: 470
    height: 110
    fontFamily: Arial
    fontSize: 44
    color: '#FFFFFF'
    horizontalAlignment: Center
    verticalAlignment: Center
    wordWrap: false
  - id: card_type
    x: 260
    y: 140
    width: 470
    height: 50
    fontFamily: Arial
    fontSize: 22
    color: '#CCCCCC'
    horizontalAlignment: Center
    verticalAlignment: Center
    wordWrap: false
  - id: slots
    x: 260
    y: 200
    width: 470
    height: 50
    fontFamily: Arial
    fontSize: 20
    color: '#EEEEEE'
    horizontalAlignment: Center
    verticalAlignment: Center
    wordWrap: false
  - id: description
    x: 25
    y: 270
    width: 700
    height: 360
    fontFamily: Arial
    fontSize: 24
    color: '#EEEEEE'
    horizontalAlignment: Left
    verticalAlignment: Top
    wordWrap: true
  - id: crisis_title
    x: 25
    y: 650
    width: 700
    height: 50
    fontFamily: Arial
    fontSize: 28
    color: '#FF0000'
    horizontalAlignment: Left
    verticalAlignment: Center
    wordWrap: false
  - id: crisis_text
    x: 25
    y: 710
    width: 700
    height: 300
    fontFamily: Arial
    fontSize: 22
    color: '#EEEEEE'
    horizontalAlignment: Left
    verticalAlignment: Top
    wordWrap: true
iconOverlays:
  - id: icon
    imagePath: ./icon.png
    x: 0
    y: 0
    width: 250
    height: 250
---

# Decline and Fall: Province (Governor) Cards

One card per province, 14 in all, taken from the Provinces table in the game design file. Each province starts with 9 neutral estate cards held with its governor card.

## How to use:
1. Replace `template.png` with your card background. The YAML assumes a 750 x 1050 image. Rescale the x, y, width, height, and fontSize values if yours differs.
2. Replace `icon.png` with your province icon. It sits in the reserved top-left 250 x 250 area, and the name, region, and slot text are placed to its right so nothing overlaps it.
3. Fill in the city count in the `slots` column once the board is designed. The design file leaves the number of city spots open.
4. Run: `dotnet run --project DeclineAndFallCardGenerator -- provinces.md`

## Province Cards

| card_name | card_type | slots | description | crisis_title | crisis_text | icon |
| --- | --- | --- | --- | --- | --- | --- |
| Britannia | Northwest | Estates: 9 Cities: __ | Far frontier, reached from the continent by sea. Remote, rich in tin and lead. Estate yield: 11 money, 10 grain, 16 materials. | Unrest (Crisis) Cubes | Each round a governor rolls 1d6 and adds the unrest cubes here. 1-2: nothing. 3-4: add 1 unrest cube. 5 or more: crisis card drawn. Lavish population removes cubes and Levy tax adds 1 (gain 3 money), both before the roll. | province |
| Gallia | West | Estates: 9 Cities: __ | Prosperous grain and wine region. Estate yield: 18 money, 18 grain, 9 materials. | Unrest (Crisis) Cubes | Each round a governor rolls 1d6 and adds the unrest cubes here. 1-2: nothing. 3-4: add 1 unrest cube. 5 or more: crisis card drawn. Lavish population removes cubes and Levy tax adds 1 (gain 3 money), both before the roll. | province |
| Hispania | West | Estates: 9 Cities: __ | Mineral-rich peninsula (copper, gold). Estate yield: 15 money, 14 grain, 10 materials. | Unrest (Crisis) Cubes | Each round a governor rolls 1d6 and adds the unrest cubes here. 1-2: nothing. 3-4: add 1 unrest cube. 5 or more: crisis card drawn. Lavish population removes cubes and Levy tax adds 1 (gain 3 money), both before the roll. | province |
| Italia | Italy | Estates: 9 Cities: __ | Heart of the empire. Contains Rome *(proposed: the city worth 2 legitimacy per cube)*. Estate yield: 17 money, 17 grain, 11 materials. | Unrest (Crisis) Cubes | Each round a governor rolls 1d6 and adds the unrest cubes here. 1-2: nothing. 3-4: add 1 unrest cube. 5 or more: crisis card drawn. Lavish population removes cubes and Levy tax adds 1 (gain 3 money), both before the roll. | province |
| Noricum | Alps and Danube | Estates: 9 Cities: __ | Alpine and Danube frontier territory, with iron and salt. Estate yield: 6 money, 6 grain, 18 materials. | Unrest (Crisis) Cubes | Each round a governor rolls 1d6 and adds the unrest cubes here. 1-2: nothing. 3-4: add 1 unrest cube. 5 or more: crisis card drawn. Lavish population removes cubes and Levy tax adds 1 (gain 3 money), both before the roll. | province |
| Dalmatia | Balkans | Estates: 9 Cities: __ | Adriatic coast and trade hub. Estate yield: 13 money, 10 grain, 11 materials. | Unrest (Crisis) Cubes | Each round a governor rolls 1d6 and adds the unrest cubes here. 1-2: nothing. 3-4: add 1 unrest cube. 5 or more: crisis card drawn. Lavish population removes cubes and Levy tax adds 1 (gain 3 money), both before the roll. | province |
| Macedonia | Balkans | Estates: 9 Cities: __ | Balkan crossroads, with gold, silver, and timber. Estate yield: 14 money, 10 grain, 11 materials. | Unrest (Crisis) Cubes | Each round a governor rolls 1d6 and adds the unrest cubes here. 1-2: nothing. 3-4: add 1 unrest cube. 5 or more: crisis card drawn. Lavish population removes cubes and Levy tax adds 1 (gain 3 money), both before the roll. | province |
| Thracia | Balkans | Estates: 9 Cities: __ | Danube frontier. Volatile. Estate yield: 12 money, 11 grain, 9 materials. | Unrest (Crisis) Cubes | Each round a governor rolls 1d6 and adds the unrest cubes here. 1-2: nothing. 3-4: add 1 unrest cube. 5 or more: crisis card drawn. Lavish population removes cubes and Levy tax adds 1 (gain 3 money), both before the roll. | province |
| Asia | Anatolia | Estates: 9 Cities: __ | Wealthy Anatolian province with luxury goods. Estate yield: 18 money, 8 grain, 16 materials. | Unrest (Crisis) Cubes | Each round a governor rolls 1d6 and adds the unrest cubes here. 1-2: nothing. 3-4: add 1 unrest cube. 5 or more: crisis card drawn. Lavish population removes cubes and Levy tax adds 1 (gain 3 money), both before the roll. | province |
| Syria | East | Estates: 9 Cities: __ | Eastern trading post at the end of the caravan routes. Estate yield: 21 money, 11 grain, 8 materials. | Unrest (Crisis) Cubes | Each round a governor rolls 1d6 and adds the unrest cubes here. 1-2: nothing. 3-4: add 1 unrest cube. 5 or more: crisis card drawn. Lavish population removes cubes and Levy tax adds 1 (gain 3 money), both before the roll. | province |
| Armenia | East | Estates: 9 Cities: __ | Frontier with the Sassanids. Volatile and strategic. Estate yield: 8 money, 11 grain, 10 materials. | Unrest (Crisis) Cubes | Each round a governor rolls 1d6 and adds the unrest cubes here. 1-2: nothing. 3-4: add 1 unrest cube. 5 or more: crisis card drawn. Lavish population removes cubes and Levy tax adds 1 (gain 3 money), both before the roll. | province |
| Egypt | Eastern Mediterranean | Estates: 9 Cities: __ | Grain breadbasket, wealthy, and a trade hub. Estate yield: 14 money, 21 grain, 8 materials. | Unrest (Crisis) Cubes | Each round a governor rolls 1d6 and adds the unrest cubes here. 1-2: nothing. 3-4: add 1 unrest cube. 5 or more: crisis card drawn. Lavish population removes cubes and Levy tax adds 1 (gain 3 money), both before the roll. | province |
| Africa | North Africa | Estates: 9 Cities: __ | North African grain and luxury trade. Estate yield: 17 money, 16 grain, 6 materials. | Unrest (Crisis) Cubes | Each round a governor rolls 1d6 and adds the unrest cubes here. 1-2: nothing. 3-4: add 1 unrest cube. 5 or more: crisis card drawn. Lavish population removes cubes and Levy tax adds 1 (gain 3 money), both before the roll. | province |
| Mauretania | North Africa | Estates: 9 Cities: __ | Remote western frontier. Estate yield: 10 money, 10 grain, 6 materials. | Unrest (Crisis) Cubes | Each round a governor rolls 1d6 and adds the unrest cubes here. 1-2: nothing. 3-4: add 1 unrest cube. 5 or more: crisis card drawn. Lavish population removes cubes and Levy tax adds 1 (gain 3 money), both before the roll. | province |
