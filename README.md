## Quick start
```
git clone git@github.com:kittipatkampa/dhamma-pipeline.git
pyenv install 3.9
pyenv local 3.9

poetry env use 3.9.17
poetry install
poetry shell
```

Generate requirements.txt
```
poetry export --without-hashes --format=requirements.txt > requirements.txt
```

## Jupyter notebook
```
poetry run jupyter lab
```

## Streamlit app
```
poetry run streamlit run simple_app.py
```