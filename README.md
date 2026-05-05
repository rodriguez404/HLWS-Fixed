# Hero Line Wars Starlight [Fixed]

<h2>Description:</h2>
Originally created by Tya (and discontinued later), this [Fixed] version was made to improve balance and fix bugs (included major, game-breaking ones) for better user experience.

I did not intend to create "new" HLWS, but rather polish the existing one, making it "how it was supposed to be" if original author continued developing it for little more.

All rights go to original creator, I do not own anything.

I am not legally and morally responsible for other people's actions if someone will decide to claim authorship for this project.

<h2>Usage:</h2>
<h3>Mods</h3>
"Mods" folder should be put in your SC2 Installation folder: "StarCraft II/"

![](https://raw.githubusercontent.com/rodriguez404/HLWS-Fixed/refs/heads/main/README_assets/Mods_placement.png)

Some dependencies contain just textures, while others contain abilities and such stuff.

Dependencies are saved as .SC2Mod Components folder. You can't open it directly via double-click, but can open in Editor:

> File > Open... > [navigate to folder]

Some dependencies rely on other dependencies. When updating any dependency, it is recommended to update all related dependencies.
Because of that, there's so-called "Dependency chain", in which order you should update your Mods (if change ones):
1. Starlight UI, Starlight Imports Legacy (independent on anything)
2. Starlight Assets Old1
3. Starlight Assets legacy open1
4. Starlight Abilities
5. War3 (last to update if anything changes in dependencies)

Thus, if you want to update some dependency, it is recommended to update all subsequent dependencies in dependency chain. 
> For example, if you update "Starlight Abilities", you should then also update "War3".

<h3>Map</h3>
Map is saved as .SC2Map Components folder. You can't open it directly via double-click, but can open in Editor:

> File > Open... > [navigate to folder]

<h3>Contribution</h3>

To contribute to project, you must `Fork` it first. From that point, you will work on your own version of this repository. After doing some `commits` in your repo, you can then either:
- create `pull requests` in this repository (which will be reviewed, and either accepted & merged, or declined),
- or keep commiting into your own repo and eventually release "HLWS Fixed v2", lol.

The project is open to community, and bug fixes / performance optimisations (that dont alter the gameplay) are very welcome.
However, balance changes will be debated, or, possibly, declined without explanation.