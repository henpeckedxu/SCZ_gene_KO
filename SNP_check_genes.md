`cat genes.txt | while read line; do qsub SNP_check.sh $line; done`
