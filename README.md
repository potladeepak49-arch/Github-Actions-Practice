# 🧮 Simple Calculator

A simple calculator project written in Python. It supports basic arithmetic operations and uses **GitHub Actions** to automatically run tests whenever code is pushed to GitHub.

## ✨ Features

* Addition
* Subtraction
* Multiplication
* Division
* Division-by-zero handling
* Automated testing with `pytest`
* Continuous Integration using GitHub Actions

## 📁 Project Structure

```text
my-calculator/
├── .github/
│   └── workflows/
│       └── calculator.yml
├── src/
│   └── calculator.py
├── tests/
│   └── test_calculator.py
└── README.md
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
cd YOUR-REPOSITORY
```

### 2. Install Python

Make sure Python 3.8 or newer is installed.

Check your version:

```bash
python --version
```

### 3. Install pytest

```bash
pip install pytest
```

### 4. Run the tests

```bash
pytest
```

## ⚙️ GitHub Actions

This project uses GitHub Actions for Continuous Integration.

The workflow is located at:

```text
.github/workflows/calculator.yml
```

The workflow automatically runs when you:

* Push code to the repository
* Create or update a pull request

GitHub Actions will:

1. Set up an Ubuntu environment.
2. Install Python.
3. Install `pytest`.
4. Run the calculator tests.
5. Report whether the tests passed or failed.

## 🧪 Example

```python
add(2, 3)
# Output: 5

subtract(5, 2)
# Output: 3

multiply(4, 3)
# Output: 12

divide(10, 2)
# Output: 5.0
```

## 📌 Technologies Used

* Python
* Pytest
* GitHub Actions
* YAML

