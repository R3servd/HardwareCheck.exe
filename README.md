HardwareCheck by R3servd 🖥️
Ein kleines, schnelles Windows-Tool, das wichtige System- und Hardwareinformationen direkt auf deinem PC ausliest und übersichtlich im Terminal anzeigt – ganz ohne dass Python installiert sein muss!

🚀 Funktionen
Prozessor (CPU): Liest das genaue Modell, die Anzahl der Kerne und die aktuelle Auslastung aus.

Arbeitsspeicher (RAM): Zeigt Gesamtgröße, verfügbaren Speicher und die prozentuale Auslastung an.

Festplatten (SSD/HDD): Analysiert Laufwerk C: und D: hinsichtlich Gesamtgröße, freiem Speicherplatz und Auslastung.

Grafikkarte (GPU): Identifiziert das verbaute Grafikkartenmodell.

Mainboard: Zeigt Hersteller und Produktbezeichnung des Mainboards.

📦 Verwendung (Ohne Installation)
Lade dir die aktuelle HardwareCheck.exe aus dem dist-Ordner herunter.

Mache einen Doppelklick auf die .exe-Datei.

Bestätige die Sicherheitsabfrage mit "ja" (falls erforderlich), und das Tool liest deine Hardware aus!

🛠️ Unter der Haube (Technologie)
Dieses Projekt wurde mit Python geschrieben und nutzt folgende Bibliotheken:

psutil: Für die effiziente Abfrage von CPU-, RAM- und Festplattendaten.

subprocess: Zur Abfrage spezifischer Windows-Hardware über die PowerShell (Get-CimInstance).

PyInstaller: Um das Skript in eine eigenständige .exe-Anwendung zu verpacken.
