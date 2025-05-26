# Forest Fire Prediction Web App

A simple machine learning web app built with Flask to predict the risk of forest fires using environmental data.

## Dataset
Uses the **Algerian Forest Fires Dataset**, which includes temperature, humidity, wind, rain, and other factors to classify fire risk.

## How to Run

```bash
git clone https://github.com/AnmolAsija/Testforestfires.git
cd Testforestfires
pip install -r requirements.txt
python application.py

Then open http://127.0.0.1:5000 in your browser.

Key Files
application.py: Flask app
model_training.ipynb: ML model training
ridge_model.pkl: Trained model
templates/index.html: Web interface
