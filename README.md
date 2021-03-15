# zmwfilter

Provides a simple ZMW ID filtering utility for BAM data, via either an
"include-list" or "exclude-list".

_zmwfilter_ is available on our servers as a GNU module.

## Usage examples
```
ID list from command line:

$ zmwfilter --include 100,200 input.bam filtered.out.bam
$ zmwfilter --exclude 50 input.bam filtered.out.bam

ID list from file:

$ zmwfilter --include good-zmws.txt input.bam filtered.out.bam
$ zmwfilter --exclude bad-zmws.txt input.bam filtered.out.bam
```
