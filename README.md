# PyPI Package Cookiecutter Template

This repository provides a Cookiecutter template for creating Python packages ready to be uploaded to PyPI. It includes integration with GitHub Actions to automatically publish new versions to PyPI.

## Features
* Standard Python package structure
* Automatic GitHub Actions setup for:
    * Building and uploading packages to PyPI when a new tag is created

* Configuration with pyproject.toml
* Support for common licenses and README
* Support for unittest/pytest

## Installation
First, install Cookiecutter if you haven't already:
```
pip install cookiecutter
```

## Usage
To generate a new project based on this template, run:
```
cookiecutter gh:ibonn/pypi-package-template
```
This will prompt you for basic information like package name, description, license, etc. and generate a ready-to-use directory structure.

## Publishing to PyPI
1. Make sure your code is ready and versioned
2. Create a tag on GitHub
    ```
    git tag v0.1.0
    git push origin v0.1.0
    ```
3. GitHub Actions will automatically build and publish the package to PyPI

## Customization
You can modify the files within the template to suit your needs. The GitHub Actions configuration is located in `.github/workflows/`

## Contributions
Contributions are welcome! If you have suggestions or improvements, open an issue or submit a pull request

## License
This project is licensed under the MIT License.

## Reference
This template was presented as part of a talk at **Python Bilbao**. Follow them on:
* [![GitHub](https://img.shields.io/badge/GitHub-%23181717.svg?style=flat&logo=github&logoColor=white)](https://github.com/pythonbilbao)
* [![Telegram](https://img.shields.io/badge/Telegram-%2326A5E4.svg?style=flat&logo=telegram&logoColor=white)](https://t.me/pythonbilbao)
* [![Meetup](https://img.shields.io/badge/Meetup-%23ED1C40.svg?style=flat&logo=meetup&logoColor=white)](https://www.meetup.com/python-bilbao/)
