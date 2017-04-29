# aatr
Amino Acid Translator
---
AATR is a simple bash script that translates an three letter amino acid sequence 
obtained from a PDB file and outputs the equivalent single letter sequence. It is
meant to be used as a command line tool like `sed` (in fact, the tool is built entirely
on it), so you may keep it in your `/bin/` if you wish to use as a tool in other 
scripts. The script is invoked as:
```bash
aatr '[sequence]'
```
