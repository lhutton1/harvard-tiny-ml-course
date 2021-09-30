# Harvard TinyML Course
Focuses on the fusion of machine learning and embedded systems. This course is split into three sections:

1. [Fundamentals of TinyML](https://www.edx.org/course/fundamentals-of-tinyml?index=product&queryID=e649f7e28b0aafae3a9225c518814c2e&position=10)
2. [Applications of TinyML](https://www.edx.org/course/applications-of-tinyml?index=product&queryID=e649f7e28b0aafae3a9225c518814c2e&position=19)
3. [Deploying TinyML](https://www.edx.org/course/deploying-tinyml?index=product&queryID=e649f7e28b0aafae3a9225c518814c2e&position=22) <-- Currently here

## Usage
### Setup python environment
This project consists of a number of Jupyter notebooks. Since a number of python packages are used to support this material, [Poetry](https://python-poetry.org/) has been used to manage dependencies.

1. First, [install poetry](https://python-poetry.org/docs/master/#installation) for your OS. We use version 1.1.10.

2. Verify poetry is installed.
```bash
poetry --version
```

3. Install dependencies.
```bash
poetry install
```

4. Activate virtual environment.
```bash
source $(poetry env info --path)/bin/activate
```

### Start Jupyter notebook
```bash
jupyter nbextension enable --py widgetsnbextension
jupyter notebook
```

## Acknowledgement
The content of these notbooks is largely based on learnings from the edX course freely available [here](https://github.com/tinyMLx). I recreated these notebooks purely for my understanding and education, adding additional notes along the way.
