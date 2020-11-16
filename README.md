# A more peaceful galaxy mod

## Mod description
This mod changes the spawn mechanics for AI empires to make the likelihood of "aggressive" (see technical description) AI spawning a lot lower than in vanilla.
This is intended to enable two different styles of gameplay:

1. "I just want to nation build".
My personal use case, this is for those players who want to just build a big empire and not have to fight wars to maintain it. A much more peaceful playstyle. Note; this only lowers the ratio of "aggressive" to "non-aggressive" AI empires, it does NOT remove them entirely from the game.

1. "I want to crush the entire galaxy under my boot".
As there are much fewer "aggressive" AI, you will have less competition to take over the galaxy. Maybe mix with a "no federations allowed" mod for an even easier play through.


## Technical description

Paradox assigns each ethic a random weight that influences how the AI empires choose their ethics, with higher weights meaning that an ethic is more likely to be chosen. Following is a table of what the random weighting was, and what it has been changed to in the mod. Ethics that have not been modified - like egalitarian - are left out of the table.

Ethic name | Vanilla random weighting | Modified random weighting | Modifier ratio
--- | --- | --- | ---
Fanatic Xenophobe | 150 | 66 | x 0.44
Xenophobe | 100 | 33 | x 0.33
Fanatic Xenophile | 100 | 150 | x 1.50
Xenophile | 66 | 100 | x 1.52
Fanatic Militarist | 250 | 100 | x 0.40
Militarist | 150 | 66 | x 0.44
Fantic Pacifist | 33 | 100 | x 3.03
Pacifist | 66 | 150 | x 2.27
