# Roadmap
![github pages](https://github.com/ymmmtym/roadmap/workflows/github%20pages/badge.svg?branch=main)

<https://ymmmtym.com/roadmap>

## Usage

### Local

activate python3 env

```bash=
git clone git@github.com:ymmmtym/roadmap.git
cd engneer-tutorial
python3 -m venv --clear .venv
. .venv/bin/activate
pip install -r requirements.txt
```

build

```bash=
python scripts/create_mkdocs.py
mkdocs build
```

run

```bash=
mkdocs serve -a 0.0.0.0:8000
```
