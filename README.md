![Python Version Check (3.6-3.8)](https://github.com/ms234/OxfordRSECourse/workflows/Python%20Version%20Check%20(3.6-3.8)/badge.svg)
![OS Check](https://github.com/ms234/OxfordRSECourse/workflows/OS%20Check/badge.svg)
[![codecov](https://codecov.io/gh/ms234/OxfordRSECourse/branch/master/graph/badge.svg)](https://codecov.io/gh/ms234/OxfordRSECourse)

# OxRSE Continuous Integration course

This project contains a small Python project. We are going to use free cloud services to automate:

- unit testing on multiple Python versions
- unit testing on multiple operating systems
- coverage testing
- static analysis
- documentation generation

To make sure all dependencies are installed, we recommend creating a new virtual environment.
From the directory containing this file:

```bash
python3 -m pip install --user virtualenv
python3 -m venv venv
```

Activate the virtual environment:

Linux / macOS:
```bash
source venv/bin/activate
```

Windows cmd.exe:
```bash
venv\Scripts\activate.bat
```

Windows PowerShell:
```bash
venv\Scripts\Activate.ps1
```

Windows using Git Bash:
```bash
source venv\Scripts\activate
```

Upgrade the build tools and install this project:

```bash
pip install --upgrade pip setuptools wheel
pip install -e .[dev,docs]
```

## Documentation
You can create documentation automatically using sphinx and https://readthedocs.org/. This creates a webpage which will host the docs and will automatically be updated if you update the docs on git.
