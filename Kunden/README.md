Routinen um Kunde.DBF-Aufgaben zu erledigen, benötigt [PSDBF.PS1](https://github.com/Delapro/PSDBF) und [DelaproInstall](https://github.com/Delapro/DelaproInstall)-Skripte!

Hat man die normalen DelaproInstall-Skripte geladen, kann man mit dem Befehl 

```Powershell
# Dot-Sourcing damit die Funktionen zur Verfügung stehen!
. Invoke-DelaproSammelsuriumDownloadAndInit Kunden\Kunden.PS1
```

die Automatisierungsskripte automatisch nachladen. Danach stehen einem die Funktionen zur Verfügung. Es muss allerdings das zu ladende Modul angegeben werden. 
