# DP_Frantisek

### Optimalizačný projekt Wandb & Biases[]()
### Pracovné súbory:
- Jupyter Notebook [predspracovanie_dat.ipynb](https://github.com/IShadowStormI/DP_Frantisek/blob/main/predspracovanie_dat.ipynb) obsahuje algoritmus slúžiaci na predspracovanie snímok a rovnako tak aj vytvorenia dataframu obsahujúceho vyextrahovaný typ cieľovej triedy a názvu týchto snímok.
- Jupyter Notebook [main_without_imggen.ipynb](https://github.com/IShadowStormI/DP_Frantisek/blob/main/model1/main_without_imggen.ipynb) obsahuje algoritmus slúžiaci na zrealizovanie experimentu 1 a tým aj vytvoreniu modelu 1.
- Jupyter Notebook [main_with_imggen.ipynb](https://github.com/IShadowStormI/DP_Frantisek/blob/main/model2/main_with_imggen.ipynb) obsahuje algoritmus slúžiaci na zrealizovanie experimentu 2 a tým aj vytvoreniu modelu 2.
- Jupyter Notebook [wandb_final.ipynb](https://github.com/IShadowStormI/DP_Frantisek/blob/main/wandb/wandb_final.ipynb) obsahuje algoritmus využitý pri realizácií procesu optimálneho vyhľadávania parametrov siete prostredníctvom platformy [Wandb & Biases](https://wandb.ai/site).
- Jupyter Notebook [A-fiery-sweep-14.ipynb](https://github.com/IShadowStormI/DP_Frantisek/blob/main/wandb/fiery-sweep-14/A-fiery-sweep-14.ipynb) obsahuje algoritmus využitý pre namodelovanie a vyhodnotenie modelu fiery-sweep-14
- Jupyter Notebook [B-decent-sweep-4.ipynb](https://github.com/IShadowStormI/DP_Frantisek/blob/main/wandb/decent-sweep-4/B-decent-sweep-4.ipynb) obsahuje algoritmus využitý pre namodelovanie a vyhodnotenie modelu decent-sweep-4
- Jupyter Notebook [B-honest-sweep-24.ipynb](https://github.com/IShadowStormI/DP_Frantisek/blob/main/wandb/honest-sweep-24/B-honest-sweep-24.ipynb) obsahuje algoritmus využitý pre namodelovanie a vyhodnotenie modelu hones-sweep-24
- Jupyter Notebook [B-icy-sweep-7.ipynb](https://github.com/IShadowStormI/DP_Frantisek/blob/main/wandb/icy-sweep-7/B-icy-sweep-7.ipynb) obsahuje algoritmus využitý pre namodelovanie a vyhodnotenie modelu icy-sweep-7

### Vstupné a výstupné súbory
**Vstupné súbory** -- vstupným súborom tejto práce bol verejne dostupný [dataset](https://data.mendeley.com/datasets/fk6rys63h9/1) snímok koronárnych tepien srdca
**Výstupné súbory** -- v tomto prípade sú výstupnými súbormi jednotlivých častí váhy modelu vo formáte .h5 ako aj ich výsledky vo formáte .csv, ktoré sú roztriedené
podľa príslušnej operácie (procesu), a to na:
1. Predspracovanie dát
⋅⋅* train.pkl -- predspracovaná trénovacia množina + dataframe
⋅⋅* test.pkl -- predspracovaná testovacia množina + dataframe
⋅⋅* valid.pkl -- predspracovaná validačná množina + dataframe
2. Experiment 1
⋅⋅* main_without_imggen.h5 -- najlepšie váhy modelu 1
⋅⋅* [main_without_imggen.csv] -- výsledky jednotlivých váh modelu 1
3. Experiment 2
⋅⋅* main_with_imggen.h5 -- najlepšie váhy modelu 2
⋅⋅* [main_with_imggen.csv] -- výsledky jednotlivých váh modelu 2
4. Experiment 3
⋅⋅* fiery-sweep-14-40.h5 -- najlepšie váhy modelu fiery-sweep-14
⋅⋅* [fiery-sweep-14.csv] -- výsledky jednotlivých váh modelu fiery-sweep-14
⋅⋅* decent-sweep-4-38.h5 -- najlepšie váhy modelu decent-sweep-4
⋅⋅* [decent-sweep-4.csv] -- výsledky jednotlivých váh modelu decent-sweep-4
⋅⋅* honest-sweep-24-34.h5 -- najlepšie váhy modelu honest-sweep-24
⋅⋅* [honest-sweep-24.csv] -- výsledky jednotlivých váh modelu honest-sweep-24
⋅⋅* icy-sweep-7-18.h5 -- najlepšie váhy modelu icy-sweep-7
⋅⋅* [icy-sweep-7.csv] -- výsledky jednotlivých váh modelu icy-sweep-7
