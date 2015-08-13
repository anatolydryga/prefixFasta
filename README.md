
# Add prefix and separator to all identifiers in FASTA

Usage:

```
prefix_fasta.py input.fasta output.fasta --separator "." --prefix "sample1"
```

Each id in the input file is prepended by prefix and separator.

e.g. Before:
```
>123
...
```
After:
```
>sample1.123
...
```
