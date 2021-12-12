## Command to Run the MLflow Server

```
mlflow server \
--backend-store-uri sqlite:///mlflow.db \
--default-artifact-root ./artifacts \
--host 127.0.0.1 -p 1234
```
## After starting the Server you can run demo.py easily

```
python demo.py
```
