# MeasurementKit Python bindings

First you need to install MeasurementKit on your system. On a MacOS
system you can use the [brew
tap](https://github.com/bassosimone/homebrew-measurement-kit) to
install the *development version* (currently 0.3.0-dev).

Then,

```
virtualenv venv
source venv/bin/activate
pip install twisted
python setup.py install
python tests.py
```