# Stationarity analysis (6 time series)

## Что внутри
- `Stationarity_Analysis.ipynb` — ноутбук с анализом и приведением рядов к стационарности (ADF + KPSS).
- `Series/` — исходные CSV (6 файлов).
- `requirements.txt` — зависимости.

## Как запустить локально
```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```