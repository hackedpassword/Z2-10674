Temporary fork of Z2 to dx [#10674](https://github.com/yairm210/Unciv/issues/10674). 

The process to split on a specific commit was codified, available as Win or Nix scripts `clone_repo` currently posted at https://github.com/hackedpassword/Unciv-Assets


# Z2 : Zelda 2 for Unciv

Looking for some NES nostalgia? With a Civ V twist? You’ve come to the right place.

![](https://raw.githubusercontent.com/hackedpassword/Z2/main/preview.png)

I’m a huge fan of the original Zelda 2, up to and including no-lives-lost vanila game completion. I also have a [less than 7 minute completion speedrun time](https://youtu.be/uHrhG_AkObw) which you may find entertaining. ;) 

## Z2 achievements:

1. For the first time in Unciv history, bridge tiles can be placed. This is accomplished with [Hybrid Tile Tech](HybridTileTech.md), invented here, and now [mentioned in Unciv's code](https://github.com/yairm210/Unciv/blob/11108112b513da41fe80875c01332650455f1196/core/src/com/unciv/models/ruleset/validation/RulesetValidator.kt#L352).
2. Thanks to hybrid tiles, three specific Zelda 2 gameplay elements have been preserved: raft crossing, boot water walking, and the bridge to Maze Island.
3. Unciv modder/mappers are going to have a field day tearing apart Z2! Have at it! Share what you learned, this is a huge opportunity!

Feedback: [Issues](https://github.com/hackedpassword/Z2/issues) (dev-related) and [Discussions](https://github.com/hackedpassword/Z2/discussions) (game-related) at the top of the page.

## Before:

![](https://raw.githubusercontent.com/hackedpassword/Unciv-Assets/main/Images/Z2/Z2_before.png)

## After:
![](https://raw.githubusercontent.com/hackedpassword/Unciv-Assets/main/Images/Z2/Screenshot_20231006_182203.jpg)

Take a closer look at the above and you'll see the **hidden water paths** using [Force](https://github.com/hackedpassword/Z2/blob/a28fc4ceebfa023fb7481dfcedd35cacc9fe58d3/jsons/Terrains.json#L282) (a TerrainFeature) via [customized ocean Hybrid tiles](https://github.com/hackedpassword/Z2/blob/a28fc4ceebfa023fb7481dfcedd35cacc9fe58d3/jsons/Terrains.json#L791) that makes the special features of the Hyrule overworld map possible! 

[Version notes](https://github.com/hackedpassword/Z2/version_notes.md)

## Player notes 

Z2 is essentially in beta. While in active development, expect anything could change! 

## Modder notes

Feel free to review/reuse the json’s. There's tons of commentary, especially towards learning what Unciv can/can't do. 

[Unciv Z2 discord](https://discord.com/channels/586194543280390151/1138883296835682324)


## Credits are due!

- [The Spriters Resource]( https://www.spriters-resource.com/) for fantastic sprite sheets.
- Included are credits to the sprite rippers: [Mister Mike](https://www.spriters-resource.com/submitter/MisterMike/), Obreck, [Bruice Juice](https://retrogamezone.co.uk/zelda2.htm), [Rick N. Bruns](https://www.pinterest.com/snesmaster/) (that partial original map above) - huge thanks for creating that map!
- Ninendo including my NES and my copy of Zelda 2.
- Yairm210 for Unciv and Unciv assets and amazing documentation.
- SomeTroglodyte for his massive contributions including debugging complex Z2 issues.
- SeventhM for all the assistance he's contributed in straightening out my mod glitches. 
- [A1y0sh4](https://github.com/A1y0sh4/The-Great-Unciv-Rework) and [Indonesian Gentleman](https://github.com/carriontrooper/Alpha-Frontier) for the relentless references I made to understand Unciv modding via their mods.
