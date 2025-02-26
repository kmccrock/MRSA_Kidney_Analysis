# MRSA_Kidney_Analysis
Spatial Transcriptomic Analysis of MRSA Infected Mouse Kidneys

Kyle McCrocklin (Indiana University Indianapolis), Dr. Takashi Hato (Indiana University Indianapolis), Jered Myslinski (Indiana University Indianapolis), Dr. Juexin Wang (Indiana University Indianapolis)

Methicillin-resistant Staphylococcus aureus (MRSA) is a bacterium that causes infections in mammal organs, which are usually difficult to treat due to its resistance to many common antibiotics. MRSA-related infection commonly occurs in hospitals and nursing homes, which makes it a significant public health issue. In this study, spatial transcriptomics is used to investigate the behavior of MRSA infection in mouse kidneys. The mice were injected with 5×10⁷ colony forming units of USA300 strain MRSA via the tail vein. Tissues were harvested on either day 2 or day 4 after injection and sequenced on the 10X Visium platform. 43 additional custom MRSA probes were included to identify spots with high levels of MRSA infection. The tissue and immune responses at each MRSA-infected location were compared between the 2 day versus 4 day infection times as well as across two kidney regions, the renal medulla and the cortex. Comprehensive computational approaches suggest that MRSA infection spreads from the renal medulla to the cortex, including trajectory/pseudotime, cell-cell communication, gene expression correlation, differential expression analysis, spatially variable gene analysis, and gene ontology/pathway analysis. These results are consistent with the expected immune response in the kidney caused by MRSA infection. 

This repository currently contains code for the COMMOT cell-cell communication analysis. The R notebook loads Seurat objects and extracts relevant data. The Python notebook runs the COMMOT analysis and generates cell-cell communication trajectory plots. 

It also contains code for the Monocle 3 pseudotime/trajectory analysis in notebook form.

S2 and A2 are both the same "day 2" sample. S4 and A4 are the same "day 4" sample.

The S and A refer to "standard" and "achromopeptidase". We compared the effects of probe penetration between the 10X default cell permeabilization reagent (standard) and achromopeptidase. No difference was found.
