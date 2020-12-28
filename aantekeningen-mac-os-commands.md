# Aantekeningen Mac OS-X Commands



## Basis commands

`mkdir` git = make directory git   
`rmdir` git = remove directory git  
`cd ..` = dan ga je vanaf je huidige directory 1 omhoog. Je moet het zien als een boomstructuur.  
`cd ~` = dat is altijd de home directory van de ingelogde gebruiker.  
`cd` = change directory, hiermee geef je aan naar welke directory je wilt.  
`touch` = hiermee maak je een leeg nieuw bestand aan.  
`echo`= hiermee echo je de tekst die daar achteraan komt naar je terminal of naar een bestand    
drwx staat voor: directory, read write en execute. Dit zijn 3 groepjes.  
`history` = hiermee kun je de eerder gebruikte commando's opvragen.  

Verschillende prompts

De prompt laat zien welke type gebruiker ingelogd moet zijn omdat type command uit te kunnen voeren.

`$> ` standard gebruiker  
`#> ` administrator gebruiker

## Markdown tips
- Command of stukje code '`' tussen back quotes En één extra om Atom niet in de war te maken '`'
- Heel block text 3 back quotes '```' aan begin en aan het einde '```'
- [GitHub Guide Markdown](https://guides.github.com/features/mastering-markdown/)



## Git Commands

https://bitbucket.org/ Dit is bedoeld voor een prive account voor git repositories.
github

`git init` = hiermee maak je een git repository aan  
`git add *` = files worden in de staging area gezet. * of naam van een file. Sterretje betekent hier alle files.  
`git status` = wat de stand van zaken is.  
`git commit -m "message"` = Hiermee geeft de message weer welke wijzigen er zijn in de files die we willen committen.  
`git push` = Als we deze wijzigingen ook op de remote git repository willen zien, dan pushen we ze daarnaar toe met deze command  
`git diff` = geeft de wijzingen weer.   
