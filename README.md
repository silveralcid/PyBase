<a id="readme-top"></a>

<div align="center">
  <h1>🐍 PyBase</h1>
  <p><em>A clean, framework-agnostic Python project scaffold for professional development and rapid prototyping.</em></p>

  <p>
    <a href="https://github.com/sillveralcid/pybase">View on GitHub</a> ·
    <a href="https://github.com/sillveralcid/pybase/issues">Report Bug</a> ·
    <a href="https://github.com/sillveralcid/pybase/issues">Request Feature</a>
  </p>
</div>

## 🚀 About

**PyBase** is a lightweight Python scaffold preconfigured with modern development tools:

- **black** – formatting  
- **isort** – import sorting  
- **flake8** – linting  
- **mypy** – static type checking  
- **pytest** – testing  
- **pre-commit** – automated code quality  
- **Makefile** – consistent developer commands (`make lint`, `make test`, etc.)

Use this as your base for any Python project — from quick scripts to FastAPI or Django applications.

## 🧱 Getting Started

### Prerequisites
- Python ≥ 3.11 (managed via `pyenv` recommended)
- Git
- (Optional) `make` for automated commands

### Installation
```bash
git clone https://github.com/sillveralcid/pybase.git my_project
cd my_project
python -m venv .venv
pip install -r requirements.txt
pre-commit install
````

Then verify:

```bash
make lint
make test
```

## ⚙️ Usage

When you clone **PyBase** for a new project:

1. Update this README — replace “PyBase” with your project’s name.
2. Change Git remote:

   ```bash
   git remote remove origin
   git remote add origin https://github.com/<yourname>/<yourproject>.git
   ```
3. Start coding.

## 🧩 Makefile Commands

| Command                | Description                                               |
| ---------------------- | --------------------------------------------------------- |
| `make lint`            | Run black, isort, and flake8                              |
| `make test`            | Run pytest                                                |
| `make clean`           | Remove cache and build files                              |
| `make check-tools`     | Show tool versions                                        |
| `make run file=app.py` | Run a specific script                                     |
| `make typecheck`       | Run mypy for type validation                              |
| `make coverage`        | Run pytest with coverage report (if pytest-cov installed) |

## 🧰 Toolchain Summary

| Tool           | Purpose                     |
| -------------- | --------------------------- |
| **black**      | Auto-format code            |
| **isort**      | Sort imports                |
| **flake8**     | Linting & style enforcement |
| **mypy**       | Type checking               |
| **pytest**     | Testing framework           |
| **pre-commit** | Git hooks for auto-checks   |
| **make**       | Unified command interface   |

## 🪪 License

Distributed under the MIT License.
See [`LICENSE`](LICENSE) for details.

## 👤 Contact

**Silver Alcid** - [LinkedIn](https://www.linkedin.com/in/silveralcid/) | [silveralcid@outlook.com](mailto:silveralcid@outlook.com)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
