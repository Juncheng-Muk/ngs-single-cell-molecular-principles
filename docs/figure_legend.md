# Figure legend

**Figure 1 | Molecular principles shared by conventional next-generation sequencing and droplet-based single-cell RNA sequencing.**

**a, Conventional bulk RNA-seq.** RNA molecules extracted from a population of cells are converted into cDNA, fragmented or size-selected as required, and ligated or extended with sequencing-compatible adapters and sample indexes. Molecules from all cells in the sample are pooled before sequencing, so the resulting abundance profile represents a population-average signal and does not preserve the cellular origin of individual transcripts.

**b, Droplet-based single-cell RNA-seq.** A single-cell suspension is partitioned into droplets together with barcoded beads. Ideally, a productive droplet contains one cell and one bead. Polyadenylated RNA is captured by bead-linked oligo(dT) primers, and reverse transcription appends a bead-specific cell barcode and a molecule-specific unique molecular identifier (UMI) to the resulting cDNA. Barcoded cDNAs can then be pooled, amplified, converted into a sequencing-compatible library, and sequenced together. The cell barcode assigns each read to a cellular partition, whereas the UMI supports computational collapsing of amplification duplicates and molecule counting. The final output is typically a sparse gene-by-cell UMI count matrix.

**c, Shared short-read sequencing layer.** Adapter-bearing library molecules bind to complementary oligonucleotides on a flow cell, undergo local clonal amplification, and are read through repeated cycles of nucleotide incorporation, fluorescence imaging, and reversible-terminator cleavage. Base calls and quality scores are written to FASTQ files. The illustrated sequencing-by-synthesis chemistry is representative of a widely used short-read platform rather than every possible second-generation sequencing instrument.

The scRNA-seq panel shows a conceptual 3′ droplet workflow. Exact primer architecture, read orientation, barcode length, UMI length, and library construction depend on the assay and chemistry version.

