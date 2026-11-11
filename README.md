# Linux für die Couch

Dieses Repository gehört zum Artikel "Linux für die Couch: Mit Plasma Bigscreen Streaming und Gaming vereinen", der bei heise+ und im c't magazin erschienen ist. Das Skript atv-launch startet eine Android-TV-App in Waydroid, das Skript
atv-add legt eine Kachel für Plasma Bigscreen an.


<img width="1920" height="1200" alt="plasma_bigscreen_final" src="https://github.com/user-attachments/assets/d6c2b47c-cbf9-48a8-86b3-3e594c4b3e53" />


Speichern Sie beide Skripte im Verzeichnis ~/.local/bin und machen Sie dann mit `chmod +x ~/.local/bin/atv-launch ~/.local/bin/atv-add` ausführbar.

Ber Befehl `waydroid app list` zeigt die Paketnamen aller installierten Android-Apps an, beispielsweise atv-add de.swr.avp.ard.tv für die ARD Mediathek.

Mit `~/.local/bin/atv-add de.swr.avp.ard.tv "ARD Mediathek"` legen Sie die entsprechende Kachel für Plasma Bigscreen an.
