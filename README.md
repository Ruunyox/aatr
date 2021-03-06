# aatr
Amino Acid Translator
---
AATR is a simple bash script that translates a three letter amino acid sequence 
obtained from a PDB file and outputs the equivalent single letter sequence. The reverse may also be done. It is
meant to be used as a command line tool like `sed` (in fact, the tool is built entirely
on it), so you may keep it in your `/bin/` if you wish to use as a tool in other 
scripts. 
#### Usage
```bash
    usage:

    aatr [opts] [string]
        [--one]     conversion to one letter code
        [--three]   conversion to three letter code
```
#### Example
```bash
WULF_CTRL:\> ./aatr --one 'ALA LEU LYS ALA GLU GLU GLN'
ALKAEEQ
```
```bash
WULF_CTRL:\> ./aatr --three 'ALKAEEQ'
ALA LEU LYS ALA GLU GLU GLN
```
