---
model_name: "Transformer Models" 
vector_length: 'Depends on model.' 
paper: "https://arxiv.org/abs/1910.03771"
repo: "https://huggingface.co/transformers/pretrained_models.html",
installation: "pip install vectorhub[encoders-text-torch-transformers-auto]"
example="""
#pip install vectorhub[encoders-text-tf-transformers]
from vectorhub.encoders.text.tf_transformers import TFTransformer2Vec
model = TFTransformer2Vec('bert-base-uncased')
model.encode("I enjoy taking long walks along the beach with my dog.")"""
---

## Description

These are Tensorflow Automodels from HuggingFace.