# PatD_Foundry
Slowly building functional character sheets for Panic at the Dojo using the Custom System Builder in Foundry.

Using the templates:
These templates are made using the Custom System Builder v3.2.1 system in Foundry v11.315. Each .json file will need to be imported (presently there is only one), and if you want your players to be able to create their own characters, you need to go to "Configure Setttings", select "Custom System Builder" on the left side of the menu, and scroll down to "Minimum Role to reload a sheet". This will allow your players to select which template they want to use when making their characters.

Known issues:
- When you first load the template onto a character, there might be some errors on the sheet and you cannot select an archetype. This can be remedied by selecting a Build or a Cinematic Weight. Doing so should refresh things and then permit you to select and archetype.
- Style Unique Action Costs are not pulling in for all stances. Not sure why, but will be working on them.
- Leveling up to level 9 or 10 breaks the sheet. The console throws an error stating "expected identifier '$' SyntaxError: Unexpected identifier '$'" Once that happens, the sheet is broken even if you reload the template to it. The error message does not give more specifics as to where that errant $ is, and there are a lot of them so there is some digging required.

Things to do:
- Implement the drop downs for pulling in Supers and the relavent Super information.
- Implement the Forms specifica information on the stances.
- Implement the Style Unique Action list for when Focused Phantom is selected.
- Implement the Elder Style and Frantic Phantom list of all Unique Actions.
- Fill out the dynamic table that will track stance names, styles, and forms.
- Implement the level 10 multi-stance tab, which will pull from the above table.
- Finish updating information based on the Errata
- Clean up some typos (there are some tiered action descriptions that still have the costs rather than T1, T2, etc).
- Modify the Focused Fighter Template to make Fusion Fighter, Frantic Fighter, Stooges, Warrior, and Boss templates.

Long off things to do: add the expansion stuff when that comes out.
