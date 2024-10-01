# Einführing

## Github einrichten
1. Github account mit der Schul-Email Adresse anlegt.
2. Respository `TG11-1` mit ´readme.md´ anlegen.
3. Einen neuen Ordner mit Stunden Nummer anlegen. Bsp. ´01-ein´
4. Eine neue Datei ´start.md´ anlegen.

## erste Markdown Befehle 
1. Eine Überschrift wird mit `# Ueberschrift` erzeugt. Die nächste Ebene wird mit ``## Ueberschrift2`` , ``###Ueberschrift3`` usw. erzeugt.


## Arbeitsablauf in Github
1. Eine neue **Datei/Ordner** erstellen
2. Die Quellcodeverwaltung aufrufen.
3. Alle geänderten Datein **stagen**. Alternativ kann im Terminal der Befehl ``git add *.*`` eingegeben werden.
D.h. alle Datein werden ab jetzt im lokalen Respository (nicht auf Github) verwaltet.
Einen Aussagekräftigen Text in das Feld über den commit `commit`- Button eingeben und die Schaltfläche commit drücken. Der Befehl im Terminal lautet: 

```bash 
git commit -m "Erstes Markdown File erstellt. `` 
```

5. Synchronisieren anklicken um die Datein auf das **Remote-Repository** auf **Github** hochzuladen. Der Terminal Befehl lautet: 

```bash
git remote add origin https://github.com/Humamimi/GitTest.git 
git push -u origin main 
```
