# 2dgamer_dev

An intentionally **empty dummy package** used for testing PyPI CI/CD deployment. It does nothing functionally — no functions, no classes, no logic. It only exposes a version string.

## Installation

```bash
pip install 2dgamer_dev
```

## Verify the install

```bash
python -c "import gamer_dev; print(gamer_dev.__version__)"
```

Expected output:

```
0.1.0
```

## Note: PyPI name vs. import name

The **PyPI project name** is `2dgamer_dev`, but the **import name** is `gamer_dev`. PyPI package names may start with a digit, but Python module names cannot — so you install `2dgamer_dev` and import `gamer_dev`.

## License

MIT
