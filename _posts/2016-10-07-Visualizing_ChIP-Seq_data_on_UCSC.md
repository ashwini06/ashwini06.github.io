---
layout: post
title: "Visualizing ChIP seq data on UCSC browser"
date: 2016-10-06
---

In  published articles, while demonstrating  ChIP-seq data, the enrichment is shown as signals/peaks  across certain gene locations.

There exists various approaches [ref] by which one can create required files (bigwig/bedgraph) which can be visualized in any genomics viewer(IGV/ UCSC browser).  

**Deeptools**        
[Deeptools](http://deeptools.readthedocs.io/en/latest/index.html) module contains [bamCompare](http://deeptools.readthedocs.io/en/latest/content/tools/bamCoverage.html) and [bamCoverage](http://deeptools.readthedocs.io/en/latest/content/tools/bamCompare.html) tools which generates bigwig/bedgraph files.


**MACS2**   

<a href https://github.com/taoliu/MACS/wiki/Build-Signal-Track#Run_MACS2_bdgcmp_to_generate_foldenrichment_and_logLR_track>https://github.com/taoliu/MACS/wiki/Build-Signal-Track#Run_MACS2_bdgcmp_to_generate_foldenrichment_and_logLR_track</a>
