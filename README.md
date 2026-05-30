# Запуск
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook

## Для запуска ноутбука нужно:
1) Создать папку `data/raw`
2) Закинуть в нее файлы, которые подготовил Федя
3) Запустить по порядку ячейки в `landsat_preprocessing.ipynb`