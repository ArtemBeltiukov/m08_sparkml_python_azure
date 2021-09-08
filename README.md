GitHub: https://github.com/ArtemBeltiukov/m08_sparkml_python_azure
* Deploy infrastructure with terraform
```
terraform init
terraform plan -out terraform.plan
terraform apply terraform.plan
....
terraform destroy
```
* Copy notebook and data into Databricks cluster
* Execute all the steps from "ML End-to-End Example" notebook

Import data from your local machine into the Databricks File System (DBFS)
![img_1.png](screenshots/img_1.png)
Visualize the data using Seaborn and matplotlib
![img.png](screenshots/img.png)
![img_2.png](screenshots/img_2.png)
![img_3.png](screenshots/img_3.png)
Run a parallel hyperparameter sweep to train machine learning models on the dataset
![img_4.png](screenshots/img_4.png)
![img_5.png](screenshots/img_5.png)
Explore the results of the hyperparameter sweep with MLflow

Register the best performing model in MLflow
![img_6.png](screenshots/img_6.png)

Apply the registered model to another dataset using a Spark UDF
![img_7.png](screenshots/img_7.png)

Set up model serving for low-latency requests
![img_8.png](screenshots/img_8.png)
![img_9.png](screenshots/img_9.png)

