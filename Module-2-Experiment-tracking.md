# Module-2: Experiment tracking notes

### Overview:
- ML expriements tracking
- Source code
- Data
- Model
- Hyperparameters
- Metrics

**Why is it important?**
- Reproducibility
- Organization
- Optimization
- Collaboration

**MLflow Commands:**

| Command    |  Function  |
|------------|------------|
|artifacts   | Upload, list, and download artifacts from an MLflow... |
|db          | Commands for managing an MLflow tracking database. |
|deployments | Deploy MLflow models to custom targets. |
|doctor      | bPrints out useful information for debugging issues with MLflow.|
|experiments | Manage experiments.|
|gc          | Permanently delete runs in the deleted lifecycle stage.|
|models      | Deploy MLflow models locally.|
|recipes     | Run MLflow Recipes and inspect recipe results.|
|run         | Run an MLflow project from the given URI.|
|runs        | Manage runs.|
|sagemaker   | Serve models on SageMaker.|
|server      | Run the MLflow tracking server|


**MLflow tracking:**

1) MLflow server tracking UI
2) Exp. tracking and metrics storage (Backend server)
3) Model artifact storage

**MLflow features:** 

1) Tracking UI
2) Parameters, metrics and artifact storage
3) Model management
4) Model registry
5) MLflow Projects

**Registry workflow:**

staging —> prod —> archive

**MLflow in diff scenarios:**

1) No tracking server, params/metrics in local filesys and models in local filesys
2) Local server, params/metrics in backend db, artifacts in local filesys
3) Remote server, params/metrics in backend db, artifacts in S3 buckets


**Local server experiment tracking:**

![Screenshot 2023-05-25 192120](https://github.com/avikumart/mlops-zoomcamp-codes-notes/assets/88608935/55289832-1a0d-4e41-85cf-59f99ac440c5)

