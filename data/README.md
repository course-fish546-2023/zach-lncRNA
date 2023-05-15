# Data

This project uses data from Danielle Becker's experiment exposing colonies of *Pocillopora verrucosa* to low level nutrient conditions (nitrogen and phosphorous).

RNA-seq data for 16 control (no low level nutrient exposure) and treatment (low level nutrient exposure) colonies.

Reference and data can be found [here](https://osf.io/uayvk/)

### Sources

-   [GitHub Repo](https://github.com/hputnam/Becker_E5)
-   [RNA-seq data](https://gannet.fish.washington.edu/Atumefaciens/hputnam-Becker_E5/Becker_RNASeq/data/trimmed/)
-   [*P. ver* genome assembly (GFF3 and fasta)](http://pver.reefgenomics.org/download/)
-   [*P. ver* genome assembly GTF](https://gannet.fish.washington.edu/Atumefaciens/20230127-pver-gff_to_gtf/)

Ultimately decided to go with reads already processed through QC and trimmed. Preliminary HISAT alignments show approximalry 15-20% higher mapping when using trimmed data compared to raw reads.

This data can be found [here](https://gannet.fish.washington.edu/Atumefaciens/hputnam-Becker_E5/Becker_RNASeq/data/trimmed/).

### Data Storage

The data from the previous link are downloaded on Raven, which is the primary maching I will be using to complete this project.

### Context
"We experimentally enriched corals with dissolved inorganic nitrogen and phosphate for 15 months on an oligotrophic fore reef in Mo'orea, French Polynesia. Our physiological analysis of coral fragments and thermal performance show that in an oligotrophic fore reef environment, nutrient enrichment can cause changes in coral endosymbiont physiology that increase the performance of the coral holobiont. To assess the molecular underpinnings of the enhanced thermal performance due to chronic low nutrient enrichment, we assessed gene expression with RNASeq and the potential for gene expression regulation through whole genome bisulfite sequencing (WGBS). Sequencing of mtORF for 32 samples of Pocillopora spp. (n=16 per treatment) identified three possible species (Pocillopora meandrina, Pocillopora eydouxi, and an unidentified variant). To delineate between Pocillopora meandrina and Pocillopora eydouxi we will be using a new set of primers following methods found in Johnston et al. 2018."
