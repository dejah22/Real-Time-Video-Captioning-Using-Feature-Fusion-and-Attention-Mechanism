# Real Time Video Captioning Using Feature Fusion and Attention Mechanism

This repository contains the implementation code for the paper Real Time Video Captioning Using Feature Fusion and Attention Mechanism published in Springer's Signal, Image and Video Processing Journal.

[Link to the research paper](https://link.springer.com/article/10.1007/s11760-025-04622-6) for elaboration on rationale, methodology, testing, qualitative and quantitative analysis, as well the algorithm exposition. 

## Cite Us

[Link to the Research Paper](https://ceur-ws.org/Vol-3497/paper-136.pdf).

If you find our work useful in your research, don't forget to cite us!

```
@article{palaniappan2023concept,
  url = {https://ceur-ws.org/Vol-3497/paper-136.pdf},
  title={Concept Detection and Caption Prediction from Medical Images using Gradient Boosted Ensembles and Deep Learning},
  author={Palaniappan, Mirunalini and Bharathi, Haricharan and Chodisetty, Eeswara Anvesh and Bhaskar, Anirudh and Desingu, Karthik},
  year={2023},
  keywords={concept detection, caption prediction, natural language processing, computer vision ensemble, feature extraction, deep learning, automated image captioning},
  journal={Conference and Labs of the Evaluation Forum},
  publisher={Conference and Labs of the Evaluation Forum},
  ISSN={1613-0073},  
  copyright = {Creative Commons Attribution 4.0 International}
}
```
## Dataset
The Microsoft Research Video Description Corpus (MSVD) dataset is sourced for this work.
The dataset is obtained from Kaggle.

Video clips: https://www.kaggle.com/datasets/sarthakjain004/msvd-clips

Annotations: https://www.kaggle.com/datasets/vtrnanh/msvd-dataset-corpus

The training splits are obtained as specified in prior work [] from the following repository: 
https://github.com/albanie/collaborative-experts/blob/master/misc/datasets/msvd/README.md

## Software requirements
* Python3
* An environment for running Python notebooks such as Jupyter Notebook or Google Colaboratory
* Python libraries (as specified in `requirements.txt`. You can also install them directly into the notebook.)

## Hardware requirements
* GPU (for speed) (here, we use the T4 GPU provided by Google Colab)
* A decent processor with 12-16 GB RAM for training the model variations on a subset of MSVD comprising 755 training videos
* A much better GPU with much higher RAM for training the model on the entire MSVD dataset (here, we use the TPU with 343 GB RAM provided by Google Colab)
