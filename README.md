* `adult_process.ipynb` processes `data/adult_og.csv` to give `data/adult_processed_small.csv` and `data/adult_processed.csv`.
* `adult_mst.ipynb` shows the maximum spanning tree based on mutual information.
* `adult_RF.ipynb` searches hyperparameters and finetunes a random forest.
* `adult_LR.ipynb` use principal component analysis to make train a logistic regression.
* `adult_synth.ipynb` trains the data synthesizer based on `adult_mst.ipynb`.
* `adult_fair.ipynb` calculates and compares the fairness scores of models on original dataset and synthetic datasets.

## Setup
```
conda env create -f environment.yml
mkdir model tmp
```
