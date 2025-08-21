# Healthcare-project
## 1. Open your project folder

Make sure all files are in place:

* app.py (Flask backend)

* model.pkl (trained ML model)

* templates/ (HTML files)

* static/ (CSS, JS, images)

* Dataset files (CSV or Excel, if needed)

🔹 2. Create and activate virtual environment (optional but recommended)
python -m venv venv
venv\Scripts\activate   # On Windows
source venv/bin/activate   # On Mac/Linux

🔹 3. Install dependencies

Inside your project folder, run:

pip install flask scikit-learn numpy pandas matplotlib


(If you used extra libraries, also install them: pip install joblib seaborn etc.)

🔹 4. Run your Flask app
<img width="1919" height="979" alt="image" src="https://github.com/user-attachments/assets/1990b535-15af-4201-a689-42b19fe7c578" />


## 5. Open in browser

After running, you’ll see something like:

 * Running on http://127.0.0.1:5000/


👉 Open this URL in your browser.
Your healthcare prediction web app will load.

🔹 6. Testing

Enter symptoms or required input.

Click Predict.

The model will use model.pkl and return the predicted disease with precautions/diet/medication details.
