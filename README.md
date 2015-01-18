# bro-size

Estimate size of a package by browserifying, uglifying and gzipping (prints all 3 sizes).

## Usage

```
npm install -g bro-size
```

```
bro-size leap-model.js -x underscore

                      Size
--------------------  --------
Uncompressed          31.77 kB
Compressed            10.74 kB
Compressed + Gzipped  3.74 kB

```

Accepts all browserify options, e.g. `-x` to exclude some module from the size estimation.


# TODO

- [ ] an option to list sizes of each module (--list)
- [ ] an option to only print the size final compressed and gzipped in bytes (--plain)