### Moritz Heusel

Mass-spectrometry-based proteomics — **tailored bioinformatic solutions** from instrument to
biological insight: DIA-MS method and software development, protein complex profiling,
LC-MS quality control, and multi-omics data integration (R, Python, Docker, Snakemake, Shiny).

[Google Scholar](https://scholar.google.com/citations?user=fl3BPiwAAAAJ) ·
[ORCID 0000-0002-8506-530X](https://orcid.org/0000-0002-8506-530X)

#### Highlights

**1. mE-DIA — multi-enzyme DIA in a single injection**
Library-free, proteoform-aware DIA-MS workflow multiplexing complementary protease digests,
with CLI, GUI and interactive Peptide Mapper (powered by DIA-NN).
[Repository](https://github.com/heuselm/mE-DIA) ·
[Preprint (bioRxiv 2026)](https://doi.org/10.64898/2026.11.06.764873)

**2. mqqc — MaxQuant-based LC-MS instrument QC**
Semi-automatic instrument qualification at the interface of MaxQuant-GUI operators and data
analysis, capturing performance as a time course.
[Repository](https://github.com/heuselm/mqqc)

**3. SECprofiler → CCprofiler — complex-centric proteome profiling (SEC-SWATH-MS)**
[SECprofiler](https://github.com/heuselm/SECprofiler) (prototype, with R. Hafen) and
[CCprofiler](https://github.com/CCprofiler/CCprofiler) for detecting hundreds of protein
complexes from co-fractionation data, with end-to-end pipelines
([peptide-centric](https://github.com/CCprofiler/SECSWATH_PeptideCentricAnalysis),
[complex-centric](https://github.com/CCprofiler/SECSWATH_ComplexCentricAnalysis)) and
interactive viewers:
[SECexplorer-cc](https://github.com/heuselm/SECexplorer_hela_cc) ([live](https://sec-explorer.shinyapps.io/hela_cellcycle/)) ·
[SECexplorer HEK293](https://github.com/heuselm/SECexplorer_HEK293) ·
[SECexplorer THP-1](https://github.com/heuselm/SECexplorer_THP1)
> Heusel M, Bludau I, Rosenberger G, et al. Complex-centric proteome profiling by SEC-SWATH-MS.
> *Mol Syst Biol* 15:e8438 (2019). [doi:10.15252/msb.20188438](https://doi.org/10.15252/msb.20188438)

**4. SWATH2stats — from OpenSWATH to statistics (Bioconductor)**
Co-developer (package author) of the R/Bioconductor package that filters, annotates and
FDR-controls OpenSWATH results and converts them for MSstats, mapDIA and aLFQ.
[Bioconductor](https://bioconductor.org/packages/SWATH2stats/) ·
[Repository](https://github.com/peterblattmann/SWATH2stats)
> Blattmann P, Heusel M, Aebersold R. SWATH2stats: an R/Bioconductor package to process and
> convert quantitative SWATH-MS proteomics data for downstream analysis tools.
> *PLoS ONE* 11:e0153160 (2016). [doi:10.1371/journal.pone.0153160](https://doi.org/10.1371/journal.pone.0153160)

#### More

[DiffTestR](https://github.com/heuselm/DiffTestR) (differential testing for AP-DIA-MS) ·
[diapipeline](https://github.com/heuselm/diapipeline) (containerized OpenSWATH) ·
[swathTUNER](https://github.com/heuselm/swathTUNER) (DIA window optimization) ·
[igseq_workflow](https://github.com/heuselm/igseq_workflow) (immunoproteogenomics)
