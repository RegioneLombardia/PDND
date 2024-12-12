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
  ```
  RegioneLombardia/PDND/
  ├── e-services/
      ├── Nome_e-service1
          ├── Nome_e-service1_ManualeUtente.pdf
          ├── Nome_e-service1_DescrittoreTecnico.yaml
      ├── Nome_e-service2
          ├── Nome_e-service2_ManualeUtente.pdf
          ├── Nome_e-service2_DescrittoreTecnico.yaml
      └── ...
  ```
