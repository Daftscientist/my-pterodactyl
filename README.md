# My Pterodactyl

[![License](https://img.shields.io/badge/license-Apache%202.0-blue)](https://github.com/Daftscientist/my-pterodactyl/blob/master/LICENSE)
[![Build Status](https://travis-ci.org/Daftscientist/my-pterodactyl.svg?branch=master)](https://travis-ci.org/Daftscientist/my-pterodactyl)
[![Coverage Status](https://coveralls.io/repos/github/Daftscientist/my-pterodactyl/badge.svg?branch=master)](https://coveralls.io/github/Daftscientist/my-pterodactyl?branch=master)

A brief description of your project.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Plugin System](#plugins)
- [Contributing](#contributing)
- [License](#license)

## Features

### Made with compatibility in mind 
- Built with SQLAlchemy, allowing for connections to `SQLite`, `Postgresql`, `MySQL`, `Oracle`, `MS-SQL`, `Firebird`, `Sybase`.
### Plugin system
- Ingegrated, out-the-box [plugin support](#plugins).
### Contributor focused
- Built with documentation, comments and moduled. This allows for easy contribiution.

## Installation

Download the files:
```shell
git clone https://github.com/Daftscientist/my-pterodactyl
```
Unzip the downloaded files:
Ubuntu: ```unzip my-pterodactyl-main.zip -d my-pterodactyl-main```
Windows: ```zip file. tar -xf my-pterodactyl-main.zip```
Check if python is installed:
```shell
python –version
OR
python3 -version
```
Make sure PIP package manager is installed:
```shell
python -m pip --version
OR
python3 -m pip --version
```
Run the backend API:
```shell
cd Backend
sanic main
```
Use `ctrl+c` to stop the backend running.

### Development tips

Running the backend API with live reloading (e.g. watchdog):
```shell
cd Backend
sanic main --dev
```
Running the backend API in debug mode:
```shell
cd Backend
sanic main --debug
```
You can combine `sanic main --dev --debug` for development.

## Usage
Explain how to use your project. Provide examples or code snippets to demonstrate its functionality.

```python
import my_pterodactyl
```

## Examples
Tests
Describe how to run the automated tests for your project. Provide any details about the testing framework used.


## Contributing
We welcome contributions from the community! To contribute to this project, please follow the guidelines below:

Fork the repository and create your branch.
Set up the development environment.
Make your changes and test thoroughly.
Submit a pull request, clearly describing the changes you've made.
Please make sure to follow our code of conduct and be respectful to all contributors.

## License
This project is licensed under the Apache License 2.0.
