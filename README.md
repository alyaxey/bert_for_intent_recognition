# BERT for intent recognition
Model:
 - bert-base-uncased
 - positive linear combination of all layer outputs
 - dense layer on top
 - multisample dropout https://arxiv.org/abs/1905.09788

To run use commands:
```
conda create -n bert_for_ir python=3.7
conda activate bert_for_ir
pip install -r requirements.txt
jupyter nbextension enable --py widgetsnbextension
jupyter labextension install @jupyter-widgets/jupyterlab-manager
jupyter lab
```
