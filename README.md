# biocHCA -- Notes on Bioconductor tasks for HCA 2018 meeting

## Bioconductor approach to Benchmark Data Repository management and contribution

- ExperimentHub: current state of art, notable examples
- Are any innovations needed?

## SingleCellExperiment extensions

- Seurat compatibility
- Internal interoperability assurances
- Different concepts of representing analysis progression - successively stick results into the 'same' object vs have separate objects for primary and derived results

## Parallelization of 10x workflow

- rhdf5 can be used with socket-level parallelism, how about forking?

## Back-ends for large volume assay quantifications

- HDF5 local and remote
- Spark and other distributed data architectures
- Parquet, Arrow

## Metadata considerations

- accommodating the HCA schema/terminology beyond files to features, cells, donors
- Does SingleCellExperiment need additional infrastructure to increase precision of provenance
- Integrating elasticsearch functionality for R users

## Workflow language and cloud deployment of 10x and allied workflows

- CWL/WDL

