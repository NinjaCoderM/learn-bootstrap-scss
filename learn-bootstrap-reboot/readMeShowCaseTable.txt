<table class="table table-primary" ...              -> table -> css für table in bootstrap + table-primary für color
<thead class="table-danger" ...                     -> color für Kopfzeile
<td class="table-info" ...                          -> color für Zelle
.container>.row>table.table-primary.table-striped   -> color primary und jede zweite Zeile leicht eingedunkelt
.container>.row>table.table-striped-columns         -> jede zweite Spalte leicht eingedunkelt
.container>.row>table.table-hover                   -> Zeilen werden eingedunkelt, wo sich Maus über der Zeile befindet  
tr.table-active bei table.table.table-hover         -> Zeile mit table-active wird immer eingedunkelt, ander Zeilen nur mouseOver
tabel.table.table-bordered                          -> Tabelle mit Umrandung, default ist nur unten ein Strich -> deutlich sichtbar ohne color
tabel.table.table-bordered.border-danger            -> Color für Border 
table-borderless                                    -> ohne Border, default Border-Bottom        
table.table.align-middle                            -> default align-top, daher Text in Zeile wird oben angezeigt, align-middle: Text in Spalte mittig
.container>.row>.table-responsive>table             -> table-responsive, für große Datenmengen z.B. viel Text

Wiederholung
.container>.row>.col-md-6                           -> halbe Breite bis kleiner md ganze Breite
.container>.row>.col-md                             -> breite auto aber kliener md ganze Breite
.container>.row.row-cols-2                          -> fix zwei Spalten