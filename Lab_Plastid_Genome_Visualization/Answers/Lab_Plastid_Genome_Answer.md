# Plastid Genome Characterization Report: *Tagetes erecta*

**Name:** Jerrick Paul T. Tayos
**Course:** Cell and Molecular Biology  
**Section:** B  
**Date:** October 9, 2026  

---

## Questions for the Student Report

### 1. Give the full scientific name, family, NCBI accession/version, database source, and complete plastid-genome size of your selected organism.

* **Scientific Name:** *Tagetes erecta* L. (African marigold)
* **Family:** Asteraceae
* **NCBI Accession/Version:** MN462588.1
* **Database Source:** NCBI Nucleotide / RefSeq
* **Complete Plastid-Genome Size:** 152,056 bp

---

### 2. What evidence shows that the sequence is a complete plastid/chloroplast genome rather than a barcode marker, genome fragment, or nuclear sequence?

The NCBI record explicitly identifies **MN462588.1** as a **complete chloroplast genome** of *Tagetes erecta*. The sequence spans 152,056 bp and contains a full set of 132 annotated gene features (87 CDS, 37 tRNAs, 8 rRNAs). This structural integrity and comprehensive gene complement are characteristic of intact land plant plastomes, setting it apart from short single-gene barcode markers (such as *rbcL* or *matK*, which are only ~1.4 kb) or fragmented genomic reads. Furthermore, the Galaxy statistics tool confirmed a single contiguous sequence record of **152,056 bp** with **0 gaps** ($N\text{ count} = 0$), verifying its completeness.

---

### 3. Describe the overall organization of the plastid genome. Does it contain the common LSC-IR-SSC-IR arrangement? Give the sizes of these regions when available.

Yes, the *Tagetes erecta* plastid genome exhibits the classical circular quadripartite structure comprising a **Large Single-Copy (LSC)** region, a **Small Single-Copy (SSC)** region, and two **Inverted Repeat ($\text{IR}_\text{a}$ and $\text{IR}_\text{b}$)** regions.

| Region | Size (bp) |
| :--- | :--- |
| **Large Single-Copy (LSC)** | ~83,800 bp |
| **Inverted Repeat A ($\text{IR}_\text{a}$)** | ~25,000 bp |
| **Small Single-Copy (SSC)** | ~18,256 bp |
| **Inverted Repeat B ($\text{IR}_\text{b}$)** | ~25,000 bp |
| **Total Genome Size** | **152,056 bp** |

The overall structural arrangement is **LSC–$\text{IR}_\text{a}$–SSC–$\text{IR}_\text{b}$**. The two identical Inverted Repeat regions contain duplicated sequences, resulting in double copies of all genes located within them.

---

### 4. Summarize the annotated gene content: total genes, protein-coding genes, tRNA genes, rRNA genes, and pseudogenes. Explain why genes located in the inverted-repeat regions may appear in two copies.

The annotated *Tagetes erecta* plastid genome contains **132 total gene features**:

| Feature | Count |
| :--- | :--- |
| **Total Annotated Genes** | 132 |
| **Protein-Coding Genes (CDS)** | 87 |
| **tRNA Genes** | 37 |
| **rRNA Genes** | 8 |
| **Pseudogenes** | 1 |

The single annotated pseudogene is a truncated fragment of **ycf1** located at the $\text{IR}_\text{b}$/SSC boundary.

**Explanation for IR Gene Duplication:**  
The Inverted Repeat regions ($\text{IR}_\text{a}$ and $\text{IR}_\text{b}$) are physically identical, duplicated nucleotide sequences positioned on opposite sides of the circular chromosome. Because these genomic segments are duplicated, any gene located within an IR region is physically encoded twice in the genome, resulting in two identical copies per plastome.

---

### 5. Choose at least eight protein-coding plastid genes from different functional groups. List each gene and briefly explain its biological function.

| Gene | Functional Group | Biological Function |
| :--- | :--- | :--- |
| **psaA** | Photosystem I | Encodes a core reaction-center protein of Photosystem I involved in light-driven electron transport. |
| **psbA** | Photosystem II | Encodes the D1 reaction-center protein of Photosystem II, essential for light absorption and photosynthetic water oxidation. |
| **atpA** | ATP Synthase | Encodes the alpha subunit of the chloroplast ATP synthase complex responsible for generating ATP. |
| **petA** | Cytochrome $\text{b}_6/\text{f}$ Complex | Encodes cytochrome f, which mediates electron transfer between Photosystem II and Photosystem I. |
| **rbcL** | Carbon Fixation | Encodes the large subunit of RuBisCO, the primary enzyme catalyzing photosynthetic $\text{CO}_2$ fixation. |
| **rpoA** | Transcription | Encodes the alpha subunit of plastid-encoded RNA polymerase (PEP) involved in gene transcription. |
| **rps12** | Translation | Encodes small ribosomal subunit protein S12, essential for organellar protein synthesis (undergoes trans-splicing). |
| **clpP** | Protein Processing | Encodes the proteolytic subunit of the ATP-dependent Clp protease complex involved in plastid protein turnover. |

---

### 6. Identify important RNA and RNA-processing features. Include the rRNA genes, examples of tRNA genes, and at least two genes with introns if present in your genome.

* **rRNA Genes:** The genome encodes four distinct ribosomal RNA types: **rrn4.5, rrn5, rrn16, and rrn23**. Because all four reside within the Inverted Repeat regions, each is present in two copies (totaling 8 rRNA genes).
* **tRNA Genes:** There are **37 tRNA genes** supplying transfer RNAs for all standard amino acids. Examples include *trnK-UUU*, *trnL-UAA*, *trnH-GUG*, *trnI-GAU*, *trnM-CAU*, and *trnfM-CAU*.
* **Intron-Containing Genes:** Several genes contain non-coding introns that must be removed via RNA splicing to generate functional mature transcripts. Key examples include:
  1. **clpP** and **ycf3** (each contain two introns).
  2. **atpF**, **petB**, and **rps12** (each contain a single intron).

---

### 7. Describe any pseudogenes, gene losses, duplications, rearrangements, or other unusual features reported for your plastid genome. If none are reported, state this clearly.

* **Pseudogenes:** One annotated pseudogene fragment of **ycf1** is present at the junction of $\text{IR}_\text{b}$ and SSC, resulting from incomplete repetition at the boundary of the inverted repeat.
* **Gene Duplications:** Duplications are confined to the **Inverted Repeat regions**, where all residing genes (including all 4 rRNA species and several tRNA genes) exist as two identical functional copies.
* **Structural Rearrangements:** The *Tagetes erecta* plastid genome retains the standard, highly conserved quadripartite structure characteristic of the Asteraceae family without major inversions or gene locus transpositions.

---

### 8. What is the GC content of your plastid genome? Based on your Galaxy results and annotation, describe two other notable sequence or structural observations.

The overall GC content of the *Tagetes erecta* plastid genome is **37.37%** (calculated via Galaxy `Fasta Statistics`).

**Two Notable Observations:**
1. **Base Composition & Sequence Integrity:** According to Galaxy statistics, the 152,056 bp genome contains zero gaps ($N\text{ count} = 0$), with an AT-rich sequence overall (Adenine: 47,465 bp; Thymine: 47,826 bp, making up over 62% of the total base pairs).
2. **GC Content Variation & Trans-splicing:** GC content is unevenly distributed across genomic regions—rRNA genes in the IRs exhibit a noticeably higher GC percentage (~50–55%) compared to AT-rich intergenic spacers. Additionally, the ribosomal protein gene **rps12** exhibits trans-splicing, where its 5' exon located in the LSC region is spliced together with 3' exons situated inside the IR regions.

---

### 9. Compare plastid and mitochondrial genomes. Give at least five similarities and five differences, considering location, biological role, inheritance, genome organization, gene content, copy number, and evolutionary behavior.

#### Similarities
1. Both reside inside organellar compartments within plant cells (chloroplasts and mitochondria).
2. Both maintain high cellular copy numbers compared to the nuclear genome.
3. Both contain their own autonomous DNA encoding organellar transcription and translation machinery.
4. Both play primary roles in cellular bioenergetics (photosynthesis vs. cellular respiration).
5. Both generally exhibit uniparental (maternal) inheritance in most angiosperms.
6. Both possess endosymbiotic bacterial origins distinct from the eukaryotic nuclear genome.
7. Both serve as effective molecular markers for plant phylogenetics and evolutionary studies.

#### Differences
1. **Location & Function:** Plastid DNA resides in the stroma and governs photosynthesis, whereas mitochondrial DNA resides in the matrix and governs oxidative phosphorylation.
2. **Organization:** Plastomes are highly conserved circular quadripartite structures (LSC-IR-SSC-IR), whereas plant chondriomes display complex, variable configurations (circular, linear, and branched subgenomic forms).
3. **Genome Size:** Plant plastid genomes are compact and uniform (~120–170 kb), whereas plant mitochondrial genomes are much larger and highly variable (~200–2,000+ kb) due to non-coding expansion.
4. **Structural Stability:** Plastid genomes exhibit high structural stability with low recombination rates, while plant mitochondrial genomes undergo frequent internal recombination and rapid structural rearrangements.
5. **Gene Content:** Plastomes encode ~110–130 genes focused on photosynthetic light reactions and carbon fixation, whereas mitochondrial genomes encode ~50–60 genes centered on respiratory electron transport complexes.

---

### 10. Explain the practical value of plastid genomes in research. List as many advantages as you can compared with the nuclear genome, including nuclear sex chromosomes where applicable, and also explain important limitations. Give one research question for which plastid data would be useful and one for which nuclear genomic data would be more appropriate.

#### Advantages of Plastid Genomes
* High copy number per cell ensures high DNA yield during extraction.
* Compact, haploid circular structure simplifies sequencing and genome assembly.
* Absence of meiotic recombination prevents allele scrambling across generations.
* Uniparental inheritance facilitates straightforward maternal lineage tracing.
* Highly conserved gene order allows robust comparative genomics across distantly related plant families.
* Serves as the gold standard for plant DNA barcoding and species identification.
* Useful in biotechnology for transplastomic engineering and high-level protein expression.

#### Limitations of Plastid Genomes
* Represents only a small fraction of the organism's total genetic repertoire.
* Uniparental inheritance obscures hybrid speciation, introgression, and polyploidy.
* Cannot provide information on nuclear-encoded traits or nuclear sex determination (e.g., X/Y sex chromosome systems in dioecious plants).
* Lower nucleotide substitution rates in some lineages may lack sufficient resolution for recent population-level events.

#### Research Questions
* **Plastid Data Question:** *How do phylogenetic relationships among wild and cultivated species of Tagetes reflect evolutionary divergence within the tribe Tageteae (Asteraceae)?*
* **Nuclear Data Question:** *Which nuclear gene variants govern lutein biosynthesis efficiency and flower color variation among commercial Tagetes erecta cultivars?*

---

## 10. Plastid vs Mitochondrial Genome Comparison Table

| Feature | Plastid Genome (*Tagetes erecta*) | Mitochondrial Genome (*Tagetes erecta*) |
| :--- | :--- | :--- |
| **Cellular Location** | Chloroplast stroma | Mitochondrial matrix |
| **Main Biological Functions** | Photosynthesis, carbon fixation, lipid/amino acid biosynthesis | Cellular respiration, oxidative phosphorylation, ATP production |
| **Typical Genome Organization** | Circular quadripartite structure (LSC, $\text{IR}_\text{a}$, SSC, $\text{IR}_\text{b}$) | Complex, dynamic structures (circular, linear, and branched forms) |
| **Relative Genome Size** | ~152 kb (highly conserved across land plants) | ~250–300 kb in *Tagetes* (highly variable in land plants, 200–2,000+ kb) |
| **Gene Content** | ~132 genes (photosynthesis, transcription, translation) | ~50–60 genes (respiratory chain complexes, rRNAs, tRNAs) |
| **Copy Number** | Thousands of copies per photosynthetic cell | Hundreds to thousands of copies per cell |
| **Inheritance** | Predominantly maternal in most angiosperms | Predominantly maternal in most angiosperms |
| **Recombination / Structural Change** | Low internal recombination; structural arrangement conserved | Frequent repeat-mediated recombination & rapid structural rearrangements |
| **Mutation / Substitution Pattern** | Moderate nucleotide substitution rate | Low nucleotide substitution rate in plant coding regions |
| **Common Research Applications** | Plant barcoding, deep phylogenetics, plastid transformation | Cytoplasmic male sterility (CMS), organelle evolution, recombination studies |
