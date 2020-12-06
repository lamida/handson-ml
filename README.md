# handson-ml
Notes and exercises from Hands-on ML Book

## Create the Workspace

Let's define the path and install venv and all the required libraries.
```
export ML_PATH="."
python3 -m venv ../venv
source ../venv/bin/activate
pip3 install jupyterlab matplotlib numpy pandas scipy scikit-learn
pip3 freeze > requirement.txt
```

Or in the rerun just run pip from requirement.txt.
```
pip3 install -r requirement.txt
```

Somehow I get this error
```
... invalid command 'bdist_wheel'
```

Therefore I just install wheel package

```
pip3 install wheel
```

Next let's run jupter lab

```
jupyter-lab
```
