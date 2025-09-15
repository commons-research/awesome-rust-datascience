# Awesome Rust Data Science & Bioinformatics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)



A curated list of **Rust crates, libraries, tools, and resources** for data science and bioinformatics.  
Inspired by [awesome-rust](https://github.com/rust-unofficial/awesome-rust).

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
- [linfa](https://github.com/rust-ml/linfa) — A Rust ML toolkit (similar to scikit-learn).
- [tch-rs](https://github.com/LaurentMazare/tch-rs) — PyTorch bindings for Rust.
- [burn](https://github.com/tracel-ai/burn) — Comprehensive deep learning framework in Rust.

### Numerical & Scientific Computing
- [ndarray](https://github.com/rust-ndarray/ndarray) — N-dimensional array library.
- [nalgebra](https://github.com/dimforge/nalgebra) — General-purpose linear algebra library.
- [ndarray-stats](https://github.com/rust-ndarray/ndarray-stats) — Statistical routines for `ndarray`.

### Visualization
- [plotters](https://github.com/plotters-rs/plotters) — Drawing library for data plotting.
- [vega_lite](https://github.com/johnwdubois/vega_lite_4_rs) — Rust bindings for Vega-Lite.

---

## Bioinformatics

### Genomics
- [rust-bio](https://github.com/rust-bio/rust-bio) — Bioinformatics algorithms and data structures.
- [rust-htslib](https://github.com/rust-bio/rust-htslib) — Bindings to HTSlib for BAM/CRAM/VCF.
- [needletail](https://github.com/onecodex/needletail) — Fast FASTA/Q parsing.

### Proteomics
- [mzML-rs](https://github.com/compomics/mzML-rs) — mzML parsing for mass spectrometry data.
- [msconvert-rs](https://github.com/mobiusklein/msconvert-rs) — Rust tools for proteomics data formats.


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
