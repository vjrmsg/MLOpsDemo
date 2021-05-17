```conda create -n MLOPSDemo python=3.9 -y
```conda activate MLOPSDemo
```create requirements.txt
```pip  install --trusted-host pypi.org --trusted-host pypi.python.org --trusted-host files.pythonhosted.org -r requirements.txt
```template.py 
```git init
```dvc init
```dvc add data_given/winequality.csv
```conda install pywin32
```git add . && git commit -m "added new directories"
...........

mlflow server --backend-store-uri sqlite:///mlflow.db --default-artifact-root ./artifacts --host 0.0.0.0 -p 1234