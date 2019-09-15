# pydemo
## PyPA
[Python Packaging User Guide](https://packaging.python.org/)
## Build
`python setup.py build`
## Install
`python setup.py install`
## Usage
```
import pydemo
pydemo.init('testdemo')
```
## [Python Package Index](https://pypi.org/)
### whl
python setup.py sdist bdist_whell
### pypi
twine upload dist/*
