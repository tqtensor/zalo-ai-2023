# zalo-ai-2023

## Install libraries

```bash
pip install -U pip
pip install poetry
poetry install
poetry run python -m pip install torch==2.0.1 torchvision==0.15.2 torchaudio==2.0.2
poetry run python -m pip install --upgrade git+https://github.com/huggingface/transformers.git scipy
poetry run python -m ipykernel install --user --name=zalo-ai-2023
```

## Toml-sort

```bash
poetry run toml-sort -i pyproject.toml --no-sort-tables --sort-table-keys
```
