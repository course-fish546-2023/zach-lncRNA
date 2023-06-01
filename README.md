# Long non-coding RNA discovery in *Pocillopora verrucosa*

*For a full overview, take a look at my [project compendium](https://rpubs.com/zbengt/coral-lncRNA-discovery).*

FISH 546 project repo examining the expression of long non-coding RNAs in coral

### Data

This project uses data from Danielle Becker's experiment exposing colonies of *Pocillopora verrucosa* to low level nutrient conditions (nitrogen and phosphorous).

RNA-seq data for 16 control (no low level nutrient exposure) and 16 treatment (low level nutrient exposure) colonies.

-   [GitHub Repo](https://github.com/hputnam/Becker_E5)
-   [RNA-seq data](https://gannet.fish.washington.edu/Atumefaciens/hputnam-Becker_E5/Becker_RNASeq/data/trimmed/)
-   [*P. ver* genome assembly (GFF3 and fasta)](http://pver.reefgenomics.org/download/)
-   [*P. ver* genome assembly GTF](https://gannet.fish.washington.edu/Atumefaciens/20230127-pver-gff_to_gtf/)

### Project Context

Original Citation: [OSF](https://osf.io/uayvk/)

We experimentally enriched corals with dissolved inorganic nitrogen and phosphate for 15 months on an oligotrophic fore reef in Mo'orea, French Polynesia. Our physiological analysis of coral fragments and thermal performance show that in an oligotrophic fore reef environment, nutrient enrichment can cause changes in coral endosymbiont physiology that increase the performance of the coral holobiont. To assess the molecular underpinnings of the enhanced thermal performance due to chronic low nutrient enrichment, we assessed gene expression with RNASeq and the potential for gene expression regulation through whole genome bisulfite sequencing (WGBS). Sequencing of mtORF for 32 samples of Pocillopora spp. (n=16 per treatment) identified three possible species (Pocillopora meandrina, Pocillopora eydouxi, and an unidentified variant). To delineate between Pocillopora meandrina and Pocillopora eydouxi we will be using a new set of primers following methods found in Johnston et al. 2018.

### My Project Goals

-   Identify lncRNAs present within the RNA-seq data
-   Create a list of lncRNA transcript IDs for further use in lncRNA-mRNA co-expression and differential expression analysis

### Workflow for identifying lncRNAs in all 32 samples

![image](https://github.com/zbengt/zbengt.github.io/blob/master/assets/img/lncRNA-disc.png?raw=true)

### Filtering Results

- [List of lncRNA transcript IDs in GTF format](https://github.com/course-fish546-2023/zach-lncRNA/blob/main/output/merged_final_lncRNAs.gtf)

### Differential Expression Analysis 

![image](https://github.com/course-fish546-2023/zach-lncRNA/blob/main/data/DGE-workflow.png?raw=true)

- [Count Matrix of lncRNAs](https://github.com/course-fish546-2023/zach-lncRNA/blob/main/output/filtered_count_matrix.tsv)

### Projected Endpoint

Endpoint is getting pushed according to how quickly I am able to finish with enough time to prep the final project

-   Original endpoint: Canonical list of lncRNAs for this experiment [complete]
-   New endpoint: Differential expression analysis of lncRNAs (nutrient exposure vs control) with blast results of 22 significantly differentially expressed lncRNAs

### Final Plan

-   Week 6-7: Kallisto count matrix of lncRNAs
-   Week 8-9: DESeq2 to examine lncRNA differential expression based on nurtrient treatment
-   Week 10: figure generation, blast of lncRNAs, and final compendium

### Weekly Log

### Week 09

-   Count matrix filter for only lncRNAs

-   DESeq2 run

-   22 significantly differentially expressed lncRNAs out of \~6000

### Week 08

-   updates to [count matrix code](https://github.com/course-fish546-2023/zach-lncRNA/blob/main/code/09-count-matrix.Rmd)

-   kallisto run to [retrieve count matrix](https://github.com/course-fish546-2023/zach-lncRNA/blob/main/output/count_matrix.isoform.counts.matrix), filter needed

-   worked on Rpub formatting and figure mock-up, [view here](https://rpubs.com/zbengt/1040642)

### Week 07

-   07-scale-up code, with workflow up to original endpoint, fixed and cleaned up

-   Tried using stringtie for count matrix, switching to kallisto

-   R pub for final project

### Progress Tracking

-   [Progress update presentation 04/27](https://rpubs.com/zbengt/1034660)
-   [Project R pub in quarto 05/12](https://rpubs.com/zbengt/1040642)

### 
