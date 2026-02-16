# Comparative Genome Analysis of Zymomonas mobilis and Gracilibacillus spp. for Antimicrobial Resistance

## Objective
To annotate and compare the genomes of four strains each of *Zymomonas mobilis* and *Gracilibacillus* spp., with a focus on antimicrobial resistance (AMR) genes, resistance mechanisms, and hypothetical protein characterization.

## Rationale
- *Zymomonas mobilis* is an industrial ethanologen used in biofuel production, but its fermentation process can be hindered by microbial contaminants. Understanding its intrinsic and acquired AMR genes helps in designing more robust industrial strains.
- *Gracilibacillus* species are halotolerant bacteria thriving in extreme saline environments. Such niches are hotspots for novel resistance mechanisms and mobile genetic elements, making them relevant to the One Health approach to antibiotic resistance.

## Materials and Methods
- **Genome Sequences**: Retrieved from NCBI using GenBank accession numbers for four strains of *Zymomonas mobilis* (ZM401, CP4, ZM4 = ATCC 31821, subsp. pomaceae) and four strains of *Gracilibacillus* (G. salitolerans, G. caseinolyticus, G. salinarum, G. sp. Marseille-P2481).
- **Genome Annotation**: Performed using Prokka (via Proksee) to predict genes and their functions.
- **AMR Gene Identification**: The CARD Resistance Gene Identifier (RGI) was used to detect antimicrobial resistance genes and classify them by resistance mechanism and gene family.
- **Hypothetical Protein Analysis**: 45 hypothetical proteins per strain (360 total) were analyzed using:
  - InterPro: for functional domains and families.
  - STRING: for protein-protein interaction networks.
  - CELLO: for subcellular localization prediction.
- **Data Analysis**: Venn diagrams were constructed to compare resistance mechanisms and gene families across strains. Pie charts summarized hypothetical protein annotations. Genome maps with ORF annotations were generated via Proksee.

## Results

### 1. Antimicrobial Resistance Genes
- **Resistance Mechanisms**:
  - All eight strains possess multiple resistance mechanisms, including antibiotic efflux, antibiotic inactivation, target alteration, target replacement, and reduced permeability.
  - *Zymomonas* strains share a core set of mechanisms (efflux, inactivation, target alteration, target replacement) with minor variations.
  - *Gracilibacillus* shows a dichotomy: *G. caseinolyticus* and *G. marseille* exhibit all six major mechanisms, while *G. salitolerans* and *G. salinarum* have only a few (primarily efflux and target alteration).

- **AMR Gene Families**:
  - Common families across all strains: ABC efflux pumps, Major Facilitator Superfamily (MFS) efflux pumps, Resistance-Nodulation-Cell Division (RND) efflux pumps, OXA beta-lactamase, tetracycline resistance proteins (ribosomal protection and inactivation), and Erm 23S rRNA methyltransferases.
  - Additional families in resistant strains: glycopeptide resistance gene clusters, macrolide phosphotransferases, and trimethoprim-resistant dihydrofolate reductase.

### 2. Open Reading Frames (ORFs)
- Genome maps for all eight strains were generated using Proksee, showing the distribution and density of ORFs. Maps highlight coding sequences, tRNA, rRNA, and other genomic features.

### 3. Hypothetical Protein Annotation
- Among 360 hypothetical proteins analyzed:
  - Approximately 40% were assigned putative functions via InterPro (e.g., transporters, transcriptional regulators, enzymes involved in stress response).
  - STRING analysis revealed potential interaction networks with known proteins, suggesting roles in membrane integrity, efflux, and metabolic pathways.
  - Subcellular localization predicted by CELLO: majority were cytoplasmic, with significant fractions localized to the membrane (especially in *Gracilibacillus*), and a small number predicted as extracellular.

### 4. Key Findings
- **Zymomonas mobilis**:
  - Robust multidrug efflux systems (RND, ABC, MFS) are primary defenses against lignocellulosic inhibitors and antibiotics.
  - TetR and MarR family transcription factors regulate efflux pump expression.
  - Membrane reinforcement via hopanoids and fatty acid remodeling under ethanol stress contributes to tolerance.

- **Gracilibacillus**:
  - Salt stress co-selects for antibiotic resistance genes (ARGs) due to genetic linkage between salt-tolerance genes (e.g., K+ uptake, osmolyte transporters) and ARGs on mobile genetic elements.
  - Mobile genetic elements (plasmids, transposons, integrons) are abundant in resistant strains, facilitating horizontal gene transfer.
  - The presence of clinically relevant resistance genes (OXA, vancomycin clusters, MCR) in environmental strains underscores the role of natural environments as resistance reservoirs.

### 5. Discussion
- Environmental bacteria harbor a diverse array of ARGs, many identical to those found in clinical pathogens, indicating potential for horizontal transfer.
- The contrast between the conserved core resistome in *Zymomonas* and the variable accessory resistome in *Gracilibacillus* reflects different evolutionary strategies: intrinsic adaptation vs. niche-specific acquisition.
- These findings highlight the importance of monitoring environmental microbiomes under the One Health framework to predict and mitigate the spread of antibiotic resistance.

## Repository Structure
