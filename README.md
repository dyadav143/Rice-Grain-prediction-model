🌾 Rice Grain Variety Classification using Machine Learning
This project aims to classify different rice grain varieties based on their image features using traditional machine learning models. It leverages a dataset of labeled rice grain images to extract meaningful features and build predictive models for accurate classification.

📌 Project Description
The goal of this project is to automate the identification of five rice varieties—Arborio, Basmati, Ipsala, Jasmine, and Karacadag—using image-based feature extraction and machine learning techniques. This model can be useful in agricultural supply chains, food quality assurance, and rice variety authentication.

🧠 Features & Capabilities
Image processing and feature extraction (size, shape, texture, color).

Exploratory Data Analysis (EDA) and visualization.

Implementation of ML models:

Naive Bayes

Decision Tree

Random Forest

Perceptron

Model evaluation using accuracy, confusion matrix, and classification reports.

Clean and modular Python codebase.

Option to save and load models using pickle.

📁 Dataset
Total images: 75,000

Varieties: Arborio, Basmati, Ipsala, Jasmine, Karacadag

Images per class: 15,000

Each image contains a top-down view of a rice grain on a plain background.

🛠️ Tech Stack
Language: Python

Libraries:

scikit-learn

matplotlib, seaborn

pandas, numpy

OpenCV (for image processing)

🚀 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/rice-classifier.git
cd rice-classifier
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the main script:

bash
Copy
Edit
python main.py
Evaluate models and view results.

📊 Results
Best accuracy: 0.79

Random Forest gave the highest performance among traditional models.

🧩 Folder Structure
bash
Copy
Edit
rice-classifier/
│
├── dataset/                # Contains image data
├── features/               # Extracted feature CSVs
├── models/                 # Pickled models
├── notebooks/              # EDA and experiments
├── main.py                 # Main pipeline
├── utils.py                # Helper functions
└── README.md


📌 Future Work
Add deep learning models (CNNs) for better accuracy.

Deploy as a web app using Flask or Streamlit.

Real-time grain classification using a webcam.
