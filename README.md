
# Python Project started

## To Get Started

```console
git clone https://github.com/HarshitJoshi9152/DarkChess
cd DarkChess
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r .\dev-requirements.txt
pre-commit install
```

## Hooks List:

- `check-toml`: Lints and corrects your TOML files.
- `check-yaml`: Lints and corrects your YAML files.
- `end-of-file-fixer`: Makes sure you always have an empty line at the end of your file.
- `trailing-whitespaces`: Removes whitespaces at the end of each line.
- `python-check-blanket-noqa`: Forbids you from using noqas on large pieces of code.
- `isort`: Runs ISort.
- `flake8`: Runs flake8.
