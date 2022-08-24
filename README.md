# edredo-App_vs_Web

## Preparation

### 1. Fork / Clone this repository

```bash
git clone https://github.com/SumitVermakgp/edredo-App_vs_Web.git
cd edredo-App_vs_Web
```


### 2. Create and activate virtual environment

Create virtual environment named `edredo`
```bash
python3 -m venv edredo
echo "export PYTHONPATH=$PWD" >> edredo/bin/activate
source edredo/bin/activate
```
Install python libraries

```bash
pip install --upgrade pip setuptools wheel
pip install -r requirements.txt
```

Add Virtual Environment to Jupyter Notebook

```bash
python -m ipykernel install --user --name=edredo
``` 

Configure ToC for jupyter notebook (optional)

```bash
jupyter contrib nbextension install --user
jupyter nbextension enable toc2/main
```

## 3. Run Jupyter Notebook

```bash
jupyter notebook
```

