# Figure QA Notes

## Scientific contract

- **Core conclusion:** bulk and single-cell RNA-seq can share the same short-read sequencing chemistry, but single-cell resolution requires cellular and molecular identities to be encoded before pooling.
- **Evidence logic:** panel a shows loss of cell-of-origin information during bulk pooling; panel b shows partitioning, cell barcodes, and UMIs; panel c shows the shared sequencing-by-synthesis endpoint.
- **Archetype:** schematic-led comparison with a shared mechanistic layer.
- **Data status:** conceptual figure; no quantitative experimental observations or inferred values are displayed.

## Scientific boundaries

- The single-cell panel represents a typical droplet-based 3′ gene-expression workflow.
- Exact oligonucleotide sequences, barcode lengths, UMI lengths, read structures, and amplification reactions are platform- and chemistry-dependent.
- Droplet occupancy is an intended one-cell/one-bead design, not a guarantee; empty droplets and multiplets occur in real experiments.
- scATAC-seq and multiome assays share cell-identity encoding logic but use different molecular reactions and output matrices.

## Visual checks

- Editable source: SVG.
- Raster preview: 1800 × 1120 PNG.
- Background: white.
- Typeface: Arial/Helvetica/sans-serif fallback.
- Encoding: blue for bulk RNA-seq, purple for single-cell identity, green for RNA/capture chemistry, orange for adapters or UMIs.
- Red and green are not used as the sole categorical contrast.
- Full-canvas preview inspected for clipped labels, overlaps, broken arrows, and unintended cropping.

