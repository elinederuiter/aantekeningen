# Vragen aan Tjeerd

- Ik heb gelezen wat markdown inhoudt. Je gaf mee als tip om dit te gebruiken in Atom. Ik heb Atom gedownload, maar ik weet niet goed hoe ik hier markdown in kan toepassen.
- wat is een frame? Waarschijnlijk gaat dit over de refresh rate. Hoe vaak het scherm opnieuw ververst wordt. Iedere keer dat het scherm opnieuw opgezet wordt.
- wat is een void. Je geeft niks terug.

### 24-12-20
- Wat is de staging area ook al weer?

  In de staging area zet je files neer welke in de volgende sessie gecommit moeten worden. Als je meerdere commits achter elkaar wil doen, dan kun je deze in de staging area zetten. Het is een soort wachtruimte voor de files die gecommited gaan worden. De files hebben een relatie met elkaar en vormen samen een geheel. Je wil zo vaak mogelijk commiten. Je kan beter vaker kleine commits doen dan dat je 1 hele grote commit doet. Dit heeft ermee te maken dat als je een fout maakt ergens, dan kun je deze makkelijker vinden. Een kleine hoeveelheid files is dan gerelateerd hieraan. Het is ook vooral om overzicht te kunnen houden.
- ik heb de naam gewijzigd van een bestand en nu krijgen ik in de status een error te zien. Hoe los ik dit op?

  Ik had de naam gewijzigd via de editor (Atom). De verwijderde files worden niet toegevoegd in de staging area. Als de naam gewijzigd wordt, dan krijgt deze de status "deleted" en dan vindt de terminal deze niet meer en dan komt deze dus niet via `git add *` in de staging area. Om dit op te lossen moet de file handmatig toegevoegd worden via `git add <filename>` (en dan de naam van de verwijdere file, dus bijvoorbeeld de naam waar de spelfout in zit).

```
MacBook-Air-van-Eline:aantekeningen elinederuiter$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	new file:   aantekeningen-mac-os-commands.md
	modified:   aantekningen-mac-os-commands.md

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	deleted:    aantekningen-mac-os-commands.md

MacBook-Air-van-Eline:aantekeningen elinederuiter$ git add aantekningen-mac-os-commands.md
```
