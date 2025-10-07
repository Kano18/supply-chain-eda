# EDA

Perform an EDA on supply chain data set to explore business insights.

## Quickstart

```bash
# Create project from template
cookiecutter path/to/this/template

# cd into project
cd eda

# Create env (optional) and install deps
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt

# Launch Jupyter
jupyter lab
```

## Structure

```
eda/
├── data/                      # put your datasets here (default: DataCoSupplyChainDataset.csv)
├── notebooks/
│   └── EDA_notebook.ipynb
├── src/eda/
│   ├── __init__.py
│   └── utils.py
├── requirements.txt
├── .gitignore
└── LICENSE
```

## Notes

- This starter targets **Jupyter notebooks** using **panel** stack (Panel/Plotly/Seaborn).
- Replace sample paths with your real dataset names (default is DataCoSupplyChainDataset.csv).
