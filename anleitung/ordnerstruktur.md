# Ordnerstruktur
Die folgende Abbildung stellt die grundlegende Struktur eines MAtP konformen Moduls dar. Weitere Ordner wie z.B. Anleitungen können bei bedarf hinzugefügt werden. Im weiteren Verlauf dieses Dokuments wird auf die einzelnen Ordner in der Unix Pfad Schreibweise referenziert (z.B. ./icons/gefaerten):
```
[module] 
|  module.json
|
+--icons
|    |
|    +--bestien
|    |  |
|    |  +avatar
|    |  |
|    |  +token
|    |
|    +--charaktaere
|    |  |
|    |  +avatar
|    |  |
|    |  +token
|    |
|    +--effekte
|    |
|    +--gefaerten
|    |  |
|    |  +avatar
|    |  |
|    |  +token
|    |
|    +--gegenstaende
|    |
|    +--karten
|    |
|    +--notizbuecher
|
+--packs
|    
+--token
    |
    +--neutral
    |
    +--feindlich

```


### ./icons
Hauptverzeichnis für alle Bilder und Karten des Modules. Um eine leichtere Suche zu ermöglichen wird folgende Unterteilung getroffen:
 - **./icons/bestien**
 
   Beinhaltet alle nicht humanoiden Wesen, wie Monster, Geister, Daemonen ...
   
 - **./icons/charaktaere** 
 
   Beinhaltet die Bilder für namentlich bekannte Charaktäre (unterteilt in den Ordnern avatar für das Charakterbogen Portrai und token für das Battlemap Token). Zu dieser Kategorie gehören, Spieler-Charaktäre (SCs), Gruppen-Nicht-Spieler-Charatäre (GNSCs), Gefährten (FNSCs) sowie ausgearbeitete (namentlich bekannte) NSCs. 
   
 - **./icons/effekte**
 - **./icons/gefaerten**
 - **./icons/gegenstaende**
 - **./icons/karten**
 - **./icons/notizbuecher**
 
### ./packs
Verzeichnis für die .db Komplendien. Diese sind mindestens entsprechenden den *VTT Typen* Akteure, Items, Szenen, Journale, Macros, Tische und Playlists zu unterteilen.


### ./token
Struktur 
Verzeichnis für weitere Token die keinem Charakter zugeordnet sind. 
Je Token sind zwei verschiedene Versionen zu erstellen und in das entsprechende Unterverzeichnis abzulegen:

**Nicht-Spieler Charaktäre** verwenden den unten abgebildeten Rahmenstil in der Silber-weissen Farbe

![](https://github.com/derkaktus/DSA5/blob/751146ac1f6e6c5a5d968571e3269b191e2e7052/Token/fifthed_border_medium_greyscale.png)

**Feindliche Nicht-Spieler Charaktäre** Verwenden den Rahmenstil in der Farbe **#8E0909**

Für Tokens die PCs, NCs oder Gefährten zugeordnet sind, siehe icons. 
