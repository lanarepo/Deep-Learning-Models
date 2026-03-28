# Deep Learning Models
##### Brief Introduction to Deep Learning
<p> A Modular Journey Through Neural Architectures
Welcome to the Deep Learning Repo, a curated collection of deep learning implementations designed for clarity, modularity, and rapid learning. Instead of a monolithic library, this repository breaks down complex architectures into isolated, "bite-sized" folders.

Whether you are a developer looking to understand the math behind the layers or a student building your first neural network, this repo provides the blueprint.
  </p>
  <p>
Most deep learning repositories suffer from "dependency spaghetti." This project takes a different approach:
<ul>
    <li> Encapsulation: Each model lives in its own directory with its own logic.</li>
    <li> Minimalism : We strip away the boilerplate to focus on the core architecture and training loops.</li>
    <li> Reproducibility: Every folder contains a sample dataset loader and a training script that works out of the box.</li>
</ul>
</p>

#### Essential Toolkits:
<ul>
  <li>Tensorflow</li>
  <li>Keras</li>
  <li>SKLearn</li>
  <li>PyTorch</li>
  <li>DL4J</li>
  <li>Caffe</li>
  <li>Microsoft Cognitive Toolkit</li>
 </ul>

🛠️ Getting Started
1. **Clone the Repository**: 
Bash
git clone https://github.com/your-username/deep-learning-models.git
cd deep-learning-models

2. **Set Up Your Environment**:
We recommend using a virtual environment to keep your dependencies clean:
Bash
python -m venv venv
source venv/bin/activate  Or `venv\Scripts\activate` on Windows
pip install -r requirements.txt

3. **Run a Model**:
Navigate to any folder and start training:
Bash
cd CNN_Vision
python train.py --epochs 10

Learning Roadmap:
This repo is designed to be followed in order. Start with the MLP Foundations to understand how gradients flow, then move to CNNs for spatial data, and eventually tackle the complexity of Self-Attention in the Transformers directory.

Tip: Check the common/ folder for shared utilities like custom plotting functions to visualize your loss curves and feature maps in real-time.

🤝 Contributing
Found a bug or want to add a new model (like Diffusion or GNNs)? Contributions are welcome! Please open an issue or submit a pull request with a clean, documented implementation.
