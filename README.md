# gambit-yaml


Read GAMBIT YAML files in Python. Why? GAMBIT YAML files contain lists as YAML keys and an !import keyword, that isn't supported out of the box
by Python YAML libraries.

## Install
```bash
pip install git+https://github.com/GambitBSM/gambit-yaml
```

## Use
```python
import gambit_yaml

with open("gambit_yaml.yaml") as f:
    data = gambit_yaml.load(f)
```

