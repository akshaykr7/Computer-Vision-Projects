# Image-Anomaly-Detection using PatchCore library

MVTec AD dataset - [kaggle link](https://www.kaggle.com/datasets/ipythonx/mvtec-ad?select=hazelnut)

1. Code using Anomalib library - code_anomalib.ipynb 
2. Code from scratch - code_scratch.ipynb

[Anomalib docs](https://anomalib.readthedocs.io/en/v1.0.1/)

Anomalib library is a collection of state-of-the-art image anomaly detection algorithms like PatchCore, PaDiM, EfficientAD.

![alt text](Images/000.png)


Steps for running code_anomalib.ipynb

- pip install --upgrade --force-reinstall pip==24.0
- pip install -r requirements.txt
- pip install anomalib==1.0.1
- Check version. pip=24.0 and python=3.10
- Restart kernel after installing all libraries.
- check dataset_root, according to your data.
- Use MVTecAD-anomalib data given here, 
- You can use your custom dataset also, directory name should be same as in MVTecAD-anomalib folder.
- Further, check anomalib docs for detailed explanation.


Steps for running code_scratch.ipynb
- No specific library required. Works well on kaggle notebook and Google colab.
- Use MVTecAD-scratch data or any custom dataset but it should be in same format.