# Real Time Video Captioning Using Feature Fusion and Attention Mechanism

This repository contains the implementation code for the paper Real Time Video Captioning Using Feature Fusion and Attention Mechanism published in Springer's Signal, Image and Video Processing Journal.

[Link to the research paper](https://link.springer.com/article/10.1007/s11760-025-04622-6) for elaboration on rationale, methodology, testing, qualitative and quantitative analysis, as well the algorithm exposition. 

## Cite Us

[Link to the Research Paper](https://ceur-ws.org/Vol-3497/paper-136.pdf).

If you find our work useful in your research, don't forget to cite us!

```
@article{chandran2025real,
  title={Real-time video captioning using feature fusion and attention mechanism},
  author={Chandran, KR and Madhusankar, Dejah and Swaminathan, Krithika},
  journal={Signal, Image and Video Processing},
  volume={19},
  number={12},
  pages={1--11},
  year={2025},
  publisher={Springer}
}
```
## Motivation
The increasing prevalence and volume of short-form video content and real-time multimedia has made live video captioning indispensable. Consequently, there is a rising demand for autonomous systems that can understand the observed scene and describe it for applications ranging from large-scale content-indexing to live-commentary systems. Effective scene understanding requires precise object identification along with contextual interpretation of object interactions. 

## Dataset
The Microsoft Research Video Description Corpus (MSVD) dataset is sourced for this work.
The dataset is obtained from Kaggle.

Video clips: https://www.kaggle.com/datasets/sarthakjain004/msvd-clips

Annotations: https://www.kaggle.com/datasets/vtrnanh/msvd-dataset-corpus

The training splits are obtained as specified in prior work from the following repository: 
https://github.com/albanie/collaborative-experts/blob/master/misc/datasets/msvd/README.md

## Software requirements
* Python 3.9
* TensorFlow 2.13, (Keras library)
* Keras-Preprocessing 1.0.8
* NumPy 1.23
* h5py 3.14.0
* Ultralytics 8.1.47 YOLOv8
  
## Hardware requirements
* **Training**
  * GPU with more than 40GB RAM (here, we use the T4 GPU with 343GB RAM for training the full MSVD dataset)
  * GPU with 12-16 GB RAM for training the model variations on a subset of MSVD comprising 755 training videos.
* **Testing**
  * (CPU/GPU/TPU) with min 8GB RAM: Better processor, faster the output :p

## Key Highlights

### Results
