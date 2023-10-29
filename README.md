# Documentation Templates

### 🤠 Data Fix

[Template](data_fix.md) to document a change in data.

We strive to avoid manipulation of production data. 
Still it may come to a situation when, because of a program bug, 
some data becomes corrupted and requires a manual correction. 
It can lead to further errors as offen done without testing and under stress and time pressure. 
Documenting manual data fix can help to avoid problems, as it supports:

- prepare fix before it is done, so that it can be reviewed / tested / run
- information about fix and its date is easily available
- changed records can be traced
- change can be easily repeated if necessary
