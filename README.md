# Demo GitHub Actions
A basic Python repository demonstrating automatic testing with GitHub Actions.

## Project Structure
```
.
├── src/
│   ├── __init__.py
│   └── calculator.py
├── tests/
│   ├── __init__.py
│   └── test_calculator.py
├── requirements.txt
└── README.md
```

## Installation
```bash
pip install -r requirements.txt
```

## Running Tests
```bash
pytest
```

## Running Tests with Coverage
```bash
pytest --cov=src tests/
```
