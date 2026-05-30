# Landsat preprocessing lab

Jupyter Notebook для этапа предобработки снимков Landsat: загрузка каналов B3-B7, проверка геопривязки, чтение метаданных, band stacking, обработка нулевых значений и подготовка композитов.

## Запуск

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

На Windows:

```bash
.venv\Scripts\activate
```

Исходные Landsat-файлы нужно положить в папку:

```text
data/raw
```

Нужные файлы:

```text
*_SR_B2.TIF  опционально, для Natural Color
*_SR_B3.TIF
*_SR_B4.TIF
*_SR_B5.TIF
*_SR_B6.TIF
*_SR_B7.TIF
*_MTL.txt или *_MTL.json
```

Открыть и выполнить сверху вниз:

```text
landsat_preprocessing.ipynb
```

Крупные исходные и обработанные GeoTIFF-файлы не хранятся в Git.
