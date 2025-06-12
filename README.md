<h1 align="center">
  <br>
   Classification of Alzheimer's Disease by Magnetic Resonance Imaging with an Ensemble Approach
  <br>
</h1>

<p align="center">
  <a href="https://colab.research.google.com/drive/1YDYlQTR0PTn49DHRDMpXE_wpvTR3HWir?usp=sharing" target="_blank" rel="noopener noreferrer"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>
  &nbsp;
  <a href="https://wandb.ai/gustaph/sbcas-ensemble/" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Weights_&_Biases-FFCC33?logo=weightsandbiases&logoColor=black" alt="Weights & Biases"></a>
</p>
</p>

Published on XXV Simpósio Brasileiro de Computação Aplicada à Saúde (SBCAS)

Link to the manuscript:

- 

### Authors

- [Gustavo S. Silva]()
- [Omar A. C. Cortes]()
- [Antonio F. L. Jacob Jr.]()

### Abstract
Alzheimer's Disease (AD), affecting over 55 million people globally, demands reliable diagnostic tools. Single-model approaches using CNNs and traditional ML face critical limitations. This study proposes two frameworks: a stacking-CNN ensemble (VGG-16, ResNet-101, DenseNet-121) and two voting ML ensembles (Voting[all]: KNN, RF, SVC, LR, XGBoost; Voting[few]: KNN, RF, XGBoost). Evaluated on 6,400 MRIs, Voting[few] achieved the highest classification metrics (97.8\% accuracy; 0.984 MCC; 93.8\% F1macro), outperforming individual CNNs, validated through Friedman-Nemenyi tests. Results suggest, in this context, that simpler ML models might better capture the inherent characteristics of MRI data for AD diagnosis.

### Citing this work
```

```

### Dataset
```
@dataset{alzheimer_mri_dataset,
  author = {Falah.G.Salieh},
  title = {Alzheimer MRI Dataset},
  year = {2023},
  publisher = {Hugging Face},
  version = {1.0},
  url = {https://huggingface.co/datasets/Falah/Alzheimer_MRI}
}
```
