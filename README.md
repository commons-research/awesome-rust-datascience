# Awesome Rust Data Science & Bioinformatics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)



A curated list of **Rust crates, libraries, tools, and resources** for data science and bioinformatics.  
See the [awesome-rust](https://github.com/rust-unofficial/awesome-rust) for a more comprehensive and less focussed list of crates of interest.

Adapting [awesome-semantic-web](https://github.com/semantalytics/awesome-semantic-web) contribution mechanisms:

- to add something to the list please either go to https://github.com/commons-research/awesome-rust-datascience/blob/main/README.md and click on the "pen" icon in the upper right corner. Make the changes to the file and follow the instructions to create a pull request. Alternatively, add a comment with a link to [awesomelets](https://github.com/commons-research/awesome-rust-datascience/issues/1). Pull requests will be evaluated shortly for inclusion while awesomelets will be evaluated at some indeterminate time in the future.

- Looking for something but can't find it? Add it to the ["Does it exist"](https://github.com/commons-research/awesome-rust-datascience/issues/2) list and we'll keep an eye out for it. If it's a good idea maybe someone will come along and create it!

---

## Contents
- [Data Science](#data-science)
  - [DataFrames & Analytics](#dataframes--analytics)
  - [Machine Learning](#machine-learning)
  - [Numerical & Scientific Computing](#numerical--scientific-computing)
  - [Visualization](#visualization)
- [Bioinformatics](#bioinformatics)
  - [Genomics](#genomics)
  - [Proteomics](#proteomics)
  - [Metabolomics](#metabolomics)
- [Resources](#resources)
  - [Tutorials](#tutorials)
  - [Books & Courses](#books--courses)
  - [Communities](#communities)

---

## Data Science

### DataFrames & Analytics
- [polars](https://github.com/pola-rs/polars) — Fast DataFrame library powered by Apache Arrow.
- [datafusion](https://github.com/apache/arrow-datafusion) — Query engine using Apache Arrow.

### Machine Learning

More comprehensive lists can be found in the [Awesome-Rust-MachineLearning](https://github.com/vaaaaanquish/Awesome-Rust-MachineLearning)

- [burn](https://github.com/tracel-ai/burn) — Comprehensive deep learning framework in Rust.
- [linfa](https://github.com/rust-ml/linfa) — A Rust ML toolkit (similar to scikit-learn).
- [rust-sdk](https://github.com/modelcontextprotocol/rust-sdk) — The SDK for creating [MCP](https://en.wikipedia.org/wiki/Model_Context_Protocol) applications with Rust.
- [tch-rs](https://github.com/LaurentMazare/tch-rs) — PyTorch bindings for Rust.


### Numerical & Scientific Computing
- [ndarray](https://github.com/rust-ndarray/ndarray) — N-dimensional array library.
- [nalgebra](https://github.com/dimforge/nalgebra) — General-purpose linear algebra library.
- [ndarray-stats](https://github.com/rust-ndarray/ndarray-stats) — Statistical routines for `ndarray`.


### Visualization
- [plotters](https://github.com/plotters-rs/plotters) — Drawing library for data plotting.
- [vega_lite](https://github.com/procyon-rs/vega_lite_4.rs) — Rust bindings for Vega-Lite.
- [charming](https://github.com/yuankunzhang/charming) — A Rust library for creating charts using Apache ECharts.
- [rustplotlib](https://github.com/askanium/rustplotlib) — A pure Rust visualization library inspired by D3.js
- [plotly.rs](https://github.com/plotly/plotly.rs) - Plotly for Rust.


---

## Bioinformatics

### Genomics
- [rust-bio](https://github.com/rust-bio/rust-bio) — Bioinformatics algorithms and data structures.
- [rust-htslib](https://github.com/rust-bio/rust-htslib) — Bindings to HTSlib for BAM/CRAM/VCF.
- [needletail](https://github.com/onecodex/needletail) — Fast FASTA/Q parsing.

### Proteomics
- [mzcore](https://github.com/compomics/mzML-rs) — A Rust library for peptide centric mass spec calculations centered around ProForma and complex theoretical fragmentation



### Metabolomics
- [mzdata](https://github.com/mobiusklein/mzdata) — A Rust library for reading mass spectrometry data file formats.
- [mzpeaks](https://github.com/mobiusklein/mzpeaks) — Types and traits for generic representation of peaks and features for mass spectrometry, including searchable collections and spatial data structures.
- [mzsignal](https://github.com/mobiusklein/mzsignal) — Algorithms for low-level signal processing of mass spectra and temporal traces like chromatograms or mobilograms, including peak picking, feature extraction, signal averaging, smoothing and denoising.
- [mzdeisotope](https://github.com/mobiusklein/mzdeisotope) — Algorithms for charge state deconvolution and deisotoping of mass spectra and feature maps.
- [mass-fragment-index](https://github.com/mobiusklein/mass-fragment-index) — Data structures for large-scale searching of precursor-product collections suitable for fragment indices, spectral libraries, or similar data. Includes fast-to-search on-disk serialization.


---

## Resources

### Tutorials
- [Rust for Data Science](https://github.com/rust-ml/linfa/tree/main/examples) — Examples from `linfa`.
- [Polars User Guide](https://pola-rs.github.io/polars-book/) — Official Polars documentation.

### Books & Courses
- [Programming Rust](https://www.oreilly.com/library/view/programming-rust-2nd/9781492052586/) — O’Reilly book.
- [Rust for Data Science Book (draft)](https://rust-ds.github.io/book/) — Early-stage open book.

### Communities
- [Rust Users Forum](https://users.rust-lang.org/)
- [Rust Bioinformatics GitHub Org](https://github.com/rust-bio)
- [Rust ML GitHub Org](https://github.com/rust-ml)

---

## Contributing
Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.
