# Datasets, pipelines and predictions of universal BMX-FC metric

[![doi](https://img.shields.io/badge/doi-TODO-c3211f)](https://www.doi.org/)
[![DOI](https://zenodo.org/badge/756983131.svg)](https://zenodo.org/doi/10.5281/zenodo.10662723)
[![license](https://img.shields.io/badge/License-CC%20BY%20SA%204.0-15a300)](https://creativecommons.org/licenses/by-sa/4.0/)

Datasets, pipelines and predictions of a metric for benchmarking an extreme 
fast-charging of Li-ion battery electrode materials.

This repository supports the main work

> TODO citation


## Content

The [datasets](https://github.com/fernandezfran/bmxfc/tree/main/datasets) folder 
contains the data of experimental characterizations, of the simulation of the map,
and for the validation of the model. The 
[predictions](https://github.com/fernandezfran/bmxfc/tree/main/predictions) folder 
contains the predictions obtained with the different `pipelines` that were run in
the following order:
1. [pipeline_metrics.ipynb](https://github.com/fernandezfran/bmxfc/blob/main/pipelines/pipeline_metrics.ipynb)
2. [pipeline_predictions.ipynb](https://github.com/fernandezfran/bmxfc/blob/main/pipelines/pipeline_predictions.ipynb)
3. [pipeline_validation.ipynb](https://github.com/fernandezfran/bmxfc/blob/main/pipelines/pipeline_validation.ipynb)


## Code Repository

https://www.github.com/fernandezfran/bmxfc


## Disclaimer

This repository only have the predictions for a kinetic rate constant of 1e-7,
the other values reported in the paper can be obtained by slightly modifying
the `pipelines`.


## License

This repository is licensed under the Creative Commons Attribution-ShareAlike 4.0
International License.


## Contact

If you have any questions, you can contact me at <ffernandev@gmail.com>
