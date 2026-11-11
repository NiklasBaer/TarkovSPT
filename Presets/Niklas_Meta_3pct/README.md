# Niklas_Meta_3pct

APBS-Preset für SPT mit stärkerer Meta-Orientierung und einer Shotgun-Gewichtung von 3 % in den erkannten PMC-Nahbereichs-Waffenpools.

## Installation

1. Den Ordner `Niklas_Meta_3pct` nach `SPT/user/mods/acidphantasm-progressivebotsystem/Presets/` kopieren.
2. Die Werte aus `APBS_config_patch.json` in die bestehende APBS-`config.json` übernehmen. Die Datei ist ein Patch, kein vollständiger Ersatz für deine Config.
3. APBS neu starten und den Debug-Equipment-Log für die ersten Raids aktiviert lassen.

## Anpassungen

- PMC-Primärwaffen: erkannte Shotguns in allen Tier-Pools auf 3 % Gesamtgewicht pro Short-Range-Slot skaliert. Die bisherigen Shotgun-Modelle bleiben anteilig erhalten.
- Ab Tier 4 werden aktuelle S-Tier-Waffen stärker gewichtet: HK416A5, MDR 7.62, Mk47 Mutant, AK-12 und RD-704.
- A-Tier-Optionen werden moderat bevorzugt, darunter M4A1, SA-58, SR-25, TX-15, AUG A3, AK-105 und AS VAL.
- Ab Tier 4 werden Chancen für Mündung, Optik, Vordergriff und taktische Anbauteile angehoben; zusätzliche Optiken/Taktikmodule bleiben durch APBS-Mod-Limits begrenzt.
- T7-Thermals bleiben deaktiviert.

## Wichtige technische Grenze

APBS wählt kompatible Aufsätze zufällig aus den jeweiligen Tier-Modlisten. Dieses Preset erhöht daher die Chance auf vollständige, hochwertige und meta-orientierte Waffenbuilds, erzeugt aber keine deterministischen 1:1-Community-Blueprints für jede Waffe. Exakte feste Rezepte würden einen zusätzlichen Weapon-Preset-Generator benötigen.

## Build-Referenzen

- APBS: https://github.com/acidphantasm/acidphantasm-apbs
- ALP Revived APBS-Preset-Konzept: https://github.com/Andrewgdewar/ALP-Revived
- Meta-Waffenübersicht, Patch 1.1.5: https://leprestore.com/guides/eft/escape-from-tarkov-weapon-tier-list/
- Community-Builds: https://senseos.gg/wiki/escape-from-tarkov/weapon-builds/
