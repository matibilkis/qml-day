# 🚀 Quantum Machine Learning Hands-On Tutorial

<div align="center">

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![PennyLane](https://img.shields.io/badge/PennyLane-0.30+-purple.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)

**A hands-on tutorial on Quantum Machine Learning using PennyLane**

*Presented at the CVC QML Day Seminar*

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Ye4d8aDY_UbKHEEq7r_H8lEWIr82WJpO?usp=sharing)

</div>

---

## 📖 About

This repository contains a comprehensive hands-on tutorial on **Quantum Machine Learning (QML)** using [PennyLane](https://pennylane.ai/), an open-source Python library for quantum machine learning. The tutorial was presented at the **CVC QML Day Seminar** and covers:

- Basic concepts of quantum information and computing
- Quantum circuit design and optimization
- Quantum machine learning with PennyLane
- Practical examples with letter classification

## 🎯 Learning Objectives

By the end of this tutorial, you will:

- ✅ Understand the fundamentals of quantum computing
- ✅ Learn how to build quantum circuits using PennyLane
- ✅ Implement quantum machine learning models
- ✅ Train quantum circuits to classify patterns
- ✅ Explore quantum optimization techniques

## 🏗️ Repository Structure

```
qml-day/
├── database.ipynb          # Main tutorial notebook
├── alphabet/               # Letter pattern data
│   ├── letters.npy        # Letter patterns (A-Z)
│   └── binary_map.npy     # Binary encoding map
├── params/                # Trained model parameters
│   ├── model_3_initial.npy
│   ├── model_3_trained.npy
│   ├── model_5_initial.npy
│   └── model_5_trained.npy
├── figures/               # Tutorial figures and images
│   ├── bloch_sphere.png
│   ├── code_hands_on.png
│   ├── talk.png
│   └── tutorial.png
├── requirements.txt       # Python dependencies (pip)
├── environment.yml        # Conda environment file
├── LICENSE                # MIT License
├── .gitignore            # Git ignore file
└── README.md             # This file
```

## 🚀 Quick Start

### Prerequisites

- Python 3.8 or higher
- pip or conda package manager

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/qml-day.git
   cd qml-day
   ```

2. **Install dependencies:**
   
   Using pip:
   ```bash
   pip install -r requirements.txt
   ```
   
   Or using conda:
   ```bash
   conda env create -f environment.yml
   conda activate qml-day
   ```

3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook database.ipynb
   ```

   Or use JupyterLab:
   ```bash
   jupyter lab database.ipynb
   ```

### Alternative: Use Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Ye4d8aDY_UbKHEEq7r_H8lEWIr82WJpO?usp=sharing)

Click the badge above to open the notebook directly in Google Colab - no installation required!

## 📚 Tutorial Content

### Part 1: Data Preparation
- Creating letter patterns (A-Z) as 5×5 binary matrices
- Visualizing the alphabet dataset
- Binary encoding for quantum states

### Part 2: Basic Quantum Circuit
- Introduction to PennyLane
- Building simple quantum circuits with rotation gates
- Understanding quantum measurements and expectations

### Part 3: Quantum Machine Learning
- Training quantum circuits for pattern classification
- Using Adam optimizer for parameter optimization
- Cost function design for quantum learning

### Part 4: Advanced Circuits
- Multi-layer quantum circuits with entangling gates
- CNOT gates for quantum entanglement
- Training models for multiple pattern classification

## 🧪 Experiments

The tutorial includes three main experiments:

1. **Model 1**: Simple single-pattern classification
2. **Model 3**: Three-pattern classification with 4 layers
3. **Model 5**: Five-pattern classification with 5 layers

All trained model parameters are saved in the `params/` directory for easy loading and comparison.

## 📊 Results

The tutorial demonstrates how quantum circuits can learn to classify different letter patterns by mapping input angles to specific output patterns. The models achieve high accuracy in distinguishing between different letter encodings.

## 🔗 Resources

- **CVC QML Day Recording**: [Watch the presentation](https://www.cvc.uab.es/cvctv/?id=372)
- **Press Release**: [Read the article](https://www.cvc.uab.es/blog/2023/10/17/quantum-machine-learning-cvc-seminar/)
- **QML Research Group**: [Visit qml.cvc.uab.es](https://qml.cvc.uab.es/)
- **PennyLane Documentation**: [docs.pennylane.ai](https://docs.pennylane.ai/)
- **PennyLane GitHub**: [github.com/PennyLaneAI/pennylane](https://github.com/PennyLaneAI/pennylane)

## 🛠️ Technologies Used

- **[PennyLane](https://pennylane.ai/)**: Quantum machine learning framework
- **[NumPy](https://numpy.org/)**: Numerical computing
- **[Matplotlib](https://matplotlib.org/)**: Data visualization
- **[Jupyter Notebook](https://jupyter.org/)**: Interactive computing environment

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Contributors

This tutorial was created for the CVC QML Day Seminar. Special thanks to the Quantum Machine Learning research group at CVC.

## 🙏 Acknowledgments

- CVC (Computer Vision Center) for hosting the QML Day
- PennyLane team for the excellent quantum ML framework
- The quantum computing community for inspiration and resources

## 📧 Contact

For questions or feedback about this tutorial, please open an issue on GitHub or contact the CVC QML research group.

---

<div align="center">

**Made with ❤️ for the Quantum Machine Learning Community**

⭐ Star this repo if you find it helpful!

</div>
