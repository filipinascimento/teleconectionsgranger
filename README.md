# Software for Detecting climate teleconnections with Granger causality

This repository holds a collection of python notebooks that can be used to replicate the findings of the paper *Detecting climate teleconnections with Granger causality*.

## Link to publications
- TBD

## Authors
- Filipi N. Silva
- Didier A. Vega-Oliveros
- Xiaoran Yan
- Alessandro Flammini
- Filippo Menczer
- Filippo Radicchi
- Ben Kravitz
- Santo Fortunato

## How to use

- First download the preprocessed data from TBD and save it in `Data` Folder.
- Use the `CalculateMetrics` notebook to calculate lagged correlation and Granger Causality.
- Use the `ValidateMetrics` notebook to evaluate the metrics according to the El Ninõ and La Niña ground truths.
- Use the `DrawMaps` notebook to construct a figure with the data.
- You can load your own data by loading and converting it in the `ParseData` notebook. 

### Data
The `Data` folder contains example output data used in the article for Granger Causality (`Causality_d7_l<maxLag>_v3.csv`) and Lagged Correlation (`Causality_d30_l<maxLag>_v3.csv`).

### Dependencies
Dependencies are listed in `requirements.txt`.

## TODO
 - Make it modular and release it as a pyPI package.


## Citing this work or software
If you use the processed data or any of the scripts in a publication, please cite the respective works listed here.
