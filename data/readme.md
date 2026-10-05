# Data

This directory contains the metadata dataset used by the Jupyter notebook `Glagoljicna_bastina_vizualizacije.ipynb`.

## File

- `glagolab_zadar_archdiocese_metadata.csv` — metadata describing 136 Glagolitic manuscripts from the Zadar Archdiocese.

## Source

The metadata originate from the **GlagoLab catalogue** of the Centre for Research in Glagolitism, University of Zadar, Croatia:
https://glagolab.unizd.hr
The collection comprises Glagolitic manuscripts gathered from parishes of the Zadar Archdiocese by don Pavao Kero and currently held at the **Archive of the Zadar Archdiocese (Arhiv Zadarske nadbiskupije)**.

## Dataset structure

The CSV file contains 136 records and 16 metadata fields:
- `id`
- `naslov`
- `raspon_godina_izdavanja_proizvodnje`
- `mjesto_izdavanja_proizvodnje`
- `materijal_podloge`
- `sadrzi_vodeni_znak`
- `vodeni_znak`
- `materijal_uveza`
- `vrsta_uveza`
- `ocuvanost_primjerka_uvez`
- `ocuvanost_primjerka_knjizni_blok`
- `organizacija`
- `provenijencija`
- `imatelj`
- `signatura`
- `sadrzaj`

Missing values are preserved as empty fields.

## Provenance

The CSV file was exported from the metadata embedded in the accompanying Jupyter notebook in order to make the underlying research data separately accessible and reusable.
The metadata were created within the GlagoLab catalogue by Marijana Tomić, Laura Grzunov and Marta Ivanović.

## Use in this repository

The dataset is used to generate the static and interactive visualisations available in the `outputs/` directory.
The Jupyter notebook contains the complete processing and visualisation workflow.

## Citation

When using these data, please cite the GlagoLab catalogue and, once available, the corresponding Zenodo dataset record.

## Rights and reuse

The descriptive metadata originate from the GlagoLab catalogue of the Centre for Research in Glagolitism, University of Zadar.
No additional licence for redistribution or reuse of the metadata is asserted in this repository unless explicitly stated in the corresponding Zenodo dataset record.
Please consult the GlagoLab catalogue and the Zenodo record for applicable rights and reuse conditions.
