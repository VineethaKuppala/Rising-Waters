# Flood Prediction Using Machine Learning

## Project Overview

The Flood Prediction System is a web application that predicts the possibility of flooding based on environmental parameters using a Machine Learning model. The application is developed using Flask for the backend and HTML/CSS for the frontend. The trained model provides fast and accurate predictions to assist in early flood risk assessment.

---

## Features

- Predicts flood occurrence using Machine Learning.
- User-friendly web interface.
- Fast prediction results.
- Flask-based web application.
- Responsive frontend using HTML and CSS.

---

## Technologies Used

- Python
- Flask
- HTML
- CSS
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Pickle

---

## Project Structure

```
Project Development Phase/
│
├── data/
├── model/
│   ├── flood_model.pkl
│   └── scaler.pkl
├── static/
│   └── style.css
├── templates/
│   └── index.html
├── app.py
├── predict.py
├── train_model.py
└── requirements.txt
```

---

## Installation

1. Clone the repository.

2. Navigate to the project directory.

3. Install the required libraries.

```
pip install -r requirements.txt
```

4. Run the Flask application.

```
python app.py
```

5. Open your browser and visit:

```
http://127.0.0.1:5000/
```

---

## How to Use

1. Open the application in your browser.
2. Enter the required environmental parameters.
3. Click the **Predict** button.
4. View the flood prediction result.

---

## Future Enhancements

- Integration with real-time weather APIs.
- Deployment on cloud platforms.
- Interactive dashboard for visualization.
- Improved prediction accuracy using larger datasets.

---

## Authors

- PM Priya (Team Lead)
- Vineetha Kuppala (Member)
- Sushma Kotluru (Member)
- Deepthi Subramanyam (Member)

---

## License

This project is developed for academic and educational purposes.
