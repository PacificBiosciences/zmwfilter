# zmwfilter

Provides a simple ZMW ID filtering utility for PacBio BAM data, via either an
"include-list" or "exclude-list".

## Availability
The latest `zmwfilter` can be installed via the bioconda package `zmwfilter`.

Please refer to our [official pbbioconda page](https://github.com/PacificBiosciences/pbbioconda)
for information on Installation, Support, License, Copyright, and Disclaimer.

## Usage examples
```
ID list from command line:

$ zmwfilter --include 100,200 input.bam filtered.out.bam
$ zmwfilter --exclude 50 input.bam filtered.out.bam

ID list from file:

$ zmwfilter --include good-zmws.txt input.bam filtered.out.bam
$ zmwfilter --exclude bad-zmws.txt input.bam filtered.out.bam
```
