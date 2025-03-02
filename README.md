## How to run project

### 1. Download Contents
Computer Vision Masterclass - Udemy

### 2. Create New Python Virtual Environment
```bash
python -m venv venv
```

### 3. Activate Python Virtual Environment
```bash
venv\Scripts\activate
```

### 4. Register Python Venv Into Notebook
```bash
python -m ipykernel install --user --name=venv --display-name "Computer Vision Masterclass (venv)"
```

### 5. Install Project Requirements
```bash
pip install -r requirements.txt
```

### 6. Install Any Additional Files Required
```bash
python -m pip install dlib-19.24.99-cp312-cp312-win_amd64.whl
```

### 7. Save Your Project Dependencies With
```bash
pip freeze > requirements.txt
```

### 8. Open Jupyter Notebook
```bash
jupyter notebook
```