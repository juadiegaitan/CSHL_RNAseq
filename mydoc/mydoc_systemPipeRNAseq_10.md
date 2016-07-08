---
title: Render report in HTML and PDF format
keywords: 
last_updated: Fri Jul  8 12:02:11 2016
---


{% highlight r %}
rmarkdown::render("systemPipeRNAseq.Rmd", c("BiocStyle::html_document", "BiocStyle::pdf_document"))
{% endhighlight %}

