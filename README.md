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
conda install nodejs==10.13.0
pip install ipywidgets==7.5.1 jupyterlab==2.1.0 environment-kernels==1.1.1
pip install -r requirements.txt
jupyter nbextension enable --py widgetsnbextension
jupyter labextension install @jupyter-widgets/jupyterlab-manager
jupyter lab
```
