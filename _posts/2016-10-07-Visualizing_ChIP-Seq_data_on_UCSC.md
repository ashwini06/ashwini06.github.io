---
layout: post
title: "Visualizing ChIP seq data on UCSC browser"
date: 2016-10-06
---

While demonstrating ChIP-seq data in the published articles, the enrichment is shown as signals/peaks across certain gene locations. There exists various approaches [ref] by which one can create required input files (bigwig/bedgraph) which can be visualized in any genomics viewer(IGV/ UCSC browser).  

**Deeptools**        
[Deeptools](http://deeptools.readthedocs.io/en/latest/index.html) module contains [bamCompare](http://deeptools.readthedocs.io/en/latest/content/tools/bamCoverage.html) and [bamCoverage](http://deeptools.readthedocs.io/en/latest/content/tools/bamCompare.html) tools which generates bigwig/bedgraph files.


**MACS2**   

[https://github.com/taoliu/MACS/wiki/Build-Signal-Track#Run_MACS2_bdgcmp_to_generate_foldenrichment_and_logLR_track](https://github.com/taoliu/MACS/wiki/Build-Signal-Track#Run_MACS2_bdgcmp_to_generate_foldenrichment_and_logLR_track)


UCSC browser:
[Here](https://genome.ucsc.edu/goldenPath/help/hgTracksHelp.html#CustomTracks) describes various formats by which we can upload data to UCSC.

Example:       
**Display BigWig files**          
Multiple Bigwig files can be uploaded by multiple track lines in one [text file](https://github.com/ashwini06/ashwini06.github.io/blob/master/test_data/bigWiggers.txt). Upon uploading the text file, ChIP signal intensities looks like [this](https://genome.ucsc.edu/cgi-bin/hgTracks?db=mm10&lastVirtModeType=default&lastVirtModeExtraState=&virtModeType=default&virtMode=0&nonVirtPosition=&position=chr3%3A66552219-67402818&hgsid=552638429_xyQghRUJD6mMfpprZXIn5MSLAce4)
