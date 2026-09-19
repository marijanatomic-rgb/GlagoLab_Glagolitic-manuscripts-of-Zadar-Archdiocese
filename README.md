# Glagoljski rukopisi Zadarske nadbiskupije – vizualizacije

Interactive data visualisations of Glagolitic manuscripts from the Zadar Archdiocese (*Glagoljski kodeksi Zadarske nadbiskupije*), built as a self-contained Jupyter notebook that runs locally or in Google Colab without any additional file uploads.

---

## Data source

The metadata comes from the **GlagoLab catalogue** at the Centre for Research in Glagolitism of the University of Zadar, Croatia

> [https://glagolab.unizd.hr](https://glagolab.unizd.hr)

The collection comprises Glagolitic manuscripts gathered from parishes of the Zadar Archdiocese by don Pavao Kero, now held at the **Arhiv Zadarske nadbiskupije** (Archive of the Zadar Archdiocese). The manuscripts are mainly parish registers (*matične knjige*) and confraternity books (*madrikule*) from Dalmatian islands and coastal villages, dating from the 17th to 19th century.

---

## Project context

This notebook was created as part of the project **The Library as an Accelerator of the Digital Transformation of Research in the Humanities and Cultural Heritage (UNILIB – HUB)** at the Department of Information Sciences and Technologies, University of Zadar, Croatia

The project is funded by the **European Union – NextGenerationEU**.

---

## Team

| Role | Name |
|---|---|
| Project head | Prof. Marijana Tomić |
| Metadata creators | Prof. Marijana Tomić, dr. Laura Grzunov, Marta Ivanović |
| Jupyter notebook | Prof. Marijana Tomić, Prof. Željka Tomasović |
| Code assistance | [Claude](https://claude.ai) (Anthropic) |

---

## Contents

The notebook produces **11 visualisations**:

| Output file | Description |
|---|---|
| `glag_kronologija.png` | Chronological distribution by century and 25-year period |
| `glag_vrste_dokumenata.png` | Document type distribution (registers, madrikule, etc.) |
| `glag_heatmapa.png` | Heatmap: place of origin × document type |
| `glag_stanje.png` | Condition of binding and text block |
| `glag_uvez.png` | Binding materials and binding types |
| `glag_vodeni_znakovi.png` | Watermark presence and most frequent motifs |
| `glag_wordcloud.png` | Word cloud of manuscript titles |
| `glag_karta.html` | **Interactive map** — manuscripts by place (click for details) |
| `glag_karta_heatmap.html` | **Interactive heat map** — geographic density |
| `glag_vrste_po_mjestima.html` | **Interactive chart** — document types by place (Altair, filterable) |
| `glag_vremenska_crta.html` | **Interactive timeline** — manuscript date spans by document type |

---

## How to open and run

### Option A — Google Colab (no installation required)

1. Upload `Glagoljicna_bastina_vizualizacije.ipynb` to Google Drive.
2. Right-click → **Open with → Google Colaboratory**.
3. In the notebook menu choose **Runtime → Run all**.

The first cell automatically installs any missing packages. All data is embedded in the notebook — no file upload is needed.

### Option B — Local Jupyter / VS Code

```bash
pip install pandas numpy matplotlib seaborn folium wordcloud geopy altair
jupyter notebook Glagoljicna_bastina_vizualizacije.ipynb
```

Then run all cells. Visualisations are saved to the `slike/` subfolder.

---

## Requirements

| Package | Purpose |
|---|---|
| `pandas`, `numpy` | Data loading and processing |
| `matplotlib`, `seaborn` | Static charts |
| `folium` | Interactive maps |
| `altair` | Interactive charts |
| `wordcloud` | Word cloud |

All packages are installed automatically when running in Google Colab.

---

## Licence

The **code** in this notebook is released under the [MIT Licence](https://opensource.org/licenses/MIT).

The **data visualisations** are released under [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)](https://creativecommons.org/licenses/by-nc-nd/4.0/). You may view and cite them, but may not share, adapt, or use them for commercial purposes.

Suggested citation:
> Tomić, Marijana. *Glagoljski rukopisi Zadarske nadbiskupije – vizualizacije metapodataka*. Centre for Research in Glagolitism, University of Zadar, 2026. [https://glagolab.unizd.hr](https://glagolab.unizd.hr)

---

## Acknowledgements

Funded by the **European Union – NextGenerationEU**.  
Data: *GlagoLab katalog*, [Centre for Resaerch in Glagolitism, University of Zadar, Croatia](https://glagolab.unizd.hr).  

