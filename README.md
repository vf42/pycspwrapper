# pycspwrapper
Version 0.1.1

Python wrapper for Latvian official statistics portal API: https://stat.gov.lv/lv/api-un-kodu-vardnicas/api

Forked from https://github.com/kirajcg/pyscbwrapper/, replacing the Sweden API endpoints with the Latvian Central Statistics Bureau ones.

Dependencies: requests>=2.21.0

To install: 
```python
pip install pycspwrapper
```

To import: 
```python
from pycspwrapper import LVStat
```

For info on usage, see the included notebooks.

## Changelog

News in version 0.1.4:
Caching info data while in the same location. Updated examples in Latvian and English.

News in version 0.1.3:
Updated query generation code to use variable and value codes instead of text values.

News in version 0.1.2:
Fixed the module name to avoid conflicts with the original version.

News in version 0.1.1:
Bugfixes: Variables with space in their names can now be accessed by removing the spaces.
New functionality: get_variables() returns a dict instead of only writing to the terminal.

News in version 0.1:
Compatible with changes in the API.  
Includes a function for generating JSON queries from user-supplied input.  
It is now possible to go up and down in the metadata tree more than one step at a time.
