# TebaloDev
PIP developer package of tebalodev - Temperature, Battery and Load aware frequency governor.

## Installation


```bash
chmod +x dependency.sh
python dependency.sh
pip install tebalodev
```

**Note**: You may need to make 


## Usage

```py
from tebalodev import utils

utils.get_current_frequency()
```

## Developers Note

To upload the package

```bash
python setup.py sdist bdist_wheel upload
```