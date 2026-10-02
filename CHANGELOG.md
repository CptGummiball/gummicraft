# Changelog

## 1.5.0 - 02.10.2026
### Fix + Stuff + Wiki

Updates:
- Fabric Loader (0.19.3 -> 0.19.5)
- Click Sign
- Clutter
- Easy NPC
- Inventory Essentials
- Fusion (Connected Textures)
- Lithostitched

Hinzugefügt:
- Pipster (by cptgummiball) hinzugefügt (fügt neue Transportrohre und Kabel hinzu)

Entfernt:
- ItemBlocker
- RecipeBlocker

Änderungen:
- Ingame-Wiki geupdated
- Item Unification: Steel vereinheitlicht – Oritech-, Energized-Power- und Tinkers-Steel ergeben jetzt überall denselben Oritech Steel Ingot und Oritech Block of Steel. Steel-Nuggets sind einheitlich die von Energized Power.
- Item Unification: Eisen-, Gold- und Kupferstaub vereinheitlicht – Pulverizer und Grinder aus Oritech und Energized Power liefern denselben Staub (Oritech).
- Item Unification: Kupfernuggets vereinheitlicht (Oritech, Tinkers, Clutter → Oritech), auch beim Gießen in der Tinkers-Schmelze.
- Item Unification: Silizium und Siliziumblöcke vereinheitlicht (Oritech, Energized Power, Refined Storage → Oritech). Alle Maschinen akzeptieren es wie bisher.
- Item Unification: Doppelte Items aus EMI und dem Kreativmenü entfernt – sie liegen gesammelt im Kreativ-Tab „Unified Duplicates" und zeigen im Tooltip das richtige Item.
- Item Unification: Alte Items gehen nicht verloren – jedes Duplikat lässt sich 1:1 umwandeln: einzeln in die Werkbank legen oder mit dem Stack in der Hand rechtsklicken. Platzierte Blöcke droppen beim Abbau automatisch die richtige Variante.
- Item Unification: Problematische Sonderitems sind bewusst ausgenommen, z. B. Uran/Uraninit, Energized Steel, Biosteel, Münzen, Hämmer, Wrenches und Lebensmittel.


Fixes:
- Refined Storage/Energized Power: Compat Layer für den Alloy Furnace eingebaut
- Fehler aus 1.4.32 behoben: Oritech-Staub lässt sich wieder normal schmelzen
- Fehler aus 1.4.32 behoben: Holz-Druckplatten (Kiefer, Tanne, Mahagoni, Ahorn, Palme, Redwood, Weide, Espe, Zypresse, Lärche, Skyroot) gehören wieder zur richtigen Holzart, droppen sich wieder selbst und tauchen wieder normal auf
- Fehler aus 1.4.32 behoben: Der Refined-Storage-Creative-Storage-Block ist wieder er selbst (wurde zum Oritech-Creative-Energy-Storage); Thorn-Coral-Blöcke aus Hybrid Aquatic und Raw Pasta aus Farmer's Delight sind wieder eigenständige Items
- Tinkers-Steel-Rüstungsbesatz (Armor Trim) funktioniert wieder, jetzt mit dem Oritech-Steel-Ingot


Notes:
- Wer in 1.4.32 Energized-Power-Staub, EP-Steel oder Clutter-Kupfernuggets gelagert hat, sollte diese einmal umwandeln (Werkbank oder Rechtsklick). Bis dahin passen sie in keine Rezepte.
- Autocrafting-Muster, Filter und Exporter, die auf die alten Items eingestellt sind, ggf. neu setzen.




## 1.4.32 - 30.09.2026
### Fix + Stuff + Wiki

Hinzugefügt:
- Pick Up Notifier hinzugefüg
- Powah!
- CraftTweaker

Änderungen:
- Ingame Wiki überarbeitet
- Gefährliche Oritech Blöcke abgeschaltet

Fixes:
- Tesseract: Item Puffer für Pipe Anbindung eingebaut
- Music Discs: Reichweiten verringert
- FTB Chunks: Todespunkte ausgeschaltet


## 1.4.31 - 29.09.2026
### Fix + Stuff

Hinzugefügt:
- weitere Music Discs
- RailNet (by cptgummiball | Beta)

Updates:
- MoonlightLib
- CreativeCore
- Collective
- Balm
- [Let's Do] Applewood Rebarked
- BeatLamp
- Geophilic
- Iventory Essentials
- Click Signs
- FTB Mods

Fixes:
- Minecarts werden von CarryOn nun ignoriert
- Botany Pots-Kompatibilität deutlich erweitert:
  - Unterstützung für zahlreiche zuvor fehlende Pflanzen, Seeds und Böden ergänzt.
  - Zusätzliche Seed-/Crop-Zuordnungen und passende Soil-Tags hinzugefügt.
  - Offensichtliche False Positives und ungeeignete Deko-/Terrainblöcke herausgefiltert.
- Tesseract:
  - Items und Fluids werden jetzt von jeder Seite erkannt
  - Registriert umliegende Blöcke jetzt sofort und ohne dass diese neu gesetzt werden müssen

Sonstiges:
- Configs aufgeräumt

Notes:
- Bekannter Bug: Refined Storage Grid flackert wenn ein Network Receiver angebunden ist (lässt sich temporär beheben wenn man den Receiver regelmäßig neu setzt)

## 1.4.27 - 27.09.2026
### Fix + Stuff

Hinzugefügt:
Tesseract hinzugefügt (Items, Flüssigkeiten und Strom schneller, weiter und über Dimensionen hinweg bewegen)
Beat Lamp hinzugefügt
cat_jam hinzugefügt
Party Parrot hinzugefügt

Updates:
- [Let's Do] Bakery - Farm&Charm Compat
- [Let's Do] Farm & Charm
- Exposure
- Hybrid Aquatic
- Mod Menu
- Trash Cans
- Waystones
- Sodium
- Entity Culling

Fixes:
- Biomes of Plenty: Corrupted End abgeschaltet
- Tinkers Construct: Tank Update Stacktrace Disconnect gefixed

## 1.4.25 - 23.09.2026
### Fix

Shader:
- BSL & Solas Shader entfernt
- Miniature Shader hinzugefügt (Sehr simpler performanter Shader für ältere Systeme)

Fixes:
- Complementary Unbound + Euphoria Patches: Falsche Shader-Blockeigenschaften für Marigold und Oritech Reactor Redstone Port entfernt
- EMI: Abstürze und Fehler bei Reparatur- sowie Tinkers’-Construct-Rezepten behoben.
- Rechiseled: EMI-Integration an Rechiseled 1.2.6 angepasst und Rezeptanzeige repariert.
- Compat Delight: Fehlerhafte und nicht verfügbare Rezepte korrigiert bzw. sauber übersprungen.
- Let’s Do Compat: Fehler beim Auslesen von requireContainer behoben.
- Diagonal Fences: 14 problematische Macaw’s-Fences von diagonalen Verbindungen ausgeschlossen.
- Diagonal Walls: 1024 problematische Aether-Wände von diagonalen Verbindungen ausgeschlossen.

## 1.4.2 - 21.09.2026
### Big Update Part 2: Beyond the Clouds

Hinzugefügte Mods:
- Connectible Chains
- The Aether
- Aether Villages hinzugefügt
- Farmer's Cutting: The Aether hinzugefügt
- Energized Power - The Aether hinzugefügt
- MapSyncer-for-XaeroWorldmap

Entfernte Mods:
- Treeharvester entfernt (Überschneidung zu FTB Ultimine)

Updates:
- [Let's Do] Apple Wood Rebarked
- [Let's Do] Alpine Whispers
- [Let's Do] Beachparty
- [Let's Do] BloomingNature
- [Let's Do] Brewery - Farm&Charm Compat
- [Let's Do] Camping updated",
- [Let's Do] Candlelight - Farm&Charm compat
- [Let's Do] Farm & Charm
- [Let's Do] Furniture
- [Let's Do] Hearth & Timber
- [Let's Do] HerbalBrews
- [Let's Do] Lili's Lucky Lures
- [Let's Do] Lili's Pottery
- [Let's Do] Vinery
- [Let's Do] Meadow
- [Let's Do] WilderNature
- Adorable Hamster Pets
- Easy NPC
- Energized Power
- Entity Culling
- Fancy Entity Renderer
- FancyMenu
- Fusion
- Geckolib
- Hybrid Aquatic
- ImmediatelyFast
- Immersive Melodies
- Inventory Essentials
- Fzzy Config
- Oritech
- Only Hammers And Excavators
- Puzzles Lib
- Rechiseled
- Sawmill
- Supplementaries
- The Bumblezone - Fabric
- Tide Extra Compatibility
- Visual Workbench
- Universal Enchants
- Waystones
- Moonlight Lib
   

Fixes:
- Oritech -> Tinker Inkompatibilität gefixed
- Tinker Leerer Casting Table fix + 10 weitere Tinker fixes

## 1.4.1 - 20.09.2026
### Big Update Part 1: The Culinary Expansion

Hinzugefügte Mods:
- Farmers Delight
- Farmer's Knives
- Farmer's Cutting: Biomes O' Plenty
- Farmer's Delight: Meal Mastery
- Energized Power - Farmer's Delight
- End's Delight
- Compat Delight
- Rustic Delight
- Ocean's Delight
- Hybrid Delights
- Vegan Delight
- Nature's Delight
- Display Delight Fabric
- Block Pack (1200+ neue Deko Blöcke)
- Nature's Spirit

Fixes:
- Mehr Performance durch Partikel Optimierung
- Mehr Performance durch Entity Optimierung
- Mehr Performance durch Lightmap Optimierung

Notes:
- Kommunikation zwischen Tinker's Construct und Oritech Fliud Röhren aktuell nicht möglich und führt zum Crash!
- Tinker's Construct fehlen noch ein paar Rezepte (kommt mit einem der 1.4 Updates)
- Es gibt noch überschneidungen von Farmer's Delight und Let's Do (werden mit einem der 1.4 Updates behoben)

## 1.3.4/1.3.5 - 29.08.2026

Hinzugefügte Mods:
- More Stick Variants
- More Weapon Variants
- More Armor Stands Variants
- More Tool Variants
- More Torch Variants
- More Rails Variants
- More Ladder Variants

Entfernte Mods:
- Axiom
- Supplemental Patches

Fixes:
- Tinkers Construct Rezeptfehler behoben
- Tinkers Construct fehlende Items teilweise behoben

## 1.3.0 - 22.08.2026

Hinzugefügte Mods:
- Underlay (ermöglicht es, Teppiche (und alles andere) unter jedem Block zu platzieren, unter dem sich freier Raum befindet)
- Unify (Reduzierung von Artikelduplikaten; Zusammenführung aller duplizierten Materialien)
- FTB Granular Claims (erweitert FTB Chunks + FTB Teams um deutlich feinere Claim-Rechte)
- TINKERS CONSTRUCT (Fabric Port von CaptainGummiball)

Änderungen:
- 24 Mods geupdated

Notes:
- Tinkers Construct kann noch Probleme machen, muss es aber nicht. Bitte alle Bugs melden

## 1.2.8 - 16.08.2026

Hinzugefügte Mods:
- Polymorph (hilft bei Rezept Konflikten)
- Splinecart (Achterbahn YAY!)
- Axiom (Admin Zeugs)

## 1.2.1 - 16.08.2026

Fixes:
- Menü Fix


## 1.2.0 - 14.08.2026

Hinzugefügte Mods:
- Oracle Index **(in den Optionen liegt die ingame Wiki auf "H", das müsst ihr anpassen, ansonsten öffnet sie sich nicht wegen überschneidender Tastenbelegung)**

Fixes:
- Erneuter Ressourcepack Fix (Jetzt funktioniert es! alle Notwendigen Ressourcen können nicht mehr entfernt werden!)

## 1.1.0 - 08.08.2026

Hinzugefügte Mods:
- Energized Power + Addons
- Envelope (Brieftauben :3 🐦)
- Recipe Essentials (Performance)
- Tide Extra Compatibility

Änderungen:
- Neues Menü
- Intro
- Xaero Configs von Waria übernommen

Fixes:
- Ressourcepack Fix (Funktioniert noch nicht korrekt über den Launcher)
- Config Fix (Funktioniert noch nicht korrekt über den Launcher)

## 1.0.5 – 04.08.2026

Fixes:
- Werkzeug Fix
