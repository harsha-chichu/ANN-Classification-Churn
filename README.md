# ANN-Classification-Churn

## Overview

This project focuses on building an Artificial Neural Network (ANN) for customer churn classification and deploying the model using Streamlit for a user-friendly interface. Customer churn prediction is a vital task for businesses to identify and retain at-risk customers by analyzing their demographic and behavioral data.

## Project Structure

```
ANN-Classification-Churn/
├── Churn_Modelling.csv          # Dataset used for training and evaluation
├── LICENSE                      # License file
├── README.md                    # Project documentation
├── app.py                       # Streamlit application for model inference
├── experiments.ipynb            # Jupyter notebook for model experimentation
├── label_encoder_gender.pkl     # Label encoder for 'Gender' feature
├── model.h5                     # Trained ANN model
├── one_hot_encoder_geo.pkl      # One-hot encoder for 'Geography' feature
├── prediction.ipynb             # Jupyter notebook for making predictions
├── requirements.txt             # List of dependencies
└── scaler.pkl                   # Scaler for feature normalization
```

## Features

- **Data Preprocessing:** Encoding categorical variables and scaling numerical features.
- **Modeling:** Implementation of an ANN using TensorFlow/Keras for binary classification.
- **Web App:** Streamlit-based interface for real-time predictions.
- **Deployment Ready:** Easily deployable Streamlit application.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/harsha-chichu/ANN-Classification-Churn.git
   cd ANN-Classification-Churn
   ```

2. **Create a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run the Streamlit application:**

   ```bash
   streamlit run app.py
   ```

2. **Access the web interface:**

   Open your web browser and navigate to `http://localhost:8501` to interact with the deployed model.

## Model Architecture

The ANN model consists of:

- **Input Layer:** Accepts the preprocessed features.
- **Hidden Layers:** Two dense layers with ReLU activation functions.
- **Output Layer:** A single neuron with a sigmoid activation function for binary classification.

## Results

- **Accuracy:** [Include accuracy metric here]
- **Precision:** [Include precision metric here]
- **Recall:** [Include recall metric here]
- **F1 Score:** [Include F1 score here]

Detailed results and visualizations can be found in the `experiments.ipynb` and `prediction.ipynb` notebooks.

## Technologies Used

- **Python:** Programming language
- **TensorFlow/Keras:** For building and training the ANN
- **Pandas and NumPy:** For data manipulation
- **Matplotlib and Seaborn:** For visualizations
- **Streamlit:** For deploying the web application

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the GPL-3.0 License. See the [LICENSE](LICENSE) file for details.
