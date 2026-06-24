# Day 1 — Mapping practical + SQANTI-reads QC

Hands-on for **Day 1 (evening)**: *Different long-read mappers and QC evaluation with SQANTI-reads*
(Carol & Tian).

## Notebooks
| file | purpose |
|------|---------|
| `mapping_and_sqanti_reads.ipynb` | student worksheet (with `# TODO` cells to complete) |
| `mapping_and_sqanti_reads.SOLUTION.ipynb` | full solution — **Run All** works end-to-end |
| `executed_SOLUTION.html` | the solution rendered with its outputs, for reference |

## Kernel / environment
Use the **`sqanti3`** kernel (shown as **"Python (SQANTI3)"**) — SQANTI3 **v6.0.1**.
⚠️ *Not* the similarly-named `SQANTI3.env` (incomplete; VS Code may mis-recommend it).
The first notebook cell prepends the env `bin/` to `$PATH` so shell `!` commands work.

## Data (symlinked, not in this repo)
Human **chr8**, **PacBio Iso-Seq (HiFi)** cDNA long reads (ENCODE H1), **6 samples in 2 groups**
(`endo` = H1-derived endoderm, `h1` = H1 ESCs), 3 replicates each, ≤25k reads/sample — the same
reads used by the Day 2 IsoTools / SQANTI3 sessions.

The reads + reference are **not committed here**. They live in
`course_data/sqanti_reads_practical/data/` on the course machine and are **symlinked** into each
student's `data/` folder at provision time:

```
data/
  endo_1.fastq … h1_3.fastq   -> course_data/sqanti_reads_practical/data/*.fastq
  reference                   -> course_data/sqanti_reads_practical/data/reference
```

The notebook reads from `data/` and writes all outputs (`*.chr8.bam`, `out/`, and SQANTI3's
`data/*.renamed.fasta`) into the **student's own folder** — the shared base is never written to,
even with the whole class running at once (verified).

## What the practical does
1. **Map** long reads with `minimap2` (splice-aware) and inspect the spliced alignments.
2. **Run `sqanti3_reads.py`** to classify every read into structural categories, hash UJCs, and
   aggregate the 6 samples faceted by group (`--factor group`). ~20 min.
3. **Explore** the QC tables + faceted report: structural categories, UJC counts, read length,
   junction CV (donor/acceptor precision), cross-sample PCA, and under-annotated genes.
