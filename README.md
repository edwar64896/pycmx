# pycmx
Python CMX3600 Edit Decision List Parser

The `pycmx` package provides a basic interface for parsing a CMX3600 EDL.

Features:
* The major variations of the CMX3600, the standard, "File32" and "File128" 
  formats are automatically detected and properly read.
* Remark or comment fields with common recognized forms are read and 
  available to the client, including clip name and source file data.

## Usage

```
Python 3.7.1 (default, Nov  6 2018, 18:46:03) 
[Clang 10.0.0 (clang-1000.11.45.5)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> import pycmx
>>> pycmx.parse_cmx3600("INS4_R1_010417.edl") 
```

## Should I Use This?

At this time, this is (at best) alpha software and the interface will be 
changing often. It may be fun to experiment with but it is not suitable
at this time for production code.

Contributions are welcome and will make this module production-ready all the
faster! Please reach out or file a ticket! 
