# weppy-Sentry

weppy-Sentry is an extension for the [weppy framework](http://weppy.org) providing an integration with the [Sentry](https://getsentry.com) error reporting platform.

[![pip version](https://img.shields.io/pypi/v/weppy-sentry.svg?style=flat)](https://pypi.python.org/pypi/weppy-Sentry) 

## Installation

You can install weppy-Sentry using pip:

    pip install weppy-Sentry

And add it to your weppy application:

```python
from weppy_haml import Sentry

app.use_extension(Sentry)
```

## Documentation

The complete documentation is available on the [weppy extensions registry](http://weppy.org/extensions/sentry).

## License

weppy-Sentry is released under BSD license. Check the LICENSE file for more details.
