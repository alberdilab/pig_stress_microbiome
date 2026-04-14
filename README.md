# pig_stress_microbiome
Pig stress microbiomes repository

## Preprocessing

```{sh}
drakkar preprocessing -i reads -r genome/GCA_000003025.7_T2T-Sscrofa_genomic.fna.gz
```

## Cataloging

```{sh}
drakkar cataloging -m individual
```

## Profiling

```{sh}
drakkar profiling -a 0.95
```

