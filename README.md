# fast-copy
Python script for fast parallel copying of files between two locations.
Initially developed for use with Google Colab notebooks, where the copying on numerous small files can take a long time. This script achieves >50X speed improvement.

## How to use
```
python fast-copy.py source destination
```
where `source` is the source folder and `destination` is the destination folder.
