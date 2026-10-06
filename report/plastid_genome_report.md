# Plastid Genome Characterization Report

### Selected Organism

- **Genus:** *Ocimum*
- **Species:** *Ocimum basilicum*
- **Family:** Lamiaceae
- **Plastid genome accession:** NC_035143.1
- **Genome type:** Complete chloroplast genome
- **Genome length:** 152,407 bp
- **Topology:** Circular

### Question 1. What organism was selected, and what is its plastid genome accession?

The selected organism is *Ocimum basilicum*, a member of the family Lamiaceae. The complete chloroplast genome was obtained from the NCBI Nucleotide/RefSeq database under accession NC_035143.1. The genome is 152,407 bp in length and has a circular topology.

### Question 2. How can you confirm that the sequence is a complete plastid genome rather than a barcode, fragment, or other sequence?

The sequence is identified in NCBI as *Ocimum basilicum* chloroplast, complete genome, with accession NC_035143.1. The NCBI record has a length of 152,407 bp and is described as a complete, full-length chloroplast genome. The sequence also contains numerous annotated plastid genes, including genes involved in photosynthesis, transcription, translation, and other chloroplast functions.

Therefore, the sequence represents a complete chloroplast genome rather than a barcode marker, genome fragment, or nuclear sequence.

### Question 3. What is the overall organization of the plastid genome?

The *Ocimum basilicum* plastid genome follows the typical quadripartite organization found in many plant chloroplast genomes, consisting of a large single-copy (LSC) region, two inverted-repeat (IR) regions, and a small single-copy (SSC) region.

For a published *O. basilicum* plastome using NC_035143.1 as a reference, the reported region sizes were:

| Region | Size |
|---|---:|
| Large single-copy (LSC) | 83,409 bp |
| Small single-copy (SSC) | 17,604 bp |
| Inverted repeat (IR) | 25,697 bp each |

These regions sum to 152,407 bp, matching the length of the NC_035143.1 genome.

### Question 4. How many genes are annotated, and what types of genes are present?

The annotated *Ocimum basilicum* chloroplast genome contains 129 annotated gene features, including:

| Gene type | Number |
|---|---:|
| Protein-coding genes | 84 |
| tRNA genes | 37 |
| rRNA genes | 8 |
| Pseudogenes | 0 |
| Total annotated gene features | 129 |

Some genes occur in two copies because the chloroplast genome contains two inverted-repeat (IR) regions. Genes located within an IR can therefore be duplicated, with one copy occurring in each of the two IR regions.

Examples of duplicated genes in this genome include *ycf2* and *rpl23*, along with several tRNA genes.

### Question 5. Identify at least eight protein-coding genes from different functional groups and explain their functions.

| Gene | Functional group | Biological function |
|---|---|---|
| *psbA* | Photosynthesis | Encodes the D1 protein of Photosystem II |
| *psaA* | Photosynthesis | Encodes a core reaction-center protein of Photosystem I |
| *atpB* | ATP synthesis | Encodes a subunit of chloroplast ATP synthase involved in ATP production |
| *petA* | Electron transport | Encodes cytochrome f, a component of the cytochrome b6f complex |
| *rbcL* | Carbon fixation | Encodes the large subunit of Rubisco |
| *rpoB* | Transcription | Encodes a subunit of the plastid-encoded RNA polymerase |
| *rpl2* | Translation | Encodes ribosomal protein L2 |
| *rps19* | Translation | Encodes ribosomal protein S19 |

The chloroplast genome contains protein-coding genes involved in several important plastid functions. For example, *psbA* and *psaA* are involved in photosynthesis, while *atpB* participates in ATP synthesis and *petA* is involved in photosynthetic electron transport. The *rbcL* gene functions in carbon fixation, while *rpoB* is involved in plastid transcription. The ribosomal protein genes *rpl2* and *rps19* contribute to plastid protein synthesis.

Together, these genes represent several major functional groups within the plastid genome.

### Question 6. What RNA genes and intron-containing genes are present?

The *Ocimum basilicum* plastid genome contains genes for both ribosomal RNAs and transfer RNAs that are important for protein synthesis.

An example of an rRNA gene is the 16S rRNA gene, which forms part of the plastid ribosome. An example of a tRNA gene is *trnH-GUG*, which encodes a tRNA for histidine.

The genome also contains protein-coding genes with introns. These can be identified from their split `join()` annotations in the GenBank record. Examples include *rpoC1* and *atpF*, while *rpl2, ndhA,* and *rps16* are additional examples of intron-containing genes.

These introns are removed during RNA processing to produce mature RNA molecules.

### Question 7. Are there pseudogenes, duplicated genes, or notable gene losses/rearrangements?

No pseudogenes were annotated in the *Ocimum basilicum* chloroplast genome.

Several genes appear in two copies because they are located within the inverted-repeat regions of the plastid genome. Examples include *ycf2*, *rpl23*, and several tRNA genes. These duplicated copies are associated with the normal inverted-repeat structure rather than representing independent gene duplications.

No specific gene losses or major rearrangements were identified from the NC_035143.1 annotation used in this analysis.

### Question 8. What are the main sequence-level observations from the Galaxy analysis?

The GC content of the *Ocimum basilicum* plastid genome is 37.84%, based on Galaxy FASTA Statistics.

The genome is 152,407 bp long and consists of one complete sequence with no gaps or ambiguous N bases.

The Galaxy statistics showed:

| Feature | Result |
|---|---:|
| Number of sequences | 1 |
| Genome length | 152,407 bp |
| GC content | 37.84% |
| Number of gaps | 0 |
| Number of N bases | 0 |
| Minimum length | 152,407 bp |
| Maximum length | 152,407 bp |

One notable structural observation is that several genes occur in two copies because of the inverted-repeat regions, including *ycf2* and *rpl23*.

Another notable observation is that the genome contains many annotated genes involved in photosynthesis, transcription, translation, and other plastid functions, including *psa*, *psb*, *atp*, *pet*, *rbcL*, *rpo*, *rpl*, and *rps* gene groups.

### Question 9. How does the plastid genome compare with the mitochondrial genome?

| Feature | Plastid genome | Mitochondrial genome |
|---|---|---|
| Cellular location | Located inside plastids, including chloroplasts. | Located inside mitochondria. |
| Main biological functions | Mainly photosynthesis and other plastid functions, including transcription and translation. | Mainly cellular respiration and energy production, especially oxidative phosphorylation. |
| Typical genome organization | Usually compact and often circular, with a quadripartite LSC-IR-SSC-IR organization. | Plant mitochondrial genomes are much more variable and can have complex structures and repeats. |
| Relative genome size | Generally small and compact; *O. basilicum* plastid genome is 152,407 bp. | Plant mitochondrial genomes vary greatly and can be much larger. |
| Gene content | Contains genes involved in photosynthesis, transcription, translation, ribosomal functions, and other plastid processes. | Contains genes mainly associated with respiration, oxidative phosphorylation, and mitochondrial protein synthesis. |
| Copy number | Multiple copies can occur within plastids and cells. | Multiple mitochondrial genome copies can occur within mitochondria and cells. |
| Inheritance | Often maternal in plants, but inheritance varies among plant lineages. | Often maternal in plants, but inheritance varies among plant lineages. |
| Recombination/structural change | Generally more structurally conserved, although rearrangements can occur. | Plant mitochondrial genomes can undergo extensive recombination and rearrangement. |
| Mutation/substitution pattern | Generally relatively conserved and useful for evolutionary comparisons. | Can show relatively slow sequence evolution but substantial structural changes and rearrangements. |
| Common research applications | Plant identification, DNA barcoding, phylogenetics, evolution, population history, and studies of organellar inheritance. | Mitochondrial evolution, plant fertility, respiration-related studies, organellar inheritance, and mitochondrial genome evolution. |

### Similarities

1. Both are organellar genomes located outside the nucleus.
2. Both contain DNA and genes required for functions of their respective organelles.
3. Multiple copies of their genomes can occur within cells.
4. Both can show non-Mendelian inheritance; maternal inheritance is common in plants, although inheritance can vary among lineages.
5. Both can be used to study evolutionary history and organellar inheritance.

### Differences

1. Location: Plastid genomes occur in plastids, while mitochondrial genomes occur in mitochondria.
2. Function: Plastid genomes contain many genes associated with photosynthesis and plastid functions, while mitochondrial genomes mainly contain genes associated with respiration and oxidative phosphorylation.
3. Genome organization: Plastid genomes are commonly compact and have a quadripartite organization, whereas plant mitochondrial genomes have much more variable structures.
4. Gene content: Plastid genomes contain photosynthetic, transcriptional, translational, and ribosomal genes, while mitochondrial genomes contain genes mainly related to respiration and mitochondrial functions.
5. Structural evolution: Plastid genomes are generally more structurally conserved, whereas plant mitochondrial genomes can experience extensive recombination and structural rearrangement.

### Question 10. What is the practical value of studying plastid genomes, and what are their limitations compared with nuclear genomes?

Plastid genomes are valuable in plant research because they are relatively small, conserved, and contain many genes that can be compared among plant species.

Plastid genome data can be used for:

- Plant identification
- DNA barcoding
- Phylogenetic analysis
- Evolutionary studies
- Population history
- Studies of organellar inheritance
- Comparison of plant lineages
- Genome structure and gene-content analysis
- Studies of plastid evolution
- Reconstruction of relationships among plant species

Because plastid genomes are much smaller than nuclear genomes, they are generally easier to sequence, assemble, and analyze.

### Limitations of plastid genomes

Compared with the nuclear genome, plastid genomes contain only a small portion of the total genetic information of a plant.

Plastid genomes are therefore limited for:

- Studying nuclear genes
- Investigating complex traits controlled by many nuclear loci
- Examining most nuclear genetic variation
- Studying nuclear sex chromosomes when these are present
- Describing the complete genetic history of an organism

Plastid genomes may also reflect only one organellar inheritance lineage rather than the complete genetic history of an organism.

Therefore, plastid genome data are most useful when combined with nuclear genomic information rather than treated as a replacement for nuclear data.

### Example research questions

**Plastid genome research question:**
- How are different *Ocimum* species evolutionarily related based on their complete chloroplast genomes?

**Nuclear genome research question:**
- Which nuclear genetic variants are associated with differences in complex traits among *Ocimum* populations?

### Advantages of plastid genomes

1. Relatively small and compact genomes.
2. Easier to sequence and assemble than large nuclear genomes.
3. Contain conserved genes useful for comparisons.
4. Useful for plant identification.
5. Useful for phylogenetic studies.
6. Useful for evolutionary analysis.
7. Useful for studying organellar inheritance.
8. Useful for comparing closely related plant species.
9. Can provide information about plastid genome structure and gene content.
10. Can be useful for population and lineage studies.

### Overall conclusion

The *Ocimum basilicum* chloroplast genome is a complete circular plastid genome of 152,407 bp with a GC content of 37.84%. The annotated NC_035143.1 record contains 129 annotated gene features, including 84 protein-coding genes, 37 tRNA genes, and 8 rRNA genes, with no annotated pseudogenes.

The genome contains genes associated with photosynthesis, carbon fixation, electron transport, ATP synthesis, transcription, and translation. The presence of duplicated genes within the inverted-repeat regions and intron-containing genes demonstrates important structural characteristics of the plastid genome.

Overall, plastid genome characterization provides useful information for understanding plant genome organization, gene function, evolutionary relationships, and organellar inheritance. However, plastid genomes represent only a small portion of a plant's total genetic information, so nuclear genomic data remain important for studying the broader genetic basis of plant traits and diversity.

# Galaxy Analysis

The complete *Ocimum basilicum* chloroplast FASTA sequence was uploaded to Galaxy and analyzed using FASTA Statistics.

The Galaxy analysis produced the following results:

- Number of sequences: 1
- Genome length: 152,407 bp
- GC content: 37.84%
- Number of gaps: 0
- Number of ambiguous N bases: 0

The Galaxy screenshot is included in the repository under:

`figures/01_galaxy_statistics.png`

# Genome Summary

| Characteristic | Result |
|---|---|
| Genus | *Ocimum* |
| Species | *Ocimum basilicum* |
| Family | Lamiaceae |
| Accession | NC_035143.1 |
| Genome type | Chloroplast/plastid |
| Genome status | Complete |
| Genome length | 152,407 bp |
| Topology | Circular |
| GC content | 37.84% |
| Annotated gene features | 129 |
| Protein-coding genes | 84 |
| tRNA genes | 37 |
| rRNA genes | 8 |
| Annotated pseudogenes | 0 |

# Data Source

The complete chloroplast genome sequence was retrieved from the NCBI Nucleotide/RefSeq database:

NCBI Accession: NC_035143.1  
Organism: *Ocimum basilicum*  
Sequence description: *Ocimum basilicum* chloroplast, complete genome.

The annotated GenBank record used for the analysis is stored in the repository under:

`data/NC_035143.1_Ocimum_basilicum.gb`

# Reproducibility

The analysis can be reproduced by downloading the complete NC_035143.1 *Ocimum basilicum* chloroplast genome from NCBI, uploading the FASTA sequence to Galaxy, and running FASTA Statistics.

The annotated GenBank record, Galaxy results, screenshot, and analysis summaries are included in this repository.

# Student Information

**Name:** Ann Marielle U. Dael

**Course and Section:** BS Biology (III) - Section A

**Date Retrieved:** September 29, 2026

**Galaxy History:** Plastid_Ocimum_Dael

**GitHub Repository:** https://github.com/annmarielledael/cmb-plastid-genome-Ocimum-Dael
