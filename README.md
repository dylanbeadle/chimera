# Chimera
> If You Want To Go Fast, Go Alone. If You Want To Go Far, Go Together

Scratchboard to brainstorm ML approaches and document findings.

### Notebook Format

+ Submit new notebook with numerical 8-character string as directory in /notebooks/0000000N
+ Submit readme.txt file in root to outline main strategy or notes regarding notebook for cover explanation.
+ Freeform name for actual notebook file, and as many notebooks within notebook directory
+ Least amount of included dependencies to eliminate repo bloat

### Stack Setup

+ Python (2.7.11)
[Install Python](https://www.python.org/downloads/)

+ PIP
``` bash
# Mac OS X install PIP if not already
$ sudo easy_install pip
```

+ TensorFlow
``` bash
# Mac OS X, CPU only, Python 2.7:
$ export TF_BINARY_URL=https://storage.googleapis.com/tensorflow/mac/cpu/tensorflow-0.11.0rc1-py2-none-any.whl
sudo pip install --upgrade $TF_BINARY_URL
```

+ Keras
``` bash
sudo pip install keras
```

+ Scikit Learn
``` bash
pip install -U scikit-learn
```
