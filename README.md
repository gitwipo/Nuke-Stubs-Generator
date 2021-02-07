# Nuke-Stubs-Generator

A stubs generator for Nuke to provide stubs for IDE autocomplete support.

# Usage

```python
import nukeStubs
nukeStubs.generate()
```

By default, generate will output **nuke.py** and **nukescripts.py** files to your home directory under a stubs folder, but it takes an optional argument like, and will write the files there instead.

```python
nukeStubs.generate('your/output/directory')
```

# Setting up your IDE

Simply add your stubs folder to your IDE's pythonpath so that it can index this stubs file.


# Original Authors

This script was written by Dhruv Govil, loosely based on the work done by Sebastien Elsner (http://www.nukepedia.com/python/misc/nukepydummy).
