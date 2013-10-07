This repository will include a library of file manipulation modules.
Included will be modules that process files like JSON, XML, HTML, etc., and extract/process information 
from them in ways that are effective and practical.

At this time, the following programs are included:

Flattening_JSON.py:
This python recursive function flattens a JSON file or a dictionary with nested lists and/or dictionaries. 
The output is a flattened dictionary that use dot-chained names for keys, based on the dictionary structure. 
This allows for reconstructing the JSON structure or converting it to other formats without loosing 
any structural information. 
Example of output:  {a.b.c.d = 'string', f.e = 12,   etc.....} meaning that 'string' is inside 'd', 
who is inside 'c', who is inside 'b' who is inside 'a'.

