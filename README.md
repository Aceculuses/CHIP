# CHIP
```
sambamba view -h -t 2 -f bam -F "[XS] == null and not unmapped  and not duplicate" $sample.sort.bam > $sample.uniq.aln.bam
```
