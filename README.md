A tool that will grab PGS Catalog Data and allow for automatic scoring of samples and comparison against the EU Control Sample Set

Required Software:
* R - 3.6.1
* Python - 2.7.16

Sample Run
```
Rscript PGSMain.R --file=sample.vcf.gz --ref=/g/data/jb96/References_and_Databases/hs37d5.fa/hs37d5x.fa --pgs-id=PGS000073
```

The tool will generate a boxplot, quantile/boxplot.png, and CSV,sample_out.csv. These can be viewed concurrently by accessing dashboard.Rmd

These files demonstrate the stratified risk of samples against control samples and risk of each sample for the last condition respectively.
