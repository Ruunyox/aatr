# aatr
Amino Acid Translator
---
AATR is a simple bash script that translates an three letter amino acid sequence 
obtained from a PDB file and outputs the equivalent single letter sequence. The reverse may also be done. It is
meant to be used as a command line tool like `sed` (in fact, the tool is built entirely
on it), so you may keep it in your `/bin/` if you wish to use as a tool in other 
scripts. 
### usage
```bash
    usage:

    aatr [opts] [string]
        [--one]     conversion to one letter code
        [--three]   conversion to three letter code
```
### example
```bash
WULF_CTRL:\> ./aatr --one 'ALA LEU LYS ALA GLU GLU GLN'
ALKAEEQ
```
```bash
WULF_CTRL:\> ./aatr --three 'ALKEEQ'
ALA LEU LYS GLU GLU GLN
```
