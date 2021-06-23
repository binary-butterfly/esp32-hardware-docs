# Platine herstellen

## CNC Fräse

Um die Platine herzustellen muss sind im Ordner `/board/` drei TAP-Dateien, um die Fräse anzusteuern:

* die `/board/rad.bot.etch.tap` beschreibt das Wegfräsen auf der Unterseite
* die `/board/rad.top.etch.tap` beschreibt das Wegfräsen auf der Oberseite  
* die `/board/rad.bot.drill.tap` beschreibt die Bohrlöcher

## Professionelle Dienstleister

Hat man keine CNC-Fräse zur Hand, so lohnt ein Blick auf professionelle Anbieter, welche einem printed circuit boards (PCBs) herstellen. Herstellungskosten für das Board liegen bei ca. 10 - 20 Euro. Hersteller von PCBs erwarten ein Layout, welches in `/board/board.kicad_pcb` als KiCad-Datei vorliegt.
