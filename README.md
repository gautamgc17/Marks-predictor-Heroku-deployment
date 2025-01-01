## Marks Predictor: Heroku Deployment
This repository demonstrates how to deploy a **Marks Predictor** using a **Linear Regression** model on **Heroku** with **Flask** as the backend framework.

### Features
- Predicts student marks based on the number of study hours.
- Deployed on Heroku: https://predicting-marks.herokuapp.com/ 

### Files and Structure
- `app.py`: Flask application script.
- `lin_reg_model.pkl`: Pre-trained Linear Regression model.
- `templates/`: Contains HTML templates for the web interface.
- `Procfile`: Configures Heroku deployment.
- `requirements.txt`: Lists dependencies for the project.

### Deployment Steps
- Ensure all dependencies in `requirements.txt` are installed.
- Use the `Procfile` for Heroku configuration.
- Deploy the repository to Heroku using the CLI or GitHub integration.
