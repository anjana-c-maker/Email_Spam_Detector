Spam Detection Machine Learning Model

Overview
This project focuses on detecting spam messages using machine learning. The system classifies messages as either spam or not spam (ham).

## Key Features
- Preprocesses text by cleaning, tokenizing, and lemmatizing.
- Uses TF-IDF for feature extraction.
- Trains a Logistic Regression model with hyperparameter tuning.
- Evaluates performance using accuracy and confusion matrix.

Steps
1. Data Preprocessing:
   - Cleans text by removing special characters and stop words.
   - Tokenizes and lemmatizes words.
2. Feature Extraction:
   - Applies TF-IDF vectorization with unigrams and bigrams.
3. Model Training:
   - Uses Logistic Regression.
   - Optimizes hyperparameters with GridSearchCV.
4. Evaluation:
   - Measures accuracy and visualizes results.

How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/spam-detection-project.git
   cd spam-detection-project
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open `Spam_Detection_Machine_Learning_Model.ipynb` in Jupyter Notebook or Google Colab and run all cells.

File Structure
```
project-folder/
|-- Spam_Detection_Machine_Learning_Model.ipynb   # Main notebook
|-- data/                                         # Dataset folder
|-- README.md                                     # Project description
|-- requirements.txt                              # Python libraries
```

Results
- Achieved high accuracy in detecting spam messages.

Future Work
- Add more models for comparison.
- Deploy the model as a web application.

License
This project is licensed under the MIT License.

