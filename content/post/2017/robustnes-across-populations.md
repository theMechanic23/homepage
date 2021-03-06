+++
title = "Transcriptome prediction models are robust across populations"
date = 2017-11-01T17:19:09-05:00
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []
categories = []

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++


Most GWAS and eQTL studies have been performed in European samples. So how well do models trained in Europeans translate to other populations? Segal et al have shown that predictions of gene expression levels are robust across populations ([link](http://dx.plos.org/10.1371/journal.pgen.1003396))

The following figure shows the p-value of the correlation between predicted and observed expression levels in European and African samples from the 1000 Genomes set (GEUVADIS RNA-seq) using model trained in GTEx with majority European individuals. As expected performance decreases (blue is more significant than red) when we apply to African samples but the correlation is still quite significant.
![](https://s3.amazonaws.com/imlab-open/Webdata/Images/2017/geuvadis-performance-EUR-AFR.png)



<!---

So et al use S-PrediXcan to find psychiatric drug repositioning candidates.

## to add figure
![](https://s3.amazonaws.com/imlab-open/Webdata/Images/2017/so2017.png)
--->
