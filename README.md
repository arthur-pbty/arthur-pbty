pip install poetry
poetry init

This command will guide you through creating your pyproject.toml config.

Package name [test]:  stephrobert
Version [0.1.0]:
Description []:
Author [Stephane Robert <stephane.robert.28@gmil.com>, n to skip]:  n
License []:
Compatible Python versions [^3.10]:

Would you like to define your main dependencies interactively? (yes/no) [yes] no
Would you like to define your development dependencies interactively? (yes/no) [yes] no
Generated file

[tool.poetry]
name = "stephrobert"
version = "0.1.0"
description = ""
authors = ["Your Name <you@example.com>"]
readme = "README.md"

[tool.poetry.dependencies]
python = "^3.10"


[build-system]
requires = ["poetry-core"]
build-backend = "poetry.core.masonry.api"


Do you confirm generation? (yes/no) [yes]
