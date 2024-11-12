# PDND
Il presente repository contiene la documentazione tecnica di tutte le API catalogate nella Piattaforma Digitale Nazionale Dati.

## Struttura del repository
Il repository contiene una cartella principale chiamata API che organizza la documentazione di ciascuna API in sotto-cartelle separate. 
Ogni sotto-cartella include:
* Documentazione tecnica (in formato PDF);
* Descrittore:
  * in formato YAML per API di tipo REST;
  * in formato WSDL per API di tipo SOAP.

### Esempio struttura delle cartelle
RegioneLombardia/PDND/
├── API/
│   ├── NomeAPI_1/
│   │   ├── documentazione.pdf
│   │   └── descrittore.yaml
│   ├── NomeAPI_2/
│   │   ├── documentazione.pdf
│   │   └── descrittore.wsdl
│   └── ...
