## Is it time to kill SAM/BAM/CRAM?

### Obtaining data

For demonstration, chromsome 20 aligned file for `HG00096` from the [1000g project](https://www.internationalgenome.org). To follow along with the various parts of this repository, it is necessary to download this file and place it in `Data/`. It can be obtained from AWS:

```bash
mkdir Data/
 aws s3 cp s3://1000genomes/phase3/data/HG00096/alignment/HG00096.chrom20.ILLUMINA.bwa.GBR.low_coverage.20120522.bam Data/
 ```