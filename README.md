# Open-source Tension-disk Infiltrometer Meta-Databse (OTIM-DB)

This repository is part of the [EJP SOIL CLIMASOMA project](https://ejpsoil.eu/soil-research/climasoma/).

This database compile data and meta-data about tension-disk infiltrometer measurements from scientific publications. To be included in the database the publication data needs to:
- be taken with an tension-disk infiltrometer in the field (not in the lab)
- contains at least two tensions (so we can fit a linear model in log-space)
- contains meta-data about the environment and management practices (at least soil type, locations, land use and tillage)

The OTIM-DB.xlsx is a relational database structured in multiples tables (multiple sheets) in a spreadsheets. The figure below illustrate the overall structure of the database. The keys of the different tables are shown in bold.

![OTIM-DB structure](structure.png)

An **exploratory data-analysis**, analysing the correlation between the different variables and a **meta-analysis** on specific factors (landuse, tillage, compaction, sampling time) was carried on the database.

This repository contains:
- [data/OTIM-DB.xlsx](data/OTIM-DB.xlsx): the OTIM database
- [notebooks/otim-fit.ipynb](notebooks/otim-fit.iypnb): fitting of a linear relationships in log-space between the hydraulic conductivity and the applied tension
- [notebooks/otim-eda.iypnb](notebooks/otimdb-eda.ipynb): exploratory data analysis (EDA) of the database
- [notebooks/meta-analysis.ipynb](notebooks/meta-analysis.ipynb): meta-analysis using the OTIM-DB

## Citation
Refer to this citation if you make use of the database:
```
TODO bibtex citation
```


