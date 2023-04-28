# Long non-coding RNA discovery in _Pocillopora verrucosa_
FISH 546 project repo examining the expression of long non-coding RNAs in coral

### Data
This project uses data from Danielle Becker's experiment exposing colonies of _Pocillopora verrucosa_ to low level nutrient conditions (nitrogen and phosphorous).

RNA-seq data for 16 control (no low level nutrient exposure) and treatment (low level nutrient exposure) colonies.

* [GitHub Repo](https://github.com/hputnam/Becker_E5)
* [RNA-seq data](https://gannet.fish.washington.edu/Atumefaciens/hputnam-Becker_E5/Becker_RNASeq/data/trimmed/)
* [_P. ver_ genome assembly (GFF3 and fasta)](http://pver.reefgenomics.org/download/)
* [_P. ver_ genome assembly GTF](https://gannet.fish.washington.edu/Atumefaciens/20230127-pver-gff_to_gtf/)

### Project Goals
* Identify lncRNAs present within the RNA-seq data
* Create a list of lncRNA transcript IDs for further use in lncRNA-mRNA co-expression and differential expression analysis

### Workflow for identifying lncRNAs in all 32 samples

![image](https://github.com/course-fish546-2023/zach-lncRNA/blob/main/code/workflow.png?raw=true)

### Results
* [List of lncRNA transcript IDs in GTF format](https://github.com/course-fish546-2023/zach-lncRNA/blob/main/output/merged_final_lncRNAs.gtf)

### Future Plans
* Week 6: Kallisto count matrix of lncRNAs
* Week 7-8: lncRNA-mRNA co-expression analysis
* Week 9: DESeq2 to examine lncRNA differential expression based on nurtrient treatment

### Progress Tracking
* [Progress update presentation 04/27](https://rpubs.com/zbengt/1034660)