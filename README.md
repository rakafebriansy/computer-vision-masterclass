## How to run project

### 1. Download Contents
https://drive.google.com/drive/folders/1fnn6e8q7Ykp7nqOPWGeSiijlNTt_kkPL

### 2. Activate Python Virtual Environment
```bash
venv\Scripts\activate
```


### 3. Register Python Venv Into Notebook
```bash
python -m ipykernel install --user --name=venv --display-name "Python (venv)"
```

### 4. Save Your Project Dependencies With
```bash
pip freeze > requirements.txt
```

### 5. Open Jupyter Notebook
```bash
jupyter notebook
```