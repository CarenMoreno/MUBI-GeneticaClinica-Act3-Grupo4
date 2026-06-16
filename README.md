# MUBI-GeneticaClinica-Act3-Grupo4
Actividad 3 grupal - Anotación e interpretación de variantes | Máster Universitario en Bioinformática (UNIR) | Genética Clínica y de Poblaciones | Análisis de exoma (Abraham &amp; Maggie Simpson, GRCh38) | Grupo 4: Caren Moreno, Analia Pastrana, Ángel Guerrero

MUBI-GeneticaClinica-Act3-Grupo4/
│
├── README.md
│
├── datos/
│   ├── AbrahamSimpson.vcf
│   └── MaggieSimpson.vcf
│
├── anotacion_VEP/
│   ├── Abraham_VEP_output.txt
│   ├── Maggie_VEP_output.txt
│   ├── Abraham_VEP_summary.html
│   └── Maggie_VEP_summary.html
│
├── analisis/
│   ├── MC4R/
│   │   ├── clustal_omega_MC4R_Pro272_alignment.fasta
│   │   ├── clustal_omega_MC4R_resultado.png
│   │   └── uniprot_P32245_dominios.png
│   ├── LEPR/
│   │   ├── biomodel_LEPR_wt_traduccion.txt
│   │   ├── biomodel_LEPR_truncada_traduccion.txt
│   │   └── uniprot_P48357_dominios.png
│   ├── TP53/
│   │   └── notas_rs1042522_polimorfismo.md
│   └── MED12/
│       └── notas_VUS_MED12.md
│
├── capturas/
│   ├── VEP_Abraham_pantalla.png
│   ├── VEP_Maggie_pantalla.png
│   ├── gnomAD_MC4R.png
│   ├── gnomAD_LEPR.png
│   ├── OMIM_MC4R.png
│   ├── OMIM_LEPR.png
│   ├── KEGG_ruta_leptina_melanocortina.png
│   └── Reactome_MC4R_LEPR.png
│
├── informe/
│   ├── informe_completo_Act3_Grupo4.md
│   └── poster_Abraham_Maggie_Act3.pptx
│
└── referencias/
    └── referencias_bibliograficas.md


   # Anotación e interpretación de variantes — Actividad 3 Grupal

**Asignatura:** Genética Clínica y de Poblaciones  
**Máster:** Universitario en Bioinformática — UNIR  
**Grupo:** 4  
**Integrantes:** Caren Moreno · Analia Pastrana · Ángel Guerrero  

---

## Descripción

Análisis bioinformático de exoma completo de dos individuos de la familia
Simpson (Abraham y Maggie) a partir de archivos VCF, con anotación de
variantes mediante Ensembl VEP (GRCh38/hg38) e interpretación clínica
de las variantes identificadas en los genes MC4R, LEPR, TP53 y MED12.

---

## Variantes identificadas

| Gen   | Coordenada (GRCh38) | HGVS c.    | HGVS p.           | Tipo        | Clasificación   |
|-------|---------------------|------------|-------------------|-------------|-----------------|
| MC4R  | chr18:60371535      | c.815C>A   | p.Pro272His       | Missense    | Mutación        |
| LEPR  | chr1:65609984       | c.1790del  | p.Ser597IlefsTer20| Frameshift  | Mutación        |
| TP53  | chr17:7676154       | c.215G>A   | p.Pro72Leu        | Missense    | Polimorfismo    |
| MED12 | chrX:71121046       | c.629G>A   | p.Ala210Val       | Missense    | VUS             |

---

## Herramientas utilizadas

| Herramienta        | Uso                                      | URL                                      |
|--------------------|------------------------------------------|------------------------------------------|
| Ensembl VEP        | Anotación de variantes (GRCh38)          | https://www.ensembl.org/Tools/VEP        |
| gnomAD v4.1.1      | Frecuencias alélicas poblacionales       | https://gnomad.broadinstitute.org        |
| Clustal Omega      | Conservación del residuo (missense)      | https://www.ebi.ac.uk/Tools/msa/clustalo |
| UniProtKB          | Dominios proteicos                       | https://www.uniprot.org                  |
| Biomodel/Mutalyzer | Traducción proteína truncada (deleción)  | https://mutalyzer.nl                     |
| OMIM               | Patología y patrón de herencia           | https://www.omim.org                     |
| KEGG / Reactome    | Ruta molecular                           | https://www.genome.jp/kegg               |

---

## Estructura del repositorio

- `datos/` — Archivos VCF originales de Abraham y Maggie Simpson
- `anotacion_VEP/` — Outputs completos de Ensembl VEP
- `analisis/` — Resultados por gen: Clustal Omega, Biomodel, UniProt
- `capturas/` — Capturas de pantalla de todos los análisis realizados
- `informe/` — Informe completo en Markdown y póster en PPTX
- `referencias/` — Bibliografía utilizada

---

## Conclusiones principales

1. La obesidad en Abraham y Maggie se debe a **MC4R p.Pro272His**
   (autosómica dominante, heterocigosis en ambos).
2. Maggie es portadora de una deleción truncante en **LEPR**
   (autosómica recesiva, heterocigosis → no causal por sí sola).
3. Ambos genes integran el **eje leptina–melanocortina**.
4. TP53 p.Pro72Leu es polimorfismo benigno; MED12 p.Ala210Val es VUS.

---

## Licencia

Trabajo académico — UNIR 2025/2026. Solo para uso educativo. 
