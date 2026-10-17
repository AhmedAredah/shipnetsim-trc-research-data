# ShipNetSim TR-C research data

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23434877.svg)](https://doi.org/10.5281/zenodo.23434877)

This repository contains the research data supporting the manuscript **“Query-Local Hierarchical Visibility Graphs with Phased Adjacency for Geometry-Derived Maritime Route Construction.”** The 48 comma-separated-value files report the route, validation, sensitivity, and performance evidence analyzed in the article and its supplementary material.

## Contents

| Directory | Contents |
|---|---|
| `00_documentation` | Dataset catalog, evidence crosswalk, data-source record, and experimental environment |
| `01_primary_routes` | Primary-route endpoints, waypoints, outcomes, refinement, and route diagnostics |
| `02_search_and_representation_validation` | Fixed-graph search checks and finite-representation cases |
| `03_hierarchy_refinement` | Hierarchy, refinement, and sparse-flat control results |
| `04_parameter_sensitivity` | Factorial and one-factor sensitivity observations |
| `05_geometry_and_source_validation` | Geometry, screening, and paired-source validation evidence |
| `06_performance` | Repeated-process performance and preprocessing-amortization observations |
| `07_external_method_adaptation` | Matched external-method measurements and resource use |

Begin with [`00_documentation/evidence_crosswalk.csv`](00_documentation/evidence_crosswalk.csv) to locate the evidence for each article result. [`00_documentation/dataset_catalog.csv`](00_documentation/dataset_catalog.csv) defines the scientific purpose of every file.

## Data conventions

- Files use UTF-8 comma-separated values with a header row.
- Units are stated in column names or in the associated manuscript definitions.
- Geographic coordinates use WGS84 longitude and latitude in decimal degrees.
- Route-waypoint files are ordered by route identifier and waypoint sequence.
- Missing or inapplicable values are represented explicitly by the corresponding status fields rather than imputed.

The evaluated software is maintained in the [ShipNetSim repository](https://github.com/VTTI-CSM/ShipNetSim). Source cartography and third-party implementations are identified in [`00_documentation/data_sources.csv`](00_documentation/data_sources.csv); they are not redistributed here.

## Citation

Please cite the archived dataset release. Version 1.0.0 is available at [https://doi.org/10.5281/zenodo.23434878](https://doi.org/10.5281/zenodo.23434878); the version-independent dataset DOI is [https://doi.org/10.5281/zenodo.23434877](https://doi.org/10.5281/zenodo.23434877). Citation metadata are provided in [`CITATION.cff`](CITATION.cff).

## License

The original contents of this repository are licensed under the [Creative Commons Attribution 4.0 International License](LICENSE.md). Third-party sources remain subject to their respective terms; see [`NOTICE.md`](NOTICE.md).

## Contact

Questions about the dataset may be directed to Ahmed Aredah at [A-Aredah@tti.tamu.edu](mailto:A-Aredah@tti.tamu.edu).
