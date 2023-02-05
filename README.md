# envs
Environments for getting ML4GLand set-up on your machine

## `eugene_dev`

```bash
# Create the base Python -- need to clean up for poetry
conda create --name eugene_dev python=3.7 -y
conda activate eugene_dev

# EUGENe with all the bells and whistles
pip install eugene-tools[docs, dev, janggu, kipoi, meme]

conda install -c anaconda cudatoolkit=10.2
conda install -c anaconda git
python -m ipykernel install --user --name eugene_dev --display-name "Python 3.7 eugene_dev"

# Latest
pip install torch-tb-profiler
pip install ray
pip install seqgra
pip install evoaug gopher tfomics
pip install modisco
pip install hyperopt
pip install tensorboardx
pip install xgboost
pip install torchegranate
pip install einops
pip install torchinfo
pip install tune-sklearn
pip install modisco-lite --no-deps
pip install skorch
```

## gkm-svm

## memesuite

## HOMER
