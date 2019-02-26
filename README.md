
## Getting started

The `getIntrons.sh` uses gencode GTF annotation files to create an intronic GTF file which is usually unavailable. Running the script is simple. First install the following:

* Install [BEDops](https://bedops.readthedocs.io/en/latest/index.html)
* Install (bedtools)[https://bedtools.readthedocs.io/en/latest/]
* Annotation files, (gencode human)[https://www.gencodegenes.org/human/] or any annotation in GTF format that contains exon and gene features

Once installed, edit the `GENE_ANNOT_FILE` variable in `getIntrons.sh` such that it points to where your annotations are. Then run:

```
./getIntrons.sh
```

Once finished, you should see `introns.gtf` in your directory.
