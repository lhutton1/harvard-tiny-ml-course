# Harvard TinyML Course
Focuses on the fusion of machine learning and embedded systems. This course is split into three sections:

1. [Fundamentals of TinyML](https://www.edx.org/course/fundamentals-of-tinyml?index=product&queryID=e649f7e28b0aafae3a9225c518814c2e&position=10)
2. [Applications of TinyML](https://www.edx.org/course/applications-of-tinyml?index=product&queryID=e649f7e28b0aafae3a9225c518814c2e&position=19)
3. [Deploying TinyML](https://www.edx.org/course/deploying-tinyml?index=product&queryID=e649f7e28b0aafae3a9225c518814c2e&position=22) <-- Currently here

## Usage
The project uses jupyter notebooks.

Setup virtual environment in project root:
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Enable widgets to be displayed and start jupyter server:
```bash
jupyter nbextension enable --py widgetsnbextension
jupyter notebook
```

## Acknowledgement
The content of these notbooks is largely based on learnings from the edX course freely available [here](https://github.com/tinyMLx). I recreated these notebooks purely for my understanding and education, adding additional notes along the way.
