# Python Courses

1. [Introduction to Python](https://github.com/hslu-dda/colabor-uncreative-machines-2025/blob/main/python-courses/1-Introduction-To-Python.ipynb)
2. [Introduction to Text and NLP](https://github.com/hslu-dda/colabor-uncreative-machines-2025/blob/main/python-courses/2-Text-and-NLP-in-Python.ipynb)


## Setup to Work Locally

Make sure that you have Python 3.11.5 installed. 

Open the python-courses folder in VS code. Create and activate a virtual env using the built in terminal. 


```sh
python -m venv .venv
```

Activate the environment (this creates a Python kernel to run the notebook on)

```sh
source .venv/bin/activate
```

Install dependencies

```sh
pip install --upgrade pip
pip install -r requirements.txt
```

To exit the virtual environment
```sh
deactivate
```

To update the requierments.txt if necessary

```sh
pip freeze > requirements.txt
```