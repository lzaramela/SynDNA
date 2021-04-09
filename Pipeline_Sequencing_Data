# Pipeline used to process the sequencing data

## Removing adapter

### for i in `ls *.fastq`;do trimmomatic SE -phred33 ${i} ${i}.trimmed.fastq ILLUMINACLIP:TruSeq2-SE.fa:2:30:10 LEADING:10 TRAILING:10 SLIDINGWINDOW:4:15 MINLEN:36; done
