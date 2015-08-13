
# Add prefix and separator to all identifiers in FASTA

Usage:

```
python prefix_fasta.py input.fasta output.fasta --separator "." --prefix "sample1"
```

Each id in the input file is prepended by prefix and separator.

e.g. before:
```
>123
...
```
after:
```
>sample1.123
...
```

See also input.fasta and corresponding output.fasta for complete example.
