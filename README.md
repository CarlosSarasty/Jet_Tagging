## Jet Tagging with Machine Learning

Jet_Tagging is a repository for classifying particle jets using the JetNet dataset. It applies machine learning techniques to differentiate between jet origins, such as quarks and gluons, based on their substructure properties. 

🚧 **This project is under active development! Expect updates and improvements.** 🚧

Key Features:

Model Architectures: Includes implementations of various neural network architectures.

Training Pipelines: Provides scripts and configurations to train models on jet datasets, with support for hyperparameter tuning and performance monitoring.

Evaluation Metrics: Offers tools to assess model performance using standard metrics in particle physics, ensuring reliable and interpretable results.


### Results and Visualizations  

Below are key performance visualizations from **binary** and **multi-class classifiers**.  

### Confusion Matrices  
These confusion matrices illustrate the classification performance of the models.  

<div align="center">  
  <table>  
    <tr>  
      <td align="center"><strong>Binary Classifier (Quark vs Gluon)</strong></td>  
      <td align="center"><strong>Multi-Class Classifier</strong></td>  
    </tr>  
    <tr>  
      <td><img src="images/Quark_Gluon_BC.png" width="400"></td>  
      <td><img src="images/confusion_matrix_res_autoencoder.png" width="400"></td>  
    </tr>  
  </table>  
</div>  

### Directories and Files

- **README.md:** Project documentation and instructions.
- **config/:** Configuration files for various setups.
- **data/:** Scripts and utilities for handling datasets.
- **evaluation/:** Evaluation scripts and results.
- **images/:** Generated figures and plots.
- **launch_project.py:** Script to launch the project.
- **models/:** Directory for model definitions and architectures.
- **scripts/:** Miscellaneous scripts for different tasks.
- **summary/:** Summaries and logs of training runs.
- **trainers/:** Training scripts and utilities.
- **utils/:** Utility functions and helpers.

## Getting Started

### Prerequisites

- Jetnet (https://github.com/jet-net/JetNet.git) 
- Python 3.10
- Pytorch 2.4.1


### Download

1. Clone the repository:
    ```sh
    git clone git@github.com:CarlosSarasty/Jet_Tagging.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Quark_Gluon_Classifier
    ```

### Usage

To launch the project, run:
```sh
python launch_project.py config/config.yaml
```

## Citations  

### JetNet  
- **JetNet GitHub Repository**: [JetNet](https://github.com/jet-net/JetNet)  
- **Paper**:  
  Kansal, R., Duarte, J., Su, H., Orzari, B., Tomei, T., Pierini, M., Touranakou, M., Vlimant, J-R., & Gunopulos, D.  
  *Particle Cloud Generation with Message Passing Generative Adversarial Networks*,  
  Advances in Neural Information Processing Systems, Vol. 34, 2021.  
  [Paper Link](https://proceedings.neurips.cc/paper_files/paper/2021/file/c8512d142a2d849725f31a9a7a361ab9-Paper.pdf) | [arXiv:2106.11535](https://arxiv.org/abs/2106.11535)  


