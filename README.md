# SwiftSecured: Credit Card Fraud Detection with Machine Learning

SwiftSecured is a full-stack web application powered by machine learning to detect credit card fraud in real time. The application uses a trained machine learning model integrated into a Flask backend and provides an easy-to-use frontend built with HTML, Tailwind CSS, and JavaScript. The project also stores prediction history using SQLite, making it a fully operational fraud detection tool for web users.

## Table of Contents

- [Tech Stack](#tech-stack)
- [How It Works](#how-it-works)
- [Key Features](#key-features)
- [Future Plans](#future-plans)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Tech Stack

- **Frontend**: HTML, Tailwind CSS, JavaScript
- **Backend**: Python Flask
- **Machine Learning Model**: Trained on Kaggle Credit Card Fraud Dataset
- **Database**: SQLite
- **Deployment**: Render.com

## How It Works

1. **Input Transaction Data**: User inputs anonymized transaction data.
2. **Data Processing**: The data is sent to the Flask backend via JavaScript.
3. **Fraud Prediction**: The trained machine learning model predicts whether the transaction is fraudulent or not.
4. **Prediction History**: The result (Fraud or Not Fraud) is stored in the SQLite database along with the timestamp.
5. **History Log**: Users can view a history of their prediction logs.

## Key Features

- **Real-time Fraud Prediction**: Detect fraudulent transactions instantly using a trained machine learning model.
- **Responsive UI**: Built with Tailwind CSS, the application has a modern, mobile-first, and responsive design.
- **Prediction History**: All predictions are stored and displayed with timestamps for future reference.
- **Flask Backend**: Uses Flask to handle requests and serve the machine learning model predictions.
- **SQLite Database**: Stores transaction predictions and other user data in a secure database.
- **Deployed and Accessible**: Hosted on Render.com, making it accessible from anywhere.

## Future Plans

- Add a user login/register system for personalized predictions.
- Develop an Admin Dashboard to visualize prediction analytics.
- Upgrade the ML model using advanced techniques like XGBoost/LightGBM for better accuracy.
- Enable PDF export for prediction reports.
- Migrate the database to PostgreSQL for better scalability and production-level use.
- Integrate an email notification system for fraud detection alerts.
- Implement CI/CD pipelines for seamless deployment updates.
- Add a dark/light mode toggle for enhanced user experience.

## Installation

To get started with **SwiftSecured**, follow the steps below:

### Prerequisites
- Python 3.x
- Flask
- SQLite
- Tailwind CSS (for frontend)

### Clone the Repository
```bash
git clone https://github.com/surajsri23/Swiftsecured.git
cd Swiftsecured
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Run the Application
```bash
python app.py
```

## Once the application is running, you can open it in your browser at 
```
http://127.0.0.1:5000
```

### Usage
- Visit the live demo at SwiftSecured Live Demo.

- The application allows users to input anonymized credit card transaction data and receive a prediction on whether the transaction is fraudulent or not.

- Users can also view past predictions in the prediction history section.

### Contributing
We welcome contributions to SwiftSecured! If you have suggestions, fixes, or new features, feel free to fork the repo and submit a pull request. To contribute:

1. Fork the repo.

2. Create a branch (git checkout -b feature-branch).

3. Commit your changes (git commit -m 'Add new feature').

4. Push to the branch (git push origin feature-branch).

5. Create a new pull request.

### License
- This project is licensed under the MIT License - see the LICENSE file for details.

- SwiftSecured is developed and maintained by Suraj Srivastav.

- Email: srivastavsuraj230@gmail.com
- GitHub: surajsri23
