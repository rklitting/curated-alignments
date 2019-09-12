## Curated alignments

We periodically combine genomic sequences generated as part of our consortium with publicly available sequences. 

Sequences with lower quality (probable sequencing errors) and incomplete sequences (<95% of (GP+NP) or (Z+L) ORFs length) are excluded from the curated alignment.Remaining sequences are trimmed to their coding regions, codon aligned using [mafft](https://mafft.cbrc.jp/alignment/software/tips0.html) and inspected manually. ORFs are arranged in sense orientation as follows:

S segment: NP -NNNNNN- GP
L segment: L -NNNNNN- Z

To control for alignment accuracy, a maximum likelihood (ML) phylogeny is reconstructed with RAxML using the general time-reversible (GTR) nucleotide substitution model, gamma-distributed rates among sites and bootstrap resampling with 500 replicates.

We will be releasing such curated alignments periodically to be used by the broader community for downstream analyses.

## Lassa

Alignment File: [LASV_2019-09-04.fasta](https://raw.githubusercontent.com/cvisb/curated-alignments/master/lassa/LASV_Sseg_2019-09-04.fasta)

Total Number of sequences: 592

FASTA header format:
```
> ID | GenBank Accession | Species | Outcome | Country | Date
```

Key:

Species

| Code | Species | Count |
|:---|:---|:---|
| Hs | *Homo sapiens* | 567 |
| Hp | *Hylomyscus pamfi* | 1 |
| Me | *Mastomys erythroleucus* | 9 |
| Mn | *Mastomys natalensis* | 15 |

Country

| Code | Country | Count |
|:--|:--|:--|
|GIN | Guinea | 9 |
| LBR | Liberia | 22 |
| MLI | Mali | 3 |
| NGA | Nigeria | 470 |
| SLE | Sierra Leone | 87 |
| TGO | Togo | 1 |

Outcome

|Code | Outcome | Count |
|:-- |:-- |:-- |
| Died | Died | 119 |
| Discharged | Discharged | 89 |
| UNK | Unknown | 384 |

---
**Andersen Lab**  
The Scripps Research Institute  
La Jolla, CA, USA  
[data@andersen-lab.com](mailto:data@andersen-lab.com)
