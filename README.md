# Action-Decision-Network-ADN-for-Visual-Tracking
(https://arxiv.org/pdf/2002.05709.pdf) <br>
Kaan Yarali (ky2446)

### Framework used: TensorFlow 
### GPUs used: V100
### Platform: GCP and Google Colab

### GCP image configuration
Operating System : Deep Learning on Linux
Version: Debian 10 based Deep Learning VM for PyTorch CPU/GPU with CUDA 11.0 M90


In this paper, we implement a rendition of the ActionDecision Network for visual tracking using deep reinforcement learning. The original network architecture combines Supervised Learning (SL), Reinforcement Learning (RL), and a form of online adaptation to train a deep network visual tracker. The network is trained to learn actions for moving and scaling a tracking bounding box across frames over a video. State is defined as the enclosed
bounding box image patch.  <br>


