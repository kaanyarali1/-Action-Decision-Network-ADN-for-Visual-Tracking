# Action-Decision-Network-ADN-for-Visual-Tracking
Kaan Yarali (ky2446)
## A Simple Framework for Contrastive Learning of Visual Representations 
(https://arxiv.org/pdf/2002.05709.pdf) <br>
## Unsupervised Feature Learning via Non-Parametric Instance Discrimination 
(https://arxiv.org/pdf/1805.01978v1.pdf) <br>

### Framework used: PyTorch 
### GPUs used: A100, V100, and P100 
### Platform: GCP and Google Colab

### GCP image configuration
Operating System : Deep Learning on Linux
Version: Debian 10 based Deep Learning VM for PyTorch CPU/GPU with CUDA 11.0 M90

All the model weights trained on this project can be found in this Google Drive Link. 
(https://drive.google.com/drive/folders/1LSGz-WAi87WbF3gI0tIVFgv8V136nhv3?usp=sharing)

All the training logs on this project can be found in this Google Drive Link.
(https://drive.google.com/drive/folders/1bR-6sMhYgHrqFsHZCSm5rjxC75F7j0MX?usp=sharing)

For example commands for this project, check the notebooks under the example-notebooks section. I also pushed the notebooks used for training.


In this project, "A Simple Framework for Contrastive Learning of Visual Representations" and "Unsupervised Feature Learning via Non-Parametric Instance Discrimination" are implemented. Labeling data is a very challenging process since it is expensive, time-consuming and can make privacy issues. Recently, self-supervised learning has been heavily used to model the representation of the unlabeled data, without any human annotation. The goal of this project is to train the models using a self-supervised learning approach to learn good feature representations with unlabeled data and compare their performance with the models trained in fully supervised learning fashion. <br>
