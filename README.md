* `adult_process.ipynb` processes `data/adult_og.csv` to give `data/adult_processed_small.csv` and `data/adult_processed.csv`.
* `adult_mst.ipynb` shows the maximum spanning tree based on mutual information.
* `adult_*.ipynb` creates a model for later scoring use.
* `adult_synth.ipynb` trains the data synthesizer based on `adult_mst.ipynb`.
* `adult_fair.ipynb` calculates and compares the fairness scores of models on original dataset and synthetic datasets.

## Setup
```
conda env create -f environment.yml
mkdir model tmp
```
