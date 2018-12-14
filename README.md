# DualFqz
DualCtx quality score compression

To compile:
    g++ dualfqz.cpp sfh.cpp -o dualfqz

To compress:
    dualfqz -k 2 -l 5 < a.fastq > a.df

To uncompress
    dualfqz -d < a.df > a.fastq
