# Datasets for catalogs OCR and segmentation 

## Description

This repository is composed of two datasets that contain images and transcriptions of historical catalogs. 
These datasets are used to train new models of segmentation and OCR for historical catalogs. 
Segmented zones in the ALTO data presented here are following [SegmOnto guidelines](https://github.com/SegmOnto/Guidelines). 

The `IMAGO` dataset is based on the [repository developed by Juliette Janes](https://github.com/Juliettejns/cataloguesSegmentationOCR/). 
The segmented data provided by Juliette Janes has been updated by Frédérine Pradier to match the current [SegmOnto](https://github.com/SegmOnto) naming zone ontology. 

The `PictoCatalogs` dataset is composed of pictorialist exhibitions catalogs, transcription and segmentation have been done by Frédérine Pradier.

## Repository

```
├── Groundtruth
│      ├── IMAGO
│      │     ├── Annuaires
│      │     ├── Cat_expositions
|      │     └── Cat_manuscrits
|      │     └── Out_of_domain
│      │
|      ├── PictoCatalogs
│      │      ├─ PCP_1894
|      │      ├─ PCP_1896
|      │      ├─ PCP_1898
│      │      └─ PCP_1906
|      │
|      └── README.md
|
└── Models
       ├── OCR
       └── Segmentation           
```

## Credits 

This repository is developed by Frédérine Pradier.

**About the `PictoCatalogs` dataset :**

`PictoCatalogs` dataset, transcription and segmentation have been done by Frédérine Pradier.

**About the `IMAGO` dataset :**

`IMAGO` dataset is based on the [repository developed by Juliette Janes](https://github.com/IMAGO-Catalogues-Jjanes/cataloguesSegmentationOCR) : 
- `Annuaires` preparation has been done by Gabriela Elgarrista, under the supervision of Carmen Brando.
- `Cat_exhibition` preparation has been done by Caroline Corbières.
- `Cat_manuscripts` preparation has been done by Simon Gabay.
- `Out_of_domain` preparation has been done by Simon Gabay.

## Licence

`PictoCatalogs` : The catalogs are in the public domain, images are made available by the Metropolitan Museum of Art under a [CC0](https://creativecommons.org/publicdomain/zero/1.0/deed.fr) license and transcriptions are [CC-BY](https://creativecommons.org/licenses/by/2.0/fr/).

`IMAGO` : Images from catalogs published prior 1920 and transcriptions are [CC-BY](https://creativecommons.org/licenses/by/2.0/fr/). The other images are extracts of catalogs published after 1920 and are the intellectual property of their productor.


## Contacts

frederine.pradier@etu-unige.ch

