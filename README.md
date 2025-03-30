# Neural network for detecting malignant tumours in breast cancer: Machine Learning improving women healthcare

This project explores the real-world impact of Machine Learning through the implementation of a neural network from scratch, designed to classify breast cancer tumours as malignant or benign. By working directly with real medical data, it highlights how technology — when thoughtfully applied — can play a transformative role in human health and wellbeing.

Developed as part of the 42 Network training, the goal was not only to build a working multilayer perceptron, but to understand the mathematical foundations and practical challenges involved in designing AI systems from the ground up. The focus is on transparency, reproducibility, and clarity — key principles when working with data that affect real lives.

Machine Learning is not just about algorithms. It's about building tools that can support better decisions, empower medical professionals, and ultimately contribute to more equitable and accessible healthcare. This project is a small but meaningful step in that direction.

> This project was developed in **Google Colab**, which offers a powerful and accessible cloud-based environment for running Jupyter notebooks. Tools like **Colab** and **Amazon SageMaker Studio Lab** are essential for modern collaboration, allowing real-time sharing, team-based iteration, and seamless access to scalable computing — especially valuable in educational and research settings.

## Project structure

- `utils_perceptron.py`  
  Core Python module containing all the helper functions for forward propagation, backpropagation, activation functions, gradient descent, and model evaluation. All logic is built from scratch without using high-level ML libraries.

- `neuron_data_analysis.ipynb`  
  Jupyter notebook with exploratory data analysis of the breast cancer dataset. It includes data cleaning, feature exploration, distribution visualizations, and preparation steps for training and validation.

- `multilayer_perceptron.ipynb`  
  The main notebook where the multilayer perceptron is implemented and trained. It features two hidden layers, custom loss tracking, learning curves, and predictions. The results are visualized inline for full transparency.

- `data.csv`  
  The original dataset provided by the University of Wisconsin. It contains 32 features extracted from digitized images of fine needle aspirates of breast masses, including the diagnosis label.

- `data_training.csv` & `data_test.csv`  
  Training and test splits used for evaluating the performance of the model. These were generated from `data.csv` after cleaning and preprocessing.

- `original_paper_University_of_Wisconsin_Hospitals.pdf`  
  Original documentation describing the dataset’s structure and feature meanings, published by the University of Wisconsin. It is an essential reference to understand the domain and data context.

- `multilayer_perceptron_subject.pdf`  
  The original project brief from 42 Network, detailing the objectives, constraints, and evaluation criteria of the exercise. Key sections include:

### Highlights of the project
  - The network is coded entirely from scratch (no high level ML libraries).
  - Implement a multilayer perceptron with at least two hidden layers.  
  - Apply it to classify breast cancer tumours as benign or malignant.  
  - Include learning curves (loss and accuracy) during training.  
  - Use softmax in the output layer and binary cross-entropy as the loss function.  
  - Divide the data manually into training an

## Installation & Usage

To reproduce the environment and run the notebooks locally:

1. Clone the repository and navigate into the project folder.
2. (Optional but recommended) Create a virtual environment:
   python -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate on Windows
3. Install the required dependencies:
   pip install -r requirements.txt
4. Launch JupyterLab:
   jupyter lab


Alternatively, you can open the notebooks directly in Google Colab or SageMaker Studio Lab for a cloud-based, collaborative experience Just make sure to update the file paths accordingly.

