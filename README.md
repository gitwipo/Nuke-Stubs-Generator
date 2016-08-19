# Nuke-Stubs-Generator

A stubs generator for Nuke to provide stubs for IDE autocomplete support.

# Usage

```python
import nukeStubs
nukeStubs.generate()
```

By default, generate will output a **nuke.py** file to your home directory under a stubs folder, but it takes an optional argument like, and will write the file there instead.

```python
nukeStubs.generate('your/output/directory')
```

# Setting up your IDE

Simply add your stubs folder to your IDE's pythonpath so that it can index this stubs file.


# Authors

This script was written by Dhruv Govil, loosely based on the work done by Sebastien Elsner (http://www.nukepedia.com/python/misc/nukepydummy).
