# Niklas_Meta_3pct

APBS-Preset mit progressiver Meta-Orientierung und ca. 3 % Shotgun-Gewichtung pro PMC-Nahbereichs-Waffenpool.

## Installation
1. Nur die 35 JSON-Dateien aus `Presets/Niklas_Meta_3pct/` nach `SPT/user/mods/acidphantasm-progressivebotsystem/Presets/Niklas_Meta_3pct/` kopieren.
2. Die Werte aus `APBS_config_patch.json` in die bestehende APBS-`config.json` übernehmen. Nicht die ganze Config ersetzen.
3. Server neu starten und im Log kontrollieren, dass APBS das Preset lädt.

## Meta-Ausrichtung
Ab Tier 4 werden aktuelle starke Waffen stärker gewichtet: HK416A5, MDR 7.62, Mk47 Mutant, AK-12 und RD-704. A-Tier-Optionen wie M4A1, SA-58, SR-25, TX-15, AUG A3, AK-105 und AS VAL werden moderat bevorzugt. Höhere Tiers erhalten bessere Munition und höhere Chancen auf sinnvolle Kernaufsätze.

Die Waffenrangliste orientiert sich an der Patch-1.1.5-Metaübersicht. Als Build-Referenz dienen unter anderem die Community-Blueprints für HK416A5, M4A1, Mk47, AS VAL und weitere Waffen aus der Tarkov101-Galerie.

## Shotguns
Shotguns werden in jedem PMC-Nahbereichspool separat auf rund 3 % der gesamten Waffengewichtung gesetzt. Die Prüfung der fertigen JSON-Dateien ergab je nach Tier, Fraktion und Slot ca. 2,86–3,13 %. Long-Range-Pools bleiben unberührt.

## Technische Grenze
APBS zieht Aufsätze zufällig aus kompatiblen Tier-Modlisten. Das Preset erhöht daher die Chance auf vollständige, starke und meta-orientierte Builds, garantiert aber keine identischen 1:1-Community-Blueprints. Die tatsächlichen Blueprints aus Community-Galerien werden nicht automatisch von APBS importiert. Dafür wäre ein zusätzlicher Generator für feste waffenspezifische Rezepte nötig.

## Quellen
- APBS: https://github.com/acidphantasm/acidphantasm-apbs
- ALP Revived: https://github.com/Andrewgdewar/ALP-Revived
- Meta-Übersicht Patch 1.1.5: https://leprestore.com/guides/eft/escape-from-tarkov-weapon-tier-list/
- Community-Blueprints: https://tarkov101.com/presets
- Weitere Community-Builds: https://senseos.gg/wiki/escape-from-tarkov/weapon-builds/
