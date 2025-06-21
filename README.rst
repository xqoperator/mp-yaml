************************************************
mp-yaml: A simple parser of YAML for MicroPython
************************************************

This is a simple parser of a subset of the YAML grammar for MicroPython,
suitable for reading YAML configuration files.


Features
--------

* nested dictionaries with consistent indentation (4 spaces)
* scalars: strings, integers, floats, booleans, and nulls
* flat lists of scalar values
* inline comments (after values, using '#')
* automatic type conversion for scalars
* pretty-printing in either JSON or YAML format

Any features beyond those listed above, e.g., nested lists, multiline
strings, anchors, complex keys, inline dictionaries and complex YAML
syntax are not supported.


Requirements
------------

No external dependencies. This will run in both MicroPython and CPython.


Files
-----

* yaml.py:              The YAML parser
* pprint.py:            Pretty-print YAML or JSON
* stringbuilder.py:     similar to Java's StringBuilder
* config_loader.py:     A convenient application configuration loader
* test.py:              test file
* config.yaml:          sample YAML file used for test


Status
******

This is a first release and supports the features as described, but it has not
been extensively tested. 


Support & Liability
*******************

This project comes with no promise of support or acceptance of liability. Use at
your own risk.


Copyright & License
*******************

All contents Copyright 2020-2025 by Murray Altheim. All rights reserved.

Software and documentation are distributed under the MIT License, see LICENSE
file included with project.
