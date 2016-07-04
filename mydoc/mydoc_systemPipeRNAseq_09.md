---
title: Render report in HTML and PDF format
keywords: 
last_updated: Mon Jul  4 15:49:28 2016
---


{% highlight r %}
rmarkdown::render("systemPipeRNAseq.Rmd", "html_document")
rmarkdown::render("systemPipeRNAseq.Rmd", "pdf_document")

# Version Information
{% endhighlight %}

{% highlight r %}
sessionInfo()
{% endhighlight %}

{% highlight txt %}
## R version 3.2.2 (2015-08-14)
## Platform: x86_64-apple-darwin14.5.0 (64-bit)
## Running under: OS X 10.10.5 (Yosemite)
## 
## locale:
## [1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8
## 
## attached base packages:
## [1] parallel  stats4    methods   stats     graphics  grDevices utils     datasets  base     
## 
## other attached packages:
##  [1] ape_3.4                    ggplot2_2.0.0              systemPipeR_1.4.7         
##  [4] RSQLite_1.0.0              DBI_0.3.1                  ShortRead_1.28.0          
##  [7] GenomicAlignments_1.6.1    SummarizedExperiment_1.0.1 Biobase_2.30.0            
## [10] BiocParallel_1.4.0         Rsamtools_1.22.0           Biostrings_2.38.2         
## [13] XVector_0.10.0             GenomicRanges_1.22.1       GenomeInfoDb_1.6.1        
## [16] IRanges_2.4.4              S4Vectors_0.8.3            BiocGenerics_0.16.1       
## [19] BiocStyle_1.8.0           
## 
## loaded via a namespace (and not attached):
##  [1] Rcpp_0.12.3             lattice_0.20-33         GO.db_3.2.2             digest_0.6.9           
##  [5] plyr_1.8.3              futile.options_1.0.0    BatchJobs_1.6           evaluate_0.8           
##  [9] zlibbioc_1.16.0         GenomicFeatures_1.22.13 annotate_1.48.0         Matrix_1.2-3           
## [13] checkmate_1.6.3         rmarkdown_0.9.2         GOstats_2.36.0          splines_3.2.2          
## [17] stringr_1.0.0           pheatmap_1.0.7          RCurl_1.95-4.7          biomaRt_2.26.1         
## [21] munsell_0.4.2           sendmailR_1.2-1         rtracklayer_1.30.1      base64enc_0.1-3        
## [25] BBmisc_1.9              htmltools_0.3           fail_1.3                edgeR_3.12.0           
## [29] codetools_0.2-14        XML_3.98-1.3            AnnotationForge_1.12.0  bitops_1.0-6           
## [33] grid_3.2.2              RBGL_1.46.0             nlme_3.1-122            xtable_1.8-0           
## [37] GSEABase_1.32.0         gtable_0.1.2            magrittr_1.5            formatR_1.2.1          
## [41] scales_0.3.0            graph_1.48.0            stringi_1.0-1           hwriter_1.3.2          
## [45] genefilter_1.52.0       limma_3.26.3            latticeExtra_0.6-26     futile.logger_1.4.1    
## [49] brew_1.0-6              rjson_0.2.15            lambda.r_1.1.7          RColorBrewer_1.1-2     
## [53] tools_3.2.2             Category_2.36.0         survival_2.38-3         yaml_2.1.13            
## [57] AnnotationDbi_1.32.0    colorspace_1.2-6        knitr_1.12
{% endhighlight %}

