# Long non-coding RNA discovery in *Pocillopora verrucosa*

FISH 546 project repo examining the expression of long non-coding RNAs in coral

### Data

This project uses data from Danielle Becker's experiment exposing colonies of *Pocillopora verrucosa* to low level nutrient conditions (nitrogen and phosphorous).

RNA-seq data for 16 control (no low level nutrient exposure) and treatment (low level nutrient exposure) colonies.

-   [GitHub Repo](https://github.com/hputnam/Becker_E5)
-   [RNA-seq data](https://gannet.fish.washington.edu/Atumefaciens/hputnam-Becker_E5/Becker_RNASeq/data/trimmed/)
-   [*P. ver* genome assembly (GFF3 and fasta)](http://pver.reefgenomics.org/download/)
-   [*P. ver* genome assembly GTF](https://gannet.fish.washington.edu/Atumefaciens/20230127-pver-gff_to_gtf/)

### Project Goals

-   Identify lncRNAs present within the RNA-seq data
-   Create a list of lncRNA transcript IDs for further use in lncRNA-mRNA co-expression and differential expression analysis

### Workflow for identifying lncRNAs in all 32 samples

![image](https://github.com/zbengt/zbengt.github.io/blob/master/assets/img/lncRNA-disc.png?raw=true)

### Results

-   [List of lncRNA transcript IDs in GTF format](https://github.com/course-fish546-2023/zach-lncRNA/blob/main/output/merged_final_lncRNAs.gtf)

### Projected Endpoint

Endpoint is getting pushed according to how quickly I am able to finish with enough time to prep the final project

-   Original endpoint: Canonical list of lncRNAs for this experiment [complete]
-   New endpoint: Differential expression analysis of lncRNAs (nutrient exposure vs control)

### Future Plans

-   Week 6-7: Kallisto count matrix of lncRNAs
-   Week 8: DESeq2 to examine lncRNA differential expression based on nurtrient treatment
-   Week 9: lncRNA-mRNA co-expression analysis

### Progress Tracking

-   [Progress update presentation 04/27](https://rpubs.com/zbengt/1034660)
-   [Project R pub in quarto 05/12](https://rpubs.com/zbengt/1040642)

### Completed this week...

-   07-scale-up code, with workflow up to original endpoint, fixed and cleaned up

-   Tried using stringtie for count matrix, switched to kallisto

-   R pub for final project
