# DualFqz
DualCtx quality score compression

To compile:
    g++ dualfqz.cpp sfh.cpp -o dualfqz

To compress:
    dualfqz -k 2 -l 5 < a.fastq > a.df

To uncompress
    dualfqz -d < a.df > a.fastq
    
DualFqz was built by substituting DualCtx for the quality score compression module in a variant of Fqzcomp (https://sourceforge.net/projects/fqzcomp/).
