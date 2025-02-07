# Advanced-Machine Learning

![License](https://img.shields.io/badge/License-GNU-blue?style=for-the-badge)
![CMP9137](https://img.shields.io/badge/Course-CMP9137-purple?style=for-the-badge)
[![VERSION](https://img.shields.io/badge/VERSION-0.1.0-COLOR.svg?style=for-the-badge&logo=LOGO)](<LINK>)
![Build Status](https://img.shields.io/badge/build-failing-red?style=for-the-badge)
![Container Size](https://img.shields.io/badge/Container%20Size-<1GB-blue?style=for-the-badge&logo=docker)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/Yolo-0078D7?style=for-the-badge&logo=Yolo&logoColor=white)
![AI](https://img.shields.io/badge/AI-0078D7?style=for-the-badge&logo=AI&logoColor=white)
 

## Build the workspace

Unzip or clone the [project file](https://github.com/Nditah/advanced-ml) 

Ensure that your Docker service is running, then open the project folder with VS Code.

VS Code will propmt you to reopen as a container. Accept and watch the logs on terminal

Select the Correct Interpreter: This is the most important step!

    - Open the command palette in VS Code (Ctrl+Shift+P or Cmd+Shift+P).
    - Type `Python: Select Interpreter` and choose the command.
    - VS Code should show you a list of available Python interpreters. Make sure you select the one inside your dev container. It will likely be something like `/usr/local/bin/python` or a path within your .venv (if you're using one). Crucially, it must be the Python interpreter where you installed the packages.


### Run Tests

1. Run all tests:

```bash
python -m unittest discover -s tests
```
2. Run all tests in a specific file:

```bash
python -m unittest tests.foo
```

3. Run a specific test case:
```bash
python -m unittest tests.foo.Class
```

4. Run a specific test method:
```bash
python -m unittest tests.foo.Class.function
```


## Week 1



## Week 2





## Project Structure

- `src/`: Source code for the project default `src`.
- `models/`: Models for processing or prediction.
- `scripts/`: Program files to run processing or checks
- `tests/`: Unit tests for the project.
- `assets/`: Contains images and other assets for the project.
- `requirements.txt`: List of dependencies.
- `README.md`: Project documentation.
- `.devcontainer/`: Configuration for the development container.

```
workspace/
│
├── .devcontainer/
│   ├── devcontainer.json
│   └── Dockerfile
│
├── src/
│   ├── Preprocessor.py
│   ├── DiseaseID.py
│   ├── FishDisease.py
│   ├── Preprocessor.py
│   ├── ReferenceMaker.py
│   ├── Segmenter.py
│   └── main.py
│
├── models/
│   ├── foo.pt
│   └── bar.pt
│
│
├── scripts/
│   ├── foo.py
│   ├── bar.py
│   ├── foo1.py
│   └── bar1.py
│
├── tests/
│   ├── test_foo.py
│   ├── test_bar.py
│   ├── test_foo1.py
│   └── test_bar1.py
│
├── assets/
│   └── images/
│       └── pictures/
│
├── requirements.txt
└── README.md
```

# advanced-ml
