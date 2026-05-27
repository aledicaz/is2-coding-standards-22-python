# loan-eligibility-python

Loan eligibility calculator for a cooperativa de ahorro y crédito. Computes whether a member is eligible for a loan and at what rate, based on income, debt, employment, and savings history.

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Run the tests

```bash
pytest
```

## Use it from the CLI

```bash
python -m loan.cli --income 1200 --debt 320 --tenure-months 18 --age 34 --savings-balance 850
```

## Linter

- Herramienta: Pylint
- Versión: 4.0.5
- Perfil: configuración por defecto de Pylint (sin desactivar reglas en .pylintrc)
- Reporte HTML: generado con pylint-json2html y guardado en reports/initial.html y reports/final.html

