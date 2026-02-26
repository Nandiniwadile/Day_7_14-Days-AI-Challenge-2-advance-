📅 Day 7 – MLflow Experiment Tracking
🚀 14 Days AI Challenge

Platform: Databricks
Tool Used: MLflow
Model: Random Forest Classifier

📌 Objective

Implemented MLflow to:

Log experiment runs

Track parameters

Record evaluation metrics

Save trained model

📊 Step 1 – Data Preparation

Created Spark DataFrame

Generated feature vector using VectorAssembler

Split data into train and test sets

🌲 Step 2 – Model Training

Trained RandomForestClassifier

Used features column for prediction

Built binary classification model

📈 Step 3 – Model Evaluation

Used BinaryClassificationEvaluator

Metric: Area Under ROC Curve (AUC)

Achieved AUC Score: 1.0

🔍 Step 4 – MLflow Tracking

Started MLflow run

Logged parameter: model_type = RandomForest

Logged metric: AUC

Logged Spark model artifact

🎯 Key Learnings

Experiment tracking is essential in production ML

MLflow helps compare and manage multiple runs

Logging models makes deployment easier

