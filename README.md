
# Pylogger

A small python logger 'package' that I like to import into projects. It provides a global logger, with optional subloggers. It is essentially a wrapper for the python logging library.

## How to use

Download the repo into your project.

Import the logger into your files.

```python
from pylogger.logger import log
```

You can then use any of the different warning levels to log messages

```python
log.debug("This is some handy debug information")
log.info("The answer to life, universe and everything is 42")
log.warning("Wait, where's Barry?")
log.error("Thanks for all the fish!")
log.critical("Time to panic.")
```

