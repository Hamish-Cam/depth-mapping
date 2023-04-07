# A machine learning approach for remote peat depth mapping: a case study in the East Anglian Fens

 [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
 <a href="https://github.com/psf/black"><img alt="Code style: black" src="https://img.shields.io/badge/code%20style-black-000000.svg"></a>

For replication of results, the required datasets can be downloaded from [here](https://doi.org/10.5281/zenodo.7808203). All code within this repository is written in Python and is formatted in Jupyter Notebooks. This allows easy annotation and allows researchers to make their own changes easily. The notebooks should be run in the order: 
  1. [preprocessing.ipynb]() - downloads additional datasets from Google Earth Engine and samples all predictors at field data point locations to make the tabular dataset required for further modelling. 
  2. [modelling.ipynb]() - carries out the feature selection process and applies a random forest and neural network model for the task of peat thickness prediction. 
  

## Abstract
Peatlands account for just 2.84% of land area worldwide but provide a terrestrial carbon store around twice
as large as global forest biomass. Within the UK, the East Anglian Fenlands offer one of the highest per area
mitigation opportunities in the country. However, a current lack of low-cost, accurate and scalable methods
for assessing the costs and benefits of regeneration projects is crippling potential investment. Advances in
remote sensing technologies and machine learning algorithms, such as random forest and neural network
models, offer a new and exciting solution to this problem. One of the key factors in determining the
potential benefits of a peatland regeneration project, is understanding the depth of peat currently present.
This project explores the viability of utilising a machine learning model for this purpose, trained using
open-source datasets and existing field data collections. Such approaches have seen success in tropical and
intact peatland ecosystems, but have never been applied within the Fens. The models produced during
the project show poor prediction capabilities for unseen data, highlighting the need for active peat depth
measurement tools such as gamma radiometric and airborne electromagnetic surveys, which are currently
unavailable for the fenland region.


## Contributors 
### Author

- Campbell, Hamish. *(AI4ER Cohort-2021, University of Cambridge)*

### Supervisors

- Coomes, David. *(Cambridge Centre for Landscape Regeneration, University of Cambridge)*

- Aldred, Oscar. *(Cambridge Centre for Landscape Regeneration, University of Cambridge)*

- Keshav, Srinivasan. *(Cambridge Centre for Landscape Regeneration, University of Cambridge)*
