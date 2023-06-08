# Module 4: Deployment

**Deployment methods:**

1) Batch preds (offline) - run at regular interval
2) Online - web service (immediate prediction at a users request)
3) Online - streaming 

**Deployment as a web-service**

- Creating a virtual environment with Pipenv
- Creating a script for predictiong
- Putting the script into a Flask app
- Packaging the app to Docker

**Deployment as a web-service with mlflow registry**

- Take the code from the previous video
- Train another model, register with MLflow
- Put the model into a scikit-learn pipeline
- Model deployment with tracking server
- Model deployment without the tracking server
