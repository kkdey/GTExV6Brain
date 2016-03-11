# GTExV6Brain
Bulk-RNA data across brain samples GTEx V6 project.

Check the [GTEx Portal](http://www.gtexportal.org/home/)

```
library(GTExV6Brain)
counts <- exprs(GTExV6Brain)
meta_data <- pData(GTExV6Brain)
gene_names <- rownames(counts)
```

