# microbiome_urine_fertilizer
It is a study on the microbiota and ARGs of source-separated urine during the process of fertilizer production.  In this study, samples of collected urine at two public events in Vermont were processed and sequenced with Illunina Hiseq 2000 in the DNA sequencing core of the University of Michigan.  The downstream analysis pipelines involved various bioinformatic tools as listed below:
Quality check using Fastqc
Adaptor sequences removal from the reads using scythe
Assembly using IDBA UD
Taxonomic classification from the initial reads using Kraken
Abundance calculation of identified microbial groups using Bracken
Read mapping against assembled scaffold using BWA
Conversion of sam to bam using samtools
Calculating coverage using bedtools
