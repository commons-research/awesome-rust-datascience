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
- [Semantic Web](#semantic-web)
  - [RDF, Linked Data & SPARQL](#rdf-linked-data--sparql)
  - [Ontologies, Validation & Reasoning](#ontologies-validation--reasoning)
  - [Data Conversion & Interchange](#data-conversion--interchange)
  - [Knowledge Graph Stores & Applications](#knowledge-graph-stores--applications)
  - [FAIR & Scholarly Data](#fair--scholarly-data)
- [Software Engineering](#software-engineering)
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
- [augurs](https://github.com/grafana/augurs) Time series analysis for Rust (MSTL, ETS, Prophet).


### Numerical & Scientific Computing
- [ndarray](https://github.com/rust-ndarray/ndarray) — N-dimensional array library.
- [nalgebra](https://github.com/dimforge/nalgebra) — General-purpose linear algebra library.
- [ndarray-stats](https://github.com/rust-ndarray/ndarray-stats) — Statistical routines for `ndarray`.
- [approx](https://github.com/brendanzab/approx) — Approximate floating point equality comparisons and assertions.


### Visualization
- [plotters](https://github.com/plotters-rs/plotters) — Drawing library for data plotting.
- [vega_lite](https://github.com/procyon-rs/vega_lite_4.rs) — Rust bindings for Vega-Lite.
- [charming](https://github.com/yuankunzhang/charming) — A Rust library for creating charts using Apache ECharts.
- [rustplotlib](https://github.com/askanium/rustplotlib) — A pure Rust visualization library inspired by D3.js
- [plotly.rs](https://github.com/plotly/plotly.rs) - Plotly for Rust.


---

## Bioinformatics
- [sprocket](https://github.com/stjude-rust-labs/sprocket) — Bioinformatics workflow engine
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

## Semantic Web


### RDF, Linked Data & SPARQL
- [harriet](https://github.com/field33/harriet) — A parser for the [Turtle](https://www.w3.org/TR/turtle/) document format.
- [json-ld](https://github.com/timothee-haudebourg/json-ld) — A Rust implementation of the [JSON-LD](https://github.com/timothee-haudebourg/json-ld) data interchange format.
- [Kolibrie](https://github.com/StreamIntelligenceLab/Kolibrie) —  a high-performance, concurrent, and feature-rich SPARQL query engine implemented in Rust.
- [linked-data-rs](https://github.com/spruceid/linked-data-rs) — Library that provides primitive traits to serialize and deserialize Linked-Data types.
- [oxigraph](https://github.com/oxigraph/oxigraph) — A graph database implementing the SPARQL standard with the goal of being safe, compliant, and fast.
  - [oxrdf](https://github.com/oxigraph/oxigraph/tree/main/lib/oxrdf) — A simple library providing datastructures encoding [RDF 1.1 concepts](https://www.w3.org/TR/rdf11-concepts/).
  - [oxrdf/xml](https://github.com/oxigraph/oxigraph/tree/main/lib/oxrdfxml) — A parser and serializer for [RDF/XML](https://www.w3.org/TR/rdf-syntax-grammar/).
  - [oxttl](https://github.com/oxigraph/oxigraph/tree/main/lib/oxttl) — A  set of parsers and serializers for [Turtle](https://www.w3.org/TR/turtle/), [TriG](https://www.w3.org/TR/trig/), [N-Triples](https://www.w3.org/TR/n-triples/), [N-Quads](https://www.w3.org/TR/n-quads/) and [N3](https://w3c.github.io/N3/spec/).
  - [spargebra](https://github.com/oxigraph/oxigraph/tree/main/lib/spargebra) — A [SPARQL](https://www.w3.org/TR/sparql11-overview/) parser.
  - [sparesults](https://github.com/oxigraph/oxigraph/tree/main/lib/sparesults) — A set of parsers and serializers for [SPARQL](https://www.w3.org/TR/sparql11-overview/) query result formats.
- [Qlue-ls](https://github.com/IoannisNezis/Qlue-ls) — A blazingly fast [language server](https://microsoft.github.io/language-server-protocol/specifications/lsp/3.17/specification) for [SPARQL](https://de.wikipedia.org/wiki/SPARQL).
- [rdf.rs](https://github.com/rust-rdf/rdf.rs) — A framework for working with [RDF](https://www.w3.org/TR/rdf12-concepts/) knowledge graphs.
- [rdftk](https://github.com/johnstonskj/rust-rdftk) — An RDF toolkit as a set of crates providing the ability to work with RDF data.
- [semantic web language server](https://github.com/SemanticWebLanguageServer/swls) — A server for IDEs to add functionality for semantic web languages.
- [Sophia](https://github.com/pchampin/sophia_rs) — A Rust toolkit for RDF and Linked Data comprising several crates.


### Ontologies, Validation & Reasoning
- [fastobo](https://github.com/fastobo/fastobo) — A library for *faultless* ASTs for Open Biomedical Ontologies.
- [horned-owl](https://github.com/phillord/horned-owl) — A library for processing and manipulating documents written using the [Web Ontology Langauge](https://github.com/phillord/horned-owl).
- [ontology-registry](https://github.com/P2GX/ontology-registry) — A robust, thread-safe Rust library for managing the lifecycle of biological ontologies.
- [plow](https://github.com/field33/plow) — A package management solution for OWL ontologies using [Semver](https://semver.org/).
- [reasonable](https://github.com/gtfierro/reasonable) — An OWL 2 RL reasoner with reasonable performance.
- [roxi](https://github.com/pbonte/roxi) — A uniform framework for Reactive Reasoning applications.
- [rudof](https://github.com/rudof-project/rudof) — An RDF data shapes library implemented in Rust; supports [ShEx](http://shex.io/), [SHACL](https://www.w3.org/TR/shacl/), [DCTap](https://www.dublincore.org/specifications/dctap/).


### Data Conversion & Interchange
- [csv2rdf](https://github.com/DeciSym/csv2rdf) — Rust-based tool that converts CSV data into RDF format.
- [decisym engine (`de`)](https://github.com/DeciSym/de) — A command-line tool for creating, querying, and inspecting RDF data in [HDT](http://www.rdfhdt.org/)(Header, Dictionary, Triples) format.
- [graph-rdfa-processor](https://github.com/nbittich/graph-rdfa-processor) — Rust and wasm library to extract RDF statements (in n-triples format) from an html file based on rdfa annotations.
- [hdt](https://github.com/konradhoeffner/hdt) — A Rust library for the [Header Dictionary Triples](https://github.com/konradhoeffner/hdt) compressed RDF format.
- [json2rdf](https://github.com/DeciSym/json2rdf) — Rust-based tool that converts JSON data into RDF format. 
- [toon-ld](https://github.com/argahsuknesib/toon-ld) — Token-Oriented Object Notation for Linked Data (TOON-LD) is a lossless knowledge graph compression format for LLM Context Windows.
- [xml2rdf](https://github.com/DeciSym/xml2rdf) — Rust-based tool that converts XML to RDF.


### Knowledge Graph Stores & Application
- [atomic-server](https://github.com/ontola/atomic-server) — A lightweight, yet powerful CMS / Graph Database using [Atomic Data](https://docs.atomicdata.dev/).
- [FalkorSemantic](https://github.com/FalkorDB/FalkorSemantic) — A high-performance Redis module that extends [FalkorDB](https://www.falkordb.com/) with RDF and SPARQL capabilities, bridging the property graph and semantic web worlds.
- [manas](https://github.com/manomayam/manas) — Modular framework and ecosystem to create correct, robust storage servers adhering to [Solid protocol](https://solidproject.org/TR/protocol).
- [nextgraph-rs](https://git.nextgraph.org/NextGraph/nextgraph-rs) — A Rust implementation of [NextGraph](https://nextgraph.org/) ([github version](https://github.com/nextgraph-org/nextgraph-rs)).
- [oxirs](https://github.com/cool-japan/oxirs) — A Rust-native, modular platform for Semantic Web, SPARQL 1.2, GraphQL, and AI-augmented reasoning.
- [rickview](https://github.com/konradhoeffner/rickview) — An easy to deploy low-resource stand-alone RDF knowledge graph browser written in Rust. 


### FAIR & Scholarly Data
- [aruna](https://github.com/arunaengine/aruna) — A federated, FAIR peer-to-peer data management framework. 
- [listeria_rs](https://github.com/magnusmanske/listeria_rs) — Code base that runs the Listeria bot on Wikimedia wikis.
- [nanopub-rs](https://nanopub.net/) — A comprehensive cross-platform toolkit to sign, publish, and check [Nanopublications](https://nanopub.net/).
- [papers](https://github.com/magnusmanske/papers) — A Rust crate and binary to create and update Wikidata items about scientific publications, and their authors, from third-party sources.
- [ro-create-rust](https://github.com/arunaengine/ro-crate-rust) — A Rust implementation of the [RO-Crate](https://www.researchobject.org/ro-crate/) metadata specification for Research Objects.
- [wikibase_rest_api](https://github.com/magnusmanske/wikibase_rest_api) — A Rust client library for the [Wikibase REST API](https://doc.wikimedia.org/Wikibase/master/js/rest-api/).
- [wikidata](https://github.com/syvb/wikidata/) — Rust bindings for [Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page) to make it easy to use data from Wikidata in Rust programs.


---

## Software Engineering
- [shadow-rs](https://github.com/baoyachi/shadow-rs) — A rust library that adds support for showing a project's `Cargo.toml` info at runtime. 
- [citum-core](https://github.com/citum/citum-core) — A citation engine with a rich reference data model and style language.
- [gloo](https://github.com/ranile/gloo) — A toolkit for building fast, reliable Web applications and libraries with Rust and Wasm.

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
