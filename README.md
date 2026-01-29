# Python Calculator & Testing Demo 🧮

Welcome to the **Python Calculator Testing Demo**! This project is a sleek, lightweight implementation of core calculator functionalities, designed to demonstrate robust testing patterns in Python using both `unittest` and `pytest`.

Whether you're exploring Python testing frameworks or building your first CI/CD pipeline, you've come to the right place.

## 🚀 Features

- **Core Math Operations**: Clean implementation of addition and subtraction.
- **Dual Testing Suites**:
  - 🛠 **Unittest**: The standard library approach.
  - 🧪 **Pytest**: The modern, pythonic testing framework.

## 🛠️ Prerequisites

- Python 3.x installed on your machine.

## ⚡ Quick Start & Setup

Follow these steps to get your environment ready. We strongly recommend using a virtual environment (`venv`) to keep your dependencies isolated and your system clean.

### 1. Set up a Virtual Environment

Run the following command to create a virtual environment named `.venv` in your project directory:

```bash
python3 -m venv .venv
```

### 2. Activate the Virtual Environment

Activate the environment to start using it:

- **macOS / Linux**:
  ```bash
  source .venv/bin/activate
  ```

- **Windows**:
  ```bash
  .venv\Scripts\activate
  ```

> *You'll know it's working when you see `(.venv)` appear at the start of your terminal prompt.*

### 3. Install Dependencies

This project uses `pytest` for running modern test suites. Install it using pip:

```bash
pip install pytest
```

### 4. Manage Dependencies

If you install additional packages, you can save them to a `requirements.txt` file so others can easily install them:

```bash
pip freeze > requirements.txt
```

---

## 🧪 Running Tests

Verify code correctness using your preferred testing framework.

### Option A: Using `unittest` (Standard Library)

Run the built-in unit tests directly:

```bash
python3 test_calculator_unittest.py
```

### Option B: Using `pytest` (Recommended)

Run the pytest suite to see a more detailed and colorful test report:

```bash
pytest test_calculator_pytest.py
```

Or simply run all tests in the directory:

```bash
pytest
```

---

*Happy Coding!* 💻✨
