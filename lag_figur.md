
# Dokumentasjon for filen *./lag_figur.sas*


## Makro `lag_figur`

### Beskrivelse

Makro for å lage ratefigur. Makroen bruker rateprogrammet for å lage rater.

### Parametre

- `dsn`: datasettet med (aggregerte) date. Må inneholde følgende variabler: alder, ermann, komnr, bydel, "rate1", "rate2", der
navnene på "rate1" og "rate2" sendes inn som egne argumenter.
- `fignavn` (=&dsn._&rate1._&rate2, hvis ikke oppgitt): figurnavn 
- `mappe` (= "\\hn.helsenord.no\UNN-Avdelinger\SKDE.avd\Analyse\Data\SAS\Bildefiler"): mappen der figur skal lagres
