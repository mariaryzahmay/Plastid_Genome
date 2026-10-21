# Plastid_Genome

Characterization and analysis of the complete chloroplast genome of *Rosa chinensis* using NCBI, Galaxy, and GitHub documentation.

---

# Characterization of the Plastid Genome of *Rosa chinensis*

## Student Information

**Student Name:** Maria Ryzah May I. Vertudazo  
**Course:** BS Biology  
**Subject:** Cell and Molecular Biology

## Selected Organism

- **Genus:** *Rosa*
- **Species:** *Rosa chinensis*
- **Family:** Rosaceae

## Genome Source

- **Database:** NCBI RefSeq / NCBI Nucleotide
- **Accession/Version:** `NC_065867.1`
- **Genome Type:** Complete chloroplast genome
- **Genome Size:** 156,591 bp
- **Topology:** Circular DNA
- **NCBI Source:** https://www.ncbi.nlm.nih.gov/nuccore/NC_065867.1


## Analysis Summary

- **Genome Retrieval Date:** October 3, 2026
- **NCBI Accession:** `NC_065867.1`
- **Galaxy History:** `Plastid_Rosa_Vertudazo`
- **Galaxy Tool Used:** FASTA Statistics
- **Galaxy History Link:** https://usegalaxy.org/u/vertudazo01/h/plastid-rosa-chinensis
- **FASTA File:** `Rosa_chinensis_NC_065867.1.fasta`
- **Annotated Genome File:** `Rosa_chinensis_NC_065867.1.gb`

**Galaxy results to insert:**

- Genome length: 156,591 bp
- Number of sequence records: 1
- GC content: 37.24%
- LSC length: 85,737 bp
- SSC length: 18,766 bp
- IR length:26,044 bp
- Total annotated genes: 
- Protein-coding genes: 79 unique
- tRNA genes: 30 unique
- rRNA genes: 4 unique
- Pseudogenes: 0 

---

# Complete Plastid Genome Characterization Report

## Question 1. Give the full scientific name, family, NCBI accession/version, database source, and complete plastid-genome size of your selected organism.

The selected organism is *Rosa chinensis*, a flowering plant belonging to the family Rosaceae. Its complete chloroplast genome was retrieved from NCBI under accession `NC_065867.1`. The sequence is reported as circular DNA with a length of 156,591 base pairs. The NCBI record serves as the primary source for the genome sequence and its annotations.

**Source:** https://www.ncbi.nlm.nih.gov/nuccore/NC_065867.1

## Question 2. What evidence shows that the sequence is a complete plastid/chloroplast genome rather than a barcode marker, genome fragment, or nuclear sequence?

The NCBI record identifies the sequence as a complete chloroplast genome of *Rosa chinensis*. Its reported length of 156,591 bp and circular topology are consistent with a complete plant chloroplast genome. The annotated record also contains genome features such as genes and RNA-coding regions, rather than representing only a single barcode marker such as *rbcL* or *matK*. The accession and genome description should be retained as evidence that the correct sequence was selected.

## Question 3. Describe the overall organization of the plastid genome. Does it contain the common LSC-IR-SSC-IR arrangement? Give the sizes of these regions when available.

Many flowering-plant chloroplast genomes have a quadripartite organization consisting of one large single-copy region (LSC), one small single-copy region (SSC), and two inverted-repeat regions (IRa and IRb). The two inverted repeats contain duplicated copies of some genes and separate the LSC and SSC regions. This organization is a common feature of angiosperm chloroplast genomes.

| Region | Length |
|---|---:|
| LSC | 85,737 bp |
| SSC | 18,766 bp |
| IRa | 26,044bp |
| IRb |  26,044bp |
| Total | 156,591 bp |


## Question 4. Summarize the annotated gene content: total genes, protein-coding genes, tRNA genes, rRNA genes, and pseudogenes. Explain why genes located in the inverted-repeat regions may appear in two copies.

The chloroplast genome contains genes involved in photosynthesis, gene expression, protein synthesis, and other plastid functions. Its annotation includes protein-coding sequences (CDS), transfer RNA genes (tRNA), and ribosomal RNA genes (rRNA). The exact number of genes in each category must be recorded from the selected RefSeq annotation.

| Gene category | Count in `NC_065867.1` |
|---|---:|
| Total annotated genes | 113 unique |
| Protein-coding genes/CDS | 79 unique |
| tRNA genes | 30 unique|
| rRNA genes | 4 unique |
| Pseudogenes | 0 |

Genes in the inverted-repeat regions may occur in two copies because the IRa and IRb regions contain corresponding duplicated DNA sequences. These copies can include protein-coding genes, tRNA genes, and rRNA genes. Therefore, the total number of annotated gene copies may differ from the number of unique gene types. The method used to count genes should be stated clearly.

## Question 5. Choose at least eight protein-coding plastid genes from different functional groups. List each gene and briefly explain its biological function.

The following table provides examples of chloroplast protein-coding genes and their general functions. Confirm each gene in the selected GenBank annotation before including it as a verified feature of this genome.

| Gene | Functional group | Biological function |
|---|---|---|
| *psaA* | Photosystem I | Encodes a core protein of photosystem I involved in light-driven electron transfer. |
| *psbA* | Photosystem II | Encodes the D1 reaction-center protein of photosystem II. |
| *atpB* | ATP synthase | Encodes a subunit of the ATP synthase complex involved in ATP production. |
| *petB* | Cytochrome b6f complex | Encodes a component of the complex that transfers electrons during photosynthesis. |
| *rbcL* | Carbon fixation | Encodes the large subunit of Rubisco, an enzyme involved in carbon dioxide fixation. |
| *rpoB* | RNA polymerase | Encodes a subunit of the plastid RNA polymerase involved in transcription. |
| *rps12* | Ribosomal proteins | Encodes a protein component of the small ribosomal subunit. |
| *rpl16* | Ribosomal proteins | Encodes a protein component of the large ribosomal subunit. |
| *ndhB* | NADH dehydrogenase-like complex | Encodes a component of the chloroplast NDH complex, which participates in photosynthetic electron transport. |
| *matK* | RNA processing | Encodes a maturase associated with the splicing of certain group II introns. |


## Question 6. Identify important RNA and RNA-processing features. Include the rRNA genes, examples of tRNA genes, and at least two genes with introns if present in your genome.

Chloroplast genomes contain RNA genes that support protein synthesis. Ribosomal RNA genes form part of the plastid ribosome, while transfer RNA genes carry amino acids to the ribosome during translation. Common chloroplast RNA gene annotations include the *rrn* and *trn* families.


| Feature | Observation in the selected genome |
|---|---|
| rRNA genes | rrn16S—-102177..103667 and complement 138662..14001152 |
| tRNA genes |trnH-GUG— 4..77 |
| First gene with an intron | trnK-UUU—1762..4222 |
| Second gene with an intron |rps16— 5293..6166  |
| Other RNA-processing features | matK— 1984..3495|

intron coordinates from the join statements [ end of exon 1 + 1 to start of exon 2 - 1 ] 

## Question 7. Describe any pseudogenes, gene losses, duplications, rearrangements, or other unusual features reported for your plastid genome. If none are reported, state this clearly.

No gene loss, pseudogene, rearrangement or other usual structural feature was identified in the GenBank annotation of NC_065867.1. The genes set appeared complete when compared with a typical angiosperm chloroplast gene set. 

## Question 8. What is the GC content of your plastid genome? Based on your Galaxy results and annotation, describe two other notable sequence or structural observations.
The GC content of the Rosa chinensis chloroplast genome is approximately 37.24%. 

| Measurement | Result |
|---|---|
| Genome length | 156,591 bp (NCBI record; verify Galaxy output) |
| GC content | Approximately 37.24% in published Rosa chinensis chloroplast genome data |
| Number of sequence records | 1 sequence   |
| Observation 1 | The chloroplast genome has four-region structure, one large single-copy region, one small single-copy region, and two inverted repeat regions.  |
| Observation 2 | The annotation includes gene with introns, such as trnK-UUU and rps16. Genes may also be duplicated in the inverted repeat regions, a common feature of chloroplast genomes. |


## Question 9. Compare plastid and mitochondrial genomes. Give at least five similarities and five differences, considering location, biological role, inheritance, genome organization, gene content, copy number, and evolutionary behavior.

Plastid and mitochondrial genomes are both organellar genomes in plant cells. They retain genes associated with organelle function and provide useful information for evolutionary and comparative studies. However, they differ in their main biological roles, typical genome organization, gene content, and patterns of genome evolution.

### Similarities

1. Both are located in organelles rather than being part of the main nuclear chromosomes.
2. Both contain DNA and genes that support organelle function.
3. Both generally rely on the nucleus for many proteins required for organelle maintenance and activity.
4. Both can be inherited through the parent or parents that contribute the relevant organelles; inheritance patterns vary by species.
5. Both have evolved from bacterial ancestors according to the endosymbiotic theory.
6. Both can be used in evolutionary, phylogenetic, and population-genetic research.

### Differences

1. **Main function:** Plastids, especially chloroplasts, carry out photosynthesis and related metabolic functions. Mitochondria primarily support cellular respiration and ATP production.
2. **Genome organization:** Many flowering-plant chloroplast genomes have a compact, circular genome with LSC, SSC, and two IR regions. Plant mitochondrial genomes have more variable structures and can contain complex arrangements and repeated sequences.
3. **Gene content:** Chloroplast genomes commonly contain photosynthesis-related genes, whereas mitochondrial genomes contain genes associated with respiration, oxidative phosphorylation, and organelle gene expression.
4. **Genome size:** Chloroplast genomes in many land plants are relatively compact. Plant mitochondrial genomes vary greatly in size and may be much larger than the chloroplast genome despite encoding fewer genes.
5. **Evolutionary behavior:** Chloroplast genomes often show relatively conserved gene order in many plant groups. Plant mitochondrial genomes can undergo frequent structural changes and recombination involving repeated sequences.
6. **Inheritance:** Chloroplast inheritance is often maternal in angiosperms, but exceptions occur. Plant mitochondrial inheritance is also frequently maternal, although inheritance varies across taxa.
7. **Copy number:** Both organelles can contain multiple genome copies per cell, but their copy numbers vary with tissue, cell type, developmental stage, and physiological condition.


## Question 10. Explain the practical value of plastid genomes in research. List advantages compared with the nuclear genome, including nuclear sex chromosomes where applicable, and explain important limitations. Give one research question for which plastid data would be useful and one for which nuclear genomic data would be more appropriate.

Plastid genomes are useful because they provide a relatively compact source of genetic information that can be sequenced, annotated, compared, and used to investigate evolutionary relationships. Their conserved genes and variable regions can help researchers identify species, examine genetic diversity, trace some patterns of ancestry, and investigate relationships among plant lineages.

### Advantages of plastid-genome analysis

1. **Compact size:** A plastid genome is generally much smaller than a plant's complete nuclear genome, making it easier to analyze.
2. **Accessible sequence data:** Complete chloroplast genomes are available for many plant species in public databases.
3. **Useful conserved genes:** Conserved plastid genes support comparisons among related plants.
4. **Species identification:** Selected plastid sequences can serve as molecular markers for plant identification.
5. **Phylogenetic analysis:** Plastid sequences can help reconstruct evolutionary relationships.
6. **Plant diversity research:** Plastid variation can be used to investigate genetic differences among populations and species.
7. **Comparative genomics:** Genome organization and gene content can be compared across plant lineages.
8. **Organellar history:** Plastid data can help investigate organelle evolution and endosymbiotic history.
9. **Genome annotation:** The relatively compact genome makes it practical to examine genes, introns, RNA genes, and repeated regions.
10. **Reproducibility:** Publicly available reference sequences allow other researchers to repeat analyses using the same accession.

### Limitations of plastid genomes

1. A plastid genome represents only a small portion of the total genetic information in a plant.
2. Plastid inheritance may reflect only one parental lineage in species with uniparental inheritance.
3. Plastid gene histories may differ from species histories because of hybridization, introgression, or other evolutionary processes.
4. Many plant traits are influenced by nuclear genes, environmental conditions, or interactions between nuclear and organellar genes.
5. Plastid genomes cannot provide a complete picture of nuclear gene expression or nuclear chromosome structure.
6. Plastid data alone are insufficient to explain most complex traits or the full genetic basis of adaptation.
7. Chloroplast inheritance and structure can vary across species, so assumptions should be checked for each study.

### Research question suited to plastid data

“How are closely related *Rosa* species related evolutionarily, based on their complete chloroplast genome sequences?”


### Research question suited to nuclear genomic data

“Which nuclear genetic variants contribute to differences in flower color and other inherited ornamental traits among rose cultivars?”

---

# Plastid Versus Mitochondrial Genome Comparison

| Feature | Plastid genome | Mitochondrial genome |
|---|---|---|
| Cellular location | Plastids, including chloroplasts | Mitochondria |
| Main biological functions | Photosynthesis and other plastid metabolic processes | Cellular respiration and ATP production |
| Typical genome organization | Often a circular molecule with LSC, SSC, and two IR regions in flowering plants | Highly variable in plants; can have complex structures and repeated sequences |
| Relative genome size | Often compact in land plants | Highly variable; plant mitochondrial genomes may be much larger |
| Gene content | Commonly includes photosynthesis, transcription, translation, and RNA genes | Commonly includes respiration-related genes and genes for organelle gene expression |
| Copy number | Multiple copies can occur per cell; varies by tissue and cell type | Multiple copies can occur per cell; varies by tissue and cell type |
| Inheritance | Often maternal in angiosperms, but exceptions occur | Often maternal in angiosperms, but exceptions occur |
| Recombination / structural change | Gene order is often conserved, though rearrangements and IR-boundary changes occur | Recombination and structural rearrangements are common in many plant mitochondrial genomes |
| Mutation / substitution pattern | Rates vary by lineage and region; often useful for phylogenetic comparisons | Rates and patterns vary by lineage and genomic region |
| Common research applications | Plant identification, phylogenetics, population history, comparative plastome analysis | Studies of respiration-related genes, organelle evolution, cytoplasmic inheritance, and mitochondrial genome structure |

---

# Galaxy Workflow

## History and uploaded dataset

- **Galaxy History Name:** `Plastid_Rosa_Vertudazo`
- **Input dataset:** `Rosa_chinensis_NC_065867.1_FASTA`
- **Tool:** FASTA Statistics 
- **Input accession:** `NC_065867.1`

## Workflow steps

1. Downloaded the complete chloroplast sequence from NCBI in FASTA format.
2. Opened a personal Galaxy account and created a new history for the plastid genome activity.
3. Uploaded the FASTA file and confirmed the dataset format.
4. Ran the available FASTA-statistics tool.
5. Recorded the genome length, number of sequence records, and GC content when available.
6. Compared the Galaxy sequence length with the NCBI record.
7. Examined the annotated GenBank record to investigate genome regions and gene features.
8. Documented the results and analysis steps in GitHub.

---

# Conclusion

The complete chloroplast genome of *Rosa chinensis* provides a useful example for learning how organellar DNA is retrieved, characterized, and interpreted using public bioinformatics resources. NCBI provides the reference sequence and annotation, while Galaxy supports basic sequence-statistics analysis. Examining the genome's structural regions and annotated genes helps explain how plastid genomes contribute to photosynthesis, gene expression, and evolutionary research. Documenting the steps and results in GitHub makes the analysis easier to review and reproduce.

---

# References

National Center for Biotechnology Information. (n.d.). *Rosa chinensis chloroplast, complete genome* (NC_065867.1). NCBI Nucleotide. https://www.ncbi.nlm.nih.gov/nuccore/NC_065867.1

Zhang, & Zhu. (2019). Characterization of the complete chloroplast genome of Chinese rose, *Rosa chinensis* (Rosaceae: Rosa). *Mitochondrial DNA Part B: Resources*. https://pmc.ncbi.nlm.nih.gov/articles/PMC7706574/

Galaxy Project. (n.d.). *Galaxy platform*. https://usegalaxy.org/

GitHub. (n.d.). *GitHub documentation*. https://docs.github.com/
