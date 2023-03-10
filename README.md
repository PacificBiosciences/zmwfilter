# zmwfilter

_zmwfilter_ provides a simple utility for filtering PacBio BAM data on ZMW ID(s), via either an
"include-list" or "exclude-list".

## Availability
The latest `zmwfilter` can be installed via the bioconda package [`pbtk`](https://github.com/PacificBiosciences/pbtk).

Please refer to our [official pbbioconda page](https://github.com/PacificBiosciences/pbbioconda)
for information on Installation, Support, License, Copyright, and Disclaimer.

## Usage
```
ID list from command line:

$ zmwfilter --include 100,200 input.bam filtered.out.bam
$ zmwfilter --exclude 50 input.bam filtered.out.bam

ID list from file:

$ zmwfilter --include good-zmws.txt input.bam filtered.out.bam
$ zmwfilter --exclude bad-zmws.txt input.bam filtered.out.bam
```

## Disclaimer
THIS WEBSITE AND CONTENT AND ALL SITE-RELATED SERVICES, INCLUDING ANY DATA, ARE PROVIDED "AS IS," WITH ALL FAULTS, WITH NO REPRESENTATIONS OR WARRANTIES OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, ANY WARRANTIES OF MERCHANTABILITY, SATISFACTORY QUALITY, NON-INFRINGEMENT OR FITNESS FOR A PARTICULAR PURPOSE. YOU ASSUME TOTAL RESPONSIBILITY AND RISK FOR YOUR USE OF THIS SITE, ALL SITE-RELATED SERVICES, AND ANY THIRD PARTY WEBSITES OR APPLICATIONS. NO ORAL OR WRITTEN INFORMATION OR ADVICE SHALL CREATE A WARRANTY OF ANY KIND. ANY REFERENCES TO SPECIFIC PRODUCTS OR SERVICES ON THE WEBSITES DO NOT CONSTITUTE OR IMPLY A RECOMMENDATION OR ENDORSEMENT BY PACIFIC BIOSCIENCES.
