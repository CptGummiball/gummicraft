
# Changelog

## 1.5.6 - 17.10.2026

**Stabilitäts-, Performance- und Balancing-Update**

### Updates:
- Supplementaries
- Crops Love Rain
- Collective

### Hinzugefügt:
- Lithium 0.15.4 wieder als Mod aufgenommen (Server/Client).

### Änderungen:
- Dauerhaften spark-Hintergrund-Profiler deaktiviert (Client).
- Simulation-Distance von 10 auf 8 Chunks reduziert. Dadurch sinkt die tickende Fläche pro Spieler um ca. 34 %. Die Sichtweite bleibt bei 10 Chunks (Server).
- Emotecraft Debug-Modus deaktiviert (Server/Client).
- Spawns zahlreicher Tierarten reduziert, Gruppengrößen verkleinert, Persistenz angepasst und doppelt vorhandene Tiere deaktiviert.
- Münzen-XP-Exploit behoben: Schmelzrezepte für Münzen geben keine XP mehr.
- Lost Trinkets: Magische Federn (Kreativflug) und Leeres Amulett (unendliche Enderperlen) gesperrt.
- Haley-Bier gewährt keinen Kreativflug mehr.
- Maximale Amboss-Kosten auf 50 Level begrenzt.
- Solarpanele V–VII (Energized Power) erzeugen weniger Energie: 4.096 / 16.384 / 49.152 E/t.
- Lava-Erzeugung durch den Stone Liquefier deutlich reduziert.
- Thermal Generator: Energieerzeugung pro Lava-Eimer von 50.000 auf 25.000 E halbiert.
- Endlos-Energie-Exploit durch Stone Liquefier und Thermal Generator behoben.
- Tesseract-Rezept deutlich verteuert und an Pipsters Quantum Tesseract angepasst.
- Botany Pots: Erntewerkzeuge verlieren wieder Haltbarkeit.
- Powah Uraninit-Erz seltener: Adern pro Chunk von 8/6/3 auf 4/3/2 reduziert.
- QuantaVolt-Roh-Uran mit Oritech-Roh-Uran vereinheitlicht.
- Fake-Player müssen die jeweiligen Team-Einstellungen für Claims beachten.
- Neue Teams verbieten Fake-Player standardmäßig. Bestehende Einstellungen bleiben erhalten.
- Carry On: Energiemaschinen, Spawner, Tresore, Shops und weitere kritische Blöcke können nicht mehr getragen werden.
- Carry On: Villager, Wanderhändler und Bienenkönigin können nicht mehr getragen werden.
- Vinery: Maximale Wein-Effektstufe von V auf II reduziert.
- Vinery: Reifezeit pro Effektstufe von 6 auf 8 Jahre erhöht.
- Vinery: Effektdauer pro Jahr halbiert und maximale Dauer von 15.000 auf 6.000 Ticks reduziert.
- Farmer's Bread: Pro Backvorgang entsteht nur noch 1 statt 3 Brote.
- Übermächtige Gerichte mit Sättigung II, Extraherzen II oder Regeneration III deaktiviert.
- Herstellung verschiedener Drachenei-Gerichte deaktiviert.

### Fixes:
- Client: Fehlerhafte 4x7-Pixel-Textur von `displaydelight:block/ctd_egg_roll` verlustfrei auf 64x112 skaliert. Dadurch funktionieren Mipmaps wieder korrekt und entfernte Blöcke flimmern weniger.
- Client: Startabsturz durch Lithium in Kombination mit Tinkers' Construct behoben. Nur das Fluid-Fluss-Modul wurde deaktiviert.
- Client: Easy NPC `/function`, Carry On sowie Spawn- und Balancing-Konfigurationen mit dem Server synchronisiert.
- Server: Absturz durch WilderNature-Igel behoben.
- Server: Absturz durch Oritech-Fluid-Pipes an Tinkers-Schmelzofen-Ausgüssen behoben.
- Server: Stille Flüssigkeits-Duplizierung, Flüssigkeitsverluste und Log-Flut behoben.
- Server: Watchdog-Absturz durch große Energized-Power-Kabelnetze behoben.
- Server: Defekte Datendateien beim Serverstart repariert.
- Server: Doppelte Mod-Datei entfernt.
- Energized Power: Geisterblöcke und Fehler beim Entfernen von Maschinen behoben.
- Easy NPC: NPC-Befehle werden wieder korrekt ausgeführt.
- FTB Chunks: Interaktions-Whitelist korrigiert.
- Hybrid Delights: 11 Gerichte sind im Farm-&-Charm-Kochtopf wieder kochbar.
- Wildkohl droppt wieder und kann wieder geschnitten werden.
- Vinery-Konfiguration im neuen 1.5.6-Format aufgebaut und bestehende Werte übernommen.
- Fehler-Flut durch Unify im Log behoben.

### Notes:
- **Carry On:** Spawner, Tresore, Villager, Wanderhändler, Technik-Maschinen, Shops und weitere sensible Blöcke können nicht mehr aufgehoben werden.
- **Lost Trinkets & Brewery:** Magische Federn, Leeres Amulett und Kreativflug durch Haley-Bier deaktiviert. Bereits freigeschaltete Trinkets werden entfernt.
- **Vinery:** Weine erreichen maximal Effektstufe II statt V.
- **Energie-Balancing:** Solarpanele V–VII, Thermal Generator und Stone Liquefier deutlich abgeschwächt. Bestehende Anlagen funktionieren mit den neuen Werten weiter.
- **Tesseract:** Neues, teureres Rezept mit Quantum Core und Netheritbarren. Bereits gebaute Tesseracts bleiben erhalten.
- **Exploit-Fixes:** Münzen-Schmelzen gibt keine XP mehr. Amboss-Kosten sind auf maximal 50 Level begrenzt.
- **Food-Balancing:** Farmer's Bread ergibt nur noch 1 statt 3 Brote. Übermächtige Gerichte wie Drachenei-Speisen, Honigbrot und Blütenkekse sind nicht mehr herstellbar. Vorhandene Gerichte bleiben nutzbar.
- **Botany Pots:** Erntewerkzeuge verlieren wieder Haltbarkeit.
- **Performance:** Farmen und Maschinen bleiben nur noch im Umkreis von 8 statt 10 Chunks um Spieler aktiv.
- **Tier-Spawns:** Weniger Hamster, Wildschweine, Bisons, Nilpferde und weitere Tiere. Vorhandene Tiere bleiben erhalten.
- **Tier-Despawn:** Krokodile, Nilpferde und Springhasen können jetzt verschwinden. Zum dauerhaften Behalten zähmen oder mit Namensschild benennen.
- **Claims:** Fake-Player berücksichtigen jetzt die Team-Einstellungen. Bitte unter FTB Chunks prüfen, ob Maschinen anderer Teams in euren Claims erlaubt sein sollen.
- **Teleportation:** `/rtp` ist auf maximal 8.000 Blöcke Entfernung begrenzt.
- **Rezepte und Fixes:** Hybrid-Delights-Gerichte im Farm-&-Charm-Kochtopf verfügbar. Wildkohl-Drops und NPC-`/function`-Aktionen (z. B. King Gummi) repariert.
- **Launcher/RAM:** Für G1 werden feste 8 GB RAM (Minimum = Maximum) empfohlen. Bei 32 GB System-RAM sind optional 10 GB möglich. Mehr RAM bringt normalerweise keine Vorteile und kann GC-Pausen verlängern.
- **Launcher/ZGC:** Nur bei mindestens 8 CPU-Kernen und 32 GB RAM empfohlen. Dann 12 GB RAM zuweisen.
- **Arbeitsspeicher:** Dual-Channel ist wichtiger als DDR4 oder DDR5. G1 profitiert kaum von DDR5, ZGC dagegen stärker von hoher Speicherbandbreite.
- **Shader/FPS:** Bei niedrigen FPS im Shader-Profil `COLORED_LIGHTING` von 192 auf 128 oder 0 reduzieren.



## 1.5.5 - 16.10.2026
### Fixes + Updates + QoL

Updates:
- More Lectern Variants
- Hybrid Delights
- [Let's Do] Mods
- Natures Spirit
- Midnight Lib
- Collective
- Supplementaries
- Puzzles Lib
- More Barrel Variants
- Moonlight Lib
- Lithostitched
- Immediately Fast
- Fusion
- EuphoriaPatcher
- EasyNPCs

Hinzugefügt:
- AFK Mods
- Nepi
- Subtle Effects
- Crops Love Rain
- Bookshelf Inspector
- Explosive Enhancement

Entfernt:
- Präriehund

Downgrade:
- Oritech

Fixes:
- Apfelpresse produziert jetzt nicht mehr als einen Stack (Chunk Save Bug)
- Oritech Fluid Container Fix

## 1.5.4 - 11.10.2026

Hinzugefügt:
- FTB-Questbuch hinzugefügt mit 25 Kapiteln in 8 Gruppen und 577 Quests (by cptgummiball)

Änderungen:
- Puff-Bomben, wachsen nicht mehr einfach so auf Feldern
- Accesoires haben jetzt ein gemeinsames Menü (by cptgummiball)
- Modpack gesäubert (Alte configs, Dateien und Ordner entfernt)
- Neues Hauptmenü (by cptgummiball)
- Neuer Ladebildschirm (by cptgummiball)
- Web Map wurde entfernt um dem Server etwas zu entlasten

Fixes:
- Käse-Tags repariert: Käsegerichte aus Candlelight und Meadow sind wieder herstellbar, unter anderem Lasagne, Pasta Bolognese, Tomaten-Mozzarella-Salat und Käsesandwich.
- Tinkers’ Construct gießt jetzt die vereinheitlichten Materialien (Oritech-Stahl, -Kupfernuggets, -Stäube, -Silizium) statt alter Doppel-Varianten.
- EMI blendet jetzt auch die vereinheitlichten QuantaVolt-Duplikate aus (Stahlbarren, Uranstaub, Tiefenschiefer-Uranerz).
- options.txt wird jetzt beim ersten Download mit geliefert

## 1.5.2 - 03.10.2026
### Drill Baby, Drill!

Hinzugefügt:
- [Let's Do] Smoker

Updates:
- QuantaVolt
- [Let's Do] Candlelight
- [Let's Do Addon] Corn Expansion
- [Let's Do] Bakery, [Let's Do] BloomingNature
- [Let's Do] Brewery
- [Let's Do] Farm & Charm
- AmbientSounds
- Beat Lamp
- Collective
- Entity Culling
- Hybrid Aquatic + API
- Hybrid Delights
- Moonlight Lib
- Oritech
- Xaero's Minimap
- Xaero's World Map
- SuperMartijn642's Core Lib

Änderungen:
- Plöpp wurde aus dem Spiel entfernt
- Gronkh wurde aus dem Spiel entfernt
- QuantaVolt Erdgas: Neue Erdgasvorkommen in der Oberwelt (5–150 Mio. mB). Etwa 60 % der Regionen enthalten kein Gas. Vorkommen sind dauerhaft erschöpfbar. Erdgas liefert doppelt so viel Energie wie Synthesegas.
- QuantaVolt Gasprospektor: Zeigt Gasvorkommen, Restmenge, Förderrate und Richtung zum nächsten Vorkommen an.
- QuantaVolt Gasbohrturm: Förderturm mit 3 × 3 Blöcken Grundfläche und 6–12 Blöcken Höhe. Fördert je nach Höhe 60–300 mB/t. Kosten: 0,5 E/mB. Förderrate sinkt bei Erschöpfung.
- QuantaVolt Oxyfuel: Gasturbine, Gasmotor und Kessel erzeugen mit zusätzlichem Sauerstoff 25 % mehr Wärme.
- QuantaVolt Gasfackel: Verbrennt überschüssige Gase (bis 500 mB/t) ohne Energiegewinnung. Mit Flammeneffekt und Redstone-Steuerung.
- QuantaVolt Bauprojektor: Zeigt Baupläne, fehlende Materialien und Blockpositionen für alle 22 Multiblock-Anlagen. Unterstützt verschiedene Größen und schichtweise Projektionen.
- QuantaVolt Fortschritte: 29 neue QuantaVolt-Fortschritte für Maschinen, Technologien und besondere Ereignisse.
- QuantaVolt Asche: Neue Rezepte für Thermobeton, Stahlbeton und Knochenmehl (3 Asche = 1 Knochenmehl).
- QuantaVolt Verbundene Texturen: Fehlende Eckpixel an Sichtglasrahmen behoben.
- QuantaVolt Kessel: Unterstützt jetzt Erdgas und Synthesegas als Brennstoff.

Fixes:
- Kupfernuggets: Die Clutter-Rezepte mit Kupfernuggets (Large Copper Chain und 60 weitere) funktionieren jetzt mit den herstellbaren Oritech-Nuggets. Doppelte Items, die das Pack zusammenführt (Kupfernuggets, Stahl, Silizium, Erzstaub), werden in EMI nicht mehr mehrfach angezeigt.
- QuantaVolt: Per Befehl (/setblock, /fill), Strukturen oder Mods platzierte Anlagenteile verbinden sich sofort mit benachbarten Blöcken.
- QuantaVolt Kondensatorbank und Solarthermiefeld: Anschlüsse an den Seiten, oben und unten funktionieren jetzt korrekt und zeigen nach außen statt in die Wand.

Notes:
- Wer bei der Energiewende auf erneuerbare Energien gehofft hat, bekommt stattdessen einen Gasbohrturm in den Vorgarten.

## 1.5.1 - 03.10.2026
### POTATO!

Hinzugefügt:
- QuantaVolt PRERELEASE (by cptgummiball)

Updates:
- dummmmmmy
- AmbientSounds
- ClickSigns
- EasyNPCs
- Collective
- ReFramed

Änderungen:
- Ingame-Wiki geupdated

Fixes:

- Tide-Köder lassen sich wieder herstellen. Der Tag für Feldfrüchte (`c:crops`) war durch einen fehlerhaften Kompatibilitäts-Eintrag komplett ausgefallen. Davon waren auch Farm & Charm und Vegan Delight betroffen.
- Der Warden droppt wieder seinen Sculk-Katalysator.
- Salat zählt wieder als Blattgemüse und Salatzutat: Sandwiches, Suppen und Nudelgerichte aus Farmer's Delight sind wieder herstellbar.
- Gerichte mit Milch, Eiern oder Paprika aus Compat Delight funktionieren wieder (Karamell, Marshmallow, Milchschokolade, Butter, Bambuskuchen, Gemüsesalat …).
- Botany Pots: Beerensträucher, Trauben, Hopfen, Tee und Helvola lassen sich jetzt anbauen.
- Stahl-Rüstungsverzierungen funktionieren wieder mit Oritech-Stahl.
- Walfälle (Hybrid Aquatic) generieren wieder in neu erkundeten Gebieten. Die Fische aus Hybrid Aquatic lassen sich mit der Fischfalle fangen.
- Muscheln (Critters & Companions) können über Tide wieder geangelt werden.
- Wilder Kohl droppt beim Abbauen wieder Kohlsamen und gelegentlich Kohl, statt immer nur sich selbst. Den Block selbst bekommt man nur noch mit der Schere.
- Schneidebrett: Wilden Kohl mit dem Messer schneiden ergibt wieder Kohlsamen und gelben Farbstoff, mit etwas Glück zusätzlich Gurkensamen.
- Entrindetes Holz verschiedener Mods zählt wieder als `c:stripped_wood`.
- Öfen aus More Furnace Variants zählen wieder als Ofen (Rezepte aus Quad und Oritech).
- Kleinere Tag-Korrekturen: Grill (Camping) ist mit der Spitzhacke abbaubar, Rucksack-Blöcke lassen sich nicht mehr mit Carry On hochheben, Random Teleport meidet Laub und Bedrock, Mob-Verhalten der Krokodile und Springhasen ist repariert.


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
