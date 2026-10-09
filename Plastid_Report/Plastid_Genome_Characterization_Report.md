# Plastid Genome Characterization Report

**Name:** Jerrick Paul T Tayos

**Course:** Cell and Molecular Biology  
**Section:** B  
**Date:** October 7, 2026  

## Questions for the Student Report

### 1. Give the full scientific name, family, NCBI accession/version, database source, and complete plastid-genome size of your selected organism.

The selected organism is *Tagetes erecta*, commonly known as the African marigold. It belongs to the family **Asteraceae**. The complete chloroplast genome was obtained from the **NCBI Nucleotide/RefSeq database** under accession **MN462588.1**. The complete plastid genome is **152,056 bp** in length.

- **Scientific name:** *Tagetes erecta*
- **Family:** Asteraceae
- **NCBI accession/version:** MN462588.1
- **Database source:** NCBI Nucleotide / RefSeq
- **Complete plastid-genome size:** 152,056 bp

---

### 2. What evidence shows that the sequence is a complete plastid/chloroplast genome rather than a barcode marker, genome fragment, or nuclear sequence?

The NCBI record identifies **MN462588.1** as a **complete chloroplast genome** of *Tagetes erecta*. The sequence is 152,056 bp long and represents one complete plastid molecule rather than a short barcode marker (e.g., *rbcL* ~1.4 kb) or genomic fragment. The annotated record contains the full complement of chloroplast genes involved in photosynthesis, transcription, translation, and other conserved plastid functions. Furthermore, the Galaxy sequence statistics confirmed **one sequence record** with a total length of **152,056 bp** and **0 gaps**, supporting that the uploaded sequence is an intact, complete genome.

---

### 3. Describe the overall organization of the plastid genome. Does it contain the common LSC-IR-SSC-IR arrangement? Give the sizes of these regions when available.

Yes. The *Tagetes erecta* plastid genome exhibits the common quadripartite organization consisting of a **Large Single Copy (LSC)** region, two **Inverted Repeat (IR)** regions ($\text{IR}_\text{a}$ and $\text{IR}_\text{b}$), and a **Small Single Copy (SSC)** region.

The estimated sizes of these regions are:

| Region | Size |
|---|---:|
| LSC | ~83,800 bp |
| IRa | ~25,000 bp |
| SSC | ~18,256 bp |
| IRb | ~25,000 bp |
| **Total** | **152,056 bp** |

The general linear arrangement is **LSC–$\text{IR}_\text{a}$–SSC–$\text{IR}_\text{b}$**. The two identical IR regions contain repeated sequences, leading to the duplication of all genes located within them.

---

### 4. Summarize the annotated gene content: total genes, protein-coding genes, tRNA genes, rRNA genes, and pseudogenes. Explain why genes located in the inverted-repeat regions may appear in two copies.

The annotated *Tagetes erecta* plastid record contains **132 annotated gene features**, including protein-coding genes, tRNA genes, rRNA genes, and a pseudogene.

| Feature | Number |
|---|---:|
| Total annotated genes | 132 |
| Protein-coding genes (CDS) | 87 |
| tRNA genes | 37 |
| rRNA genes | 8 |
| Pseudogenes | 1 |

The annotated pseudogene is a truncated **ycf1** fragment located at the $\text{IR}_\text{b}$/SSC boundary.

Genes located within the inverted-repeat regions appear in two copies because the IR regions themselves are physically duplicated in the circular plastid chromosome. Consequently, any gene positioned inside these repeated segments is present twice in the genome, with one identical copy in each IR.

---

### 5. Choose at least eight protein-coding plastid genes from different functional groups. List each gene and briefly explain its biological function.

| Gene | Functional group | Biological function |
|---|---|---|
| *psaA* | Photosystem I | Encodes a core reaction-center protein of Photosystem I involved in light-driven electron transport. |
| *psbA* | Photosystem II | Encodes the D1 reaction-center protein of Photosystem II, essential for light absorption and water oxidation. |
| *atpA* | ATP synthase | Encodes the alpha subunit of the chloroplast ATP synthase complex responsible for ATP synthesis. |
| *petA* | Cytochrome b6/f complex | Encodes cytochrome f, a key component of the cytochrome b6f complex facilitating electron transport between PSII and PSI. |
| *rbcL* | Carbon fixation | Encodes the large subunit of RuBisCO, catalyzing primary photosynthetic carbon fixation. |
| *rpoA* | Transcription | Encodes the alpha subunit of plastid-encoded RNA polymerase (PEP) involved in plastid gene transcription. |
| *rps12* | Translation | Encodes small ribosomal subunit protein S12, essential for plastid translation (undergoes trans-splicing). |
| *clpP* | Protein processing | Encodes the proteolytic subunit of the ATP-dependent Clp protease complex involved in protein turnover. |

---

### 6. Identify important RNA and RNA-processing features. Include the rRNA genes, examples of tRNA genes, and at least two genes with introns if present in your genome.

The plastid genome encodes four unique rRNA species: **rrn4.5, rrn5, rrn16, and rrn23**. Because all rRNA genes reside within the Inverted Repeat regions, each is present in two copies (total of 8 rRNA genes).

The genome contains **37 tRNA genes**. Examples include *trnK-UUU*, *trnL-UAA*, *trnH-GUG*, *trnI-GAU*, *trnM-CAU*, and *trnfM-CAU*.

Several plastid genes contain introns. Notable examples include **clpP** and **ycf3** (which contain two introns each), as well as **atpF**, **petB**, and **rps12** (which contain single introns). These introns are removed via post-transcriptional RNA splicing to produce mature messenger RNAs.

---

### 7. Describe any pseudogenes, gene losses, duplications, rearrangements, or other unusual features reported for your plastid genome. If none are reported, state this clearly.

One annotated pseudogene is present in the *Tagetes erecta* plastid genome: a truncated fragment of **ycf1** located at the boundary between the $\text{IR}_\text{b}$ and SSC regions, created by incomplete repetition at the IR junction.

Gene duplication is restricted to the **inverted repeat regions**, where all residing genes (including ribosomal RNA genes and several tRNA genes) exist in two functional copies.

The overall genomic arrangement exhibits the standard conserved quadripartite structure typical of the family Asteraceae without major structural rearrangements.

---

### 8. What is the GC content of your plastid genome? Based on your Galaxy results and annotation, describe two other notable sequence or structural observations.

The overall GC content of the *Tagetes erecta* plastid genome is **37.37%**.

Two notable observations are:

1. **Sequence integrity and base composition:** Based on Galaxy sequence statistics, the genome is 152,056 bp long, represented by a single sequence record with 0 gaps ($N\text{ count} = 0$), where adenine (47,465 bp) and thymine (47,826 bp) together comprise over 62% of the sequence.
2. **Uneven GC distribution & trans-splicing:** GC content is unevenly distributed across the genome, being highest in the rRNA genes of the IR regions (~50–55%) and lowest in intergenic spacers. Additionally, the ribosomal protein gene *rps12* is trans-spliced, with its 5' exon in the LSC region and 3' exons in the IR regions.

---

### 9. Compare plastid and mitochondrial genomes. Give at least five similarities and five differences, considering location, biological role, inheritance, genome organization, gene content, copy number, and evolutionary behavior.

#### Similarities

1. Both plastid and mitochondrial genomes reside inside dedicated **energy-converting organelles** within plant cells.
2. Both maintain **high copy numbers** per cell compared to the single- or low-copy nuclear genome.
3. Both encode their own **organellar transcription and translation machinery** (rRNAs, tRNAs, and ribosomal proteins).
4. Both are directly involved in vital cellular **energy conversion and metabolic processes** (photosynthesis and respiration).
5. Both are predominantly **uniparentally inherited** through the cytoplasm (maternal inheritance in most angiosperms).
6. Both possess endosymbiotic evolutionary origins distinct from the host nuclear genome.
7. Both serve as valuable molecular markers in studies of **plant phylogenetics, population genetics, and evolutionary biology**.

#### Differences

| Feature | Plastid Genome | Mitochondrial Genome |
|---|---|---|
| Cellular location | Chloroplast stroma | Mitochondrial matrix |
| Main biological role | Photosynthesis, carbon fixation, fatty acid synthesis, and plastid gene expression | Cellular respiration, oxidative phosphorylation, ATP generation, and mitochondrial gene expression |
| Organization | Highly conserved circular quadripartite structure (LSC,SSC) | Complex, highly variable structural forms (circular, linear, and branched subgenomic molecules) |
| Gene content | Encodes ~110–130 genes mainly for photosynthesis (*psa*, *psb*, *pet*, *rbcL*, *atp*) and translation | Encodes ~50–60 genes mainly for electron transport chain complexes, rRNAs, and tRNAs |
| Genome size | Conserved size range (~120–170 kb); *T. erecta* plastome is 152,056 bp | Extremely variable and larger in land plants (~200–2,000+ kb) due to non-coding sequence expansion |
| Structural evolution | High structural stability with rare genomic rearrangements | Rapid structural evolution driven by frequent internal recombination |
| Research use | Ideal for plant barcoding, deep phylogenetics, plastid transformation, and chloroplast biology | Used for studying cytoplasmic male sterility (CMS), mitochondrial recombination, and organelle evolution |

---

### 10. Explain the practical value of plastid genomes in research. List as many advantages as you can compared with the nuclear genome, including nuclear sex chromosomes where applicable, and also explain important limitations. Give one research question for which plastid data would be useful and one for which nuclear genomic data would be more appropriate.

Plastid genomes are highly valuable in plant science because their conserved structure and haploid nature make them effective tools for plant classification, evolutionary reconstruction, species barcoding, and genetic engineering.

#### Advantages of plastid genomes

- High copy number per cell ensures high yield during DNA extraction.
- Compact, haploid genome structure simplifies sequencing and assembly.
- Absence of meiotic recombination prevents allele scrambling across generations.
- Uniparental (maternal) inheritance simplifies tracing maternal lineages.
- Highly conserved gene order enables comparative genomics across broad taxonomic ranges.
- Ideal target for DNA barcoding and species identification.
- Highly useful for resolving deep phylogenetic relationships among plant families.
- Useful for agricultural biotechnology via transplastomic engineering.

#### Limitations of plastid genomes

- Represents only a minor fraction of the total plant genome content.
- Uniparental inheritance obscures hybrid speciation, introgression, and polyploidy events.
- Does not encode the vast majority of nuclear-driven physiological and morphological traits.
- Reduced substitution rates in some lineages may lack resolution for very recent population-level events.

Nuclear genomes contain the majority of an organism's genes, including biparentally inherited alleles. In species with nuclear sex chromosomes (such as X/Y systems in dioecious plants), nuclear genomic data is required to study sex determination and sex-linked inheritance, features completely absent from organellar genomes.

#### Research question where plastid data would be useful

**How do phylogenetic relationships among wild and cultivated species of *Tagetes* reflect evolutionary divergence within the tribe Tageteae (Asteraceae)?**

#### Research question where nuclear genomic data would be more appropriate

**Which nuclear gene variants govern lutein biosynthesis pathway efficiency and flower color variation among commercial *Tagetes erecta* cultivars?**
