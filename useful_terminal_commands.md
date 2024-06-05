# Nützliche Terminalbefehle

## Verzeichnis- und Dateiverwaltung
- `ls`: Listet Dateien und Verzeichnisse auf.
- `cd [Verzeichnis]`: Wechselt das Verzeichnis.
- `pwd`: Zeigt das aktuelle Verzeichnis an.
- `touch [Dateiname]`: Erstellt eine neue Datei.
- `mkdir [Verzeichnisname]`: Erstellt ein neues Verzeichnis.
- `rm [Dateiname]`: Löscht eine Datei.
- `rm -r [Verzeichnisname]`: Löscht ein Verzeichnis und dessen Inhalt rekursiv.
- `cp [Quelle] [Ziel]`: Kopiert eine Datei oder ein Verzeichnis.
- `mv [Quelle] [Ziel]`: Verschiebt oder benennt eine Datei oder ein Verzeichnis um.
- `cat [Dateiname]`: Zeigt den Inhalt einer Datei an.
- `nano [Dateiname]`: Öffnet eine Datei im Nano-Editor.
- `vim [Dateiname]`: Öffnet eine Datei im Vim-Editor.
- `code [Dateiname]`: Öffnet eine Datei in Visual Studio Code (wenn installiert).
- `less [Dateiname]`: Zeigt den Inhalt einer Datei seitenweise an.
- `more [Dateiname]`: Zeigt den Inhalt einer Datei seitenweise an.

## Textverarbeitung
- `echo [Text]`: Gibt Text im Terminal aus. Zum Beispiel `echo "Hallo Welt"`.
- `echo [Text] > [Dateiname]`: Schreibt Text in eine Datei. Zum Beispiel `echo "Dies ist ein Beispieltext" > beispiel.txt`.
- `echo [Text] >> [Dateiname]`: Hängt Text an eine Datei an. Zum Beispiel `echo "Dieser Text wird angehängt" >> beispiel.txt`.
- `grep [Suchbegriff] [Dateiname]`: Durchsucht eine Datei nach einem bestimmten Text. Zum Beispiel `grep "Text" datei.txt`.

## Systeminformationen
- `uname -a`: Zeigt Informationen über das System an.
- `top`: Zeigt eine Echtzeitübersicht der Systemaktivität an.
- `htop`: Eine verbesserte Version von `top` (muss installiert sein).
- `df -h`: Zeigt Informationen über den freien Speicherplatz auf Dateisystemen an.
- `du -sh [Verzeichnis]`: Zeigt die Größe eines Verzeichnisses an.
- `free -h`: Zeigt den verfügbaren und verwendeten Speicher an.
- `uptime`: Zeigt an, wie lange das System bereits läuft.
- `who`: Zeigt an, wer derzeit am System angemeldet ist.
- `ps aux`: Zeigt eine Liste aller laufenden Prozesse an.

## Netzwerk
- `ping [Hostname oder IP-Adresse]`: Überprüft die Erreichbarkeit eines Hosts.
- `ifconfig`: Zeigt Netzwerkinterface-Konfigurationen an.
- `ip addr`: Zeigt IP-Adressen und Netzwerkschnittstellen an.
- `curl [URL]`: Ruft eine URL ab und zeigt den Inhalt an.
- `wget [URL]`: Lädt eine Datei von einer URL herunter.
- `ssh [Benutzer]@[Hostname]`: Verbindet sich per SSH mit einem entfernten Rechner.
- `scp [Quelle] [Ziel]`: Kopiert Dateien zwischen Hosts über SSH.

## Dateiberechtigungen und -eigenschaften
- `chmod [Modus] [Dateiname]`: Ändert die Dateiberechtigungen.
- `chown [Benutzer]:[Gruppe] [Dateiname]`: Ändert den Besitzer und die Gruppe einer Datei.
- `ls -l`: Zeigt detaillierte Informationen zu Dateien und Verzeichnissen an.
- `stat [Dateiname]`: Zeigt detaillierte Statusinformationen zu einer Datei an.

## Paketverwaltung (macOS Homebrew)
- `brew install [Paketname]`: Installiert ein Paket.
- `brew update`: Aktualisiert die Liste der verfügbaren Pakete.
- `brew upgrade`: Aktualisiert installierte Pakete.
- `brew remove [Paketname]`: Entfernt ein installiertes Paket.

## Archivierung und Komprimierung
- `tar -czvf [Archivname].tar.gz [Dateien/Verzeichnisse]`: Erstellt ein komprimiertes Tar-Gzip-Archiv.
- `tar -xzvf [Archivname].tar.gz`: Entpackt ein komprimiertes Tar-Gzip-Archiv.
- `zip [Archivname].zip [Dateien/Verzeichnisse]`: Erstellt ein ZIP-Archiv.
- `unzip [Archivname].zip`: Entpackt ein ZIP-Archiv.

## Sonstiges
- `history`: Zeigt die Befehlsverlaufsliste an.
- `alias [AliasName]='[Befehl]'`: Erstellt ein Alias für einen Befehl. Zum Beispiel `alias ll='ls -la'`.
- `date`: Zeigt das aktuelle Datum und die Uhrzeit an.
- `cal`: Zeigt den aktuellen Monat des Kalenders an.
- `clear`: Löscht den Terminal-Bildschirm.
