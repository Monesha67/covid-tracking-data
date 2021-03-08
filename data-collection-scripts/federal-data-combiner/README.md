# federal-data-combiner

Combine federal testing, hospitalization, and case/death data into single state-level output.

This script is saved as a Jupyter notebook because it's intended to be run from Google Colab.

Usage:
```shell script
pip install -r requirements.txt
jupyter nbconvert --to python combine.ipynb  # convert jupyter notebook to python
python combine.py  # outputs to federal-covid-data-DATE.csv
python combine.py STDOUT  # outputs to STDOUT
```