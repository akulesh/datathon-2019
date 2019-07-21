# Datathon 2019: Explanation of machine learning models predictions
Materials for my talk at Datathon 2019 (Minsk)

**keywords**: black box, interpretability, LIME, SHAP, ELI5, InterpretML, local explanation, feature importance  

# Short description
We discuss the problem of interpreting “black boxes”, models that are commonly used to solve a wide range of applied problems. We talk about importance of this topic, what methods and tools exist, how to use them when solving problems of supervised learning (customer churn prediction), and what strengths/weaknesses these approaches have.

Slides: [PDF](https://github.com/akulesh/datathon-2019/blob/master/Datathon.%20Models%20Explanation.pdf)  
Code: [Notebook](https://github.com/akulesh/datathon-2019/blob/master/explanation-of-model-predictions.ipynb) | [HTML](https://raw.githubusercontent.com/akulesh/datathon-2019/master/explanation-of-model-predictions.html)(with outputs)

# Setup
If you use `conda`:
1. create and activate your working environment:
```
conda create --name myenv python
conda activate myenv
conda install nb_conda  # to use env with jupyter
conda install -c conda-forge ipywidgets  # add widgets
```
2. install required packages:
```
pip install -r requirements.txt
```
