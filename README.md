# NHL Game Outcome Predictor

This project is a Neural Network model built using TensorFlow/Keras to predict the outcome of NHL games based on game statistics. The model is trained on various game features like goals, assists, shots, hits, and power-play goals. It has been deployed as a web app using Streamlit.

## Model Description

The model is a Multi-layer Artificial Neural Network (ANN) with the following architecture:
- Input Layer: Accepts 7 features (goals, assists, shots, hits, etc.).
- Hidden Layers: 
  - First hidden layer with 10 neurons and ReLU activation.
  - Second hidden layer with 5 neurons and ReLU activation.
- Output Layer: A single neuron with a sigmoid activation for binary classification (whether the team wins or loses).
  
The model is trained using the Adam optimizer and binary cross-entropy loss function, and it achieves decent accuracy on test data.

## How to Run the App Locally

### Prerequisites

To run the app locally, you need to have the following installed:

- Python 3.7+
- pip (Python package manager)

### Setup Instructions

1. Clone the repository:

   ```bash
   git clone (https://github.com/Nick-Maitland/DeployingAIAssignment2)
2. Install required dependencies:
   pip install streamlit tensorflow pandas numpy scikit-learn

4. run terminal for installed folder:
   streamlit run app.py
