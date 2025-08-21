# Healthcare Prediction project
## 1. Open your project folder

Make sure all files are in place:

* app.py (Flask backend)

* model.pkl (trained ML model)

* templates/ (HTML files)

* static/ (CSS, JS, images)

* Dataset files (CSV or Excel, if needed)

## 2. Install dependencies

Inside your project folder, run:
pip install flask, scikit-learn, numpy, pandas, matplotlib.

(If you used extra libraries, also install them: pip install joblib seaborn etc.)

 ## 3. Change the directories to your folder
 Open the windows powershell in your pc.
 Use "cd Desktop", "cd <your project folder name>". Like this navigate to your project folder here i have used this name for my project.
 * cd Desktop
 * cd MH
 * cd MH
 * cd flask-my-app.

## 4. Run your Flask app
By using the command " $env:FLASK_APP = "app" "," python -m flask run".
<img width="1919" height="979" alt="image" src="https://github.com/user-attachments/assets/1990b535-15af-4201-a689-42b19fe7c578" />

## 5. Open in browser

After running, you’ll see something like:
 * Running on http://127.0.0.1:5000/
 Open this URL in your browser.
Your healthcare prediction web app will load.
<img width="1919" height="969" alt="image" src="https://github.com/user-attachments/assets/dc649751-8f16-4898-b0c2-4f1a6a6d8f6e" />

## 6. Testing
Enter symptoms as per the data you used.
eg: shivering, itching, etc,...
Click Predict.

The model will use model.pkl and return the predicted disease with precautions/diet/medication details.
