# Characterization of the Plastid Genome of Tagetes erecta

**Student:** Jerrick Paul T. Tayos  
**Course:** Cell & Molecular Biology  
**Species:** *Tagetes erecta* L. (African Marigold)  
**Family:** Asteraceae  
**NCBI Accession:** MN462588.1  
**Retrieval Date:** October 7, 2026

## Selected Plant

**Genus:** *Tagetes*  
**Species:** *Tagetes erecta*  
**Family:** Asteraceae  

## NCBI Accession

**Accession:** MN462588.1  
**Genome Type:** Complete chloroplast genome  
**Genome Size:** 152,056 bp  

**NCBI Source:**  
[https://www.ncbi.nlm.nih.gov/nuccore/MN462588.1  ](https://www.ncbi.nlm.nih.gov/nuccore/MN462588.1/)

## Genome Overview
- **Genome Size:** 152,065 bp
- **GC Content:** 37.4%
- **Topology:** Circular quadripartite
- **Total Genes:** 132 (87 CDS, 37 tRNA, 8 rRNA)

## NCBI Accession & Reference
- **Organism:** *Tagetes erecta* L.
- **Family:** Asteraceae
- **Accession:** `MN462588.1`

## Plastid Genome Summary

The complete chloroplast genome of *Tagetes erecta* is 152,056 bp long. It has a quadripartite organization consisting of the Large Single Copy (LSC), two Inverted Repeat (IR) regions, and the Small Single Copy (SSC) region.
- **LSC:** ~83,800 bp
- **IRa:** ~25,000 bp
- **SSC:** ~18,256 bp
- **IRb:** ~25,000 bp
- **GC Content:** 37.37%

The genome contains protein-coding genes, tRNA genes, rRNA genes, and pseudogenes. Several genes are duplicated because they occur within the inverted repeat regions.

## Galaxy Analysis

- **Galaxy Platform:** https://galaxy-main.usegalaxy.org/u/jerrick_tayos/h/plastid-tagetes-tayos
- **Galaxy History:** `Plastid_Tagetes_Tayos

The FASTA sequence was downloaded from NCBI and uploaded to Galaxy. A FASTA sequence statistics tool (`Fasta Statistics`) was used to determine the genome length, number of sequence records, GC content, and base counts.

## Galaxy Results

| Parameter | Result |
| :--- | :--- |
| **Genome length** | 152,056 bp |
| **Sequence records** | 1 |
| **GC content** | 37.37% |
| **Gaps (N count)** | 0 |

## Gene Characterization

Important plastid gene groups identified include:
- `psa` (Photosystem I)
- `psb` (Photosystem II)
- `atp` (ATP Synthase)
- `pet` (Cytochrome b6f)
- `rbcL` (RuBisCO large subunit)
- `rpo` (RNA polymerase)
- `rpl` and `rps` (Ribosomal proteins)
- `rrn` (rRNA genes) and `trn` (tRNA genes)
- `matK`, `clpP`, `accD`, `cemA`, and `ycf` genes

The annotated genome also contains genes associated with the inverted repeat regions. An annotated pseudogene fragment located at the $\text{IR}_\text{b}$/SSC boundary is `ycf1`.

## Important Observations

1. The *Tagetes erecta* chloroplast genome has the typical quadripartite organization found in many land-plant plastomes. The two inverted repeat regions contribute to the duplication of several genes, including ribosomal RNAs and tRNAs.
2. The plastid genome contains genes involved in photosynthesis, transcription, translation, ribosomal function, and other key plastid-related metabolic processes.



## Data Sources

- NCBI Nucleotide: https://www.ncbi.nlm.nih.gov/nuccore/
- NCBI GenBank: https://www.ncbi.nlm.nih.gov/genbank/
- usegalaxy.org: https://usegalaxy.org/
- Galaxy Training Network: https://training.galaxyproject.org/
- GitHub: https://github.com/

## Reproducibility

Another student can repeat this analysis by:
1. Searching NCBI Nucleotide for the complete chloroplast genome of *Tagetes erecta*.
2. Opening accession `MN462588.1`.
3. Downloading the FASTA sequence (`tagetes_erecta_sequence.fasta`).
4. Creating a Galaxy history named `Plastid_Tagetes_<Surname>`.
5. Uploading the FASTA file to usegalaxy.org.
6. Running the `Fasta Statistics` tool.
7. Recording genome length (152,056 bp), sequence count (1), GC content (37.37%), and gaps (0).
8. Using the annotated GenBank record to characterize genes, inverted repeats, introns, and pseudogenes.
9. Comparing the results with those reported in this repository.


