
A bash script `SNP_check.sh` was created to check SNPs in each gene in `genes.txt` file. 
```
cat genes.txt | while read line; do qsub SNP_check.sh $line; done
```
