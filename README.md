# patoisfencer8s-kit

Validate JSON files and print a normalized form.

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m patoisfencer8s_kit.cli --help
```

```python
from patoisfencer8s_kit.core import Patoisfencer8sTool

tool = Patoisfencer8sTool()
print(tool)
```

## Layout

```
patoisfencer8s_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 patoisfencer8s
