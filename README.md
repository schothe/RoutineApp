# 🌟 Meine Kinder-Routine App
Eine barrierefreie, kinderfreundliche Web-Anwendung zur spielerischen Erledigung von Tagesroutinen (Morgen, Tag, Abend). Speziell entwickelt für Kleinkinder und Vorschulkinder (z. B. 3 und 6 Jahre), die ohne Lesekenntnisse intuitiv über Emojis und große Touch-Flächen bedient werden kann.
🚀 Features & Highlights
￼ Visual First (Ohne Lesekenntnisse): Große Kacheln, leuchtende Farben und anschauliche Emoji-Icons.
￼ Mehrkind-Verwaltung: Eigene Profile mit Tier-Avataren (🐶, 🐱, 🐼, 🦁, etc.) und individuellen Ziel-Pokalen.
￼ Tageszeiten-Struktur: Einteilung der Aufgaben nach 🌅 Morgen, ☀️ Tag und 🌙 Abend.
￼ Belohnungssystem & Animationen:
￼ Pop- und Haptik-Effekte beim Abhaken von Kacheln.
￼ Sprachausgabe (⁠SpeechSynthesis⁠) mit motivierendem Lob.
￼ Sternen- und Konfetti-Regen (⁠burst⁠) beim Erfüllen der Tagesaufgabe.
￼ Wochen-Belohnungssystem mit Fortschritts-Tracker (z. B. Pokal ab 5 perfekten Tagen).
￼ Intelligente Filtereinstellungen: Aufgaben können flexibel nach Alter (z. B. nur 6-Jährige), bestimmten Wochentagen (z. B. Kita-Tage Mo–Fr) oder spezifischen Kindern zugewiesen werden.
￼ Geschützter Eltern-Bereich: Zufallsbasierte Rechenaufgabe (Mathe-Gate 🔒) verhindert versehentliches Verstellen durch die Kinder.
￼ PWA & Offline-fähig: Funktioniert dank ⁠localStorage⁠ und Service-Worker komplett ohne Server/Internetverbindung direkt im Browser oder als Web-App auf dem iPad/Tablet-Homescreen.
📁 Dateistruktur für die Web-App
Um die App vollständig als Progressive Web App (PWA) zu nutzen, legst du folgende Dateien im selben Ordner an:
⚙️ Zusatzdateien erstellen
1. ⁠manifest.webmanifest⁠
2. ⁠sw.js⁠ (Offline Service Worker)
3. ⁠icon.svg⁠ (Beispiel Icon)
📲 Installation auf dem iPad / Tablet
1. Öffne die ⁠index.html⁠ in Safari auf dem iPad.
2. Tippe auf das Teilen-Symbol (Quadrat mit Pfeil nach oben).
3. Wähle "Zum Home-Bildschirm" aus.
4. Die App kann nun wie eine native App ohne Adressleiste im Vollbildmodus gestartet werden.
🛠️ Eltern-Bereich Bedienen
￼ Zugang: Tippe oben rechts auf das Schloss-Icon (🔒) und löse die kleine Mathe-Aufgabe.
￼ Kinder verwalten: Namen, Alter und Avatare anpassen oder neue Kinder hinzufügen.
￼ Karten verwalten: Neue Routine-Karten mit Emoji-Icons anlegen, Tageszeiten (Morgen/Tag/Abend) zuweisen und Alters- oder Wochentag-Filter aktivieren.
￼ Wochen-Ziel: Zielanzahl an perfekten Tagen festlegen, ab denen der Pokal verliehen wird.
￼ Einstellungen: Sprachausgabe aktivieren/deaktivieren oder den Tagesfortschritt zurücksetzen.