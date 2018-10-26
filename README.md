# interleave_paired_fastq
Interleaves separated pair-ended FASTQ files

    chmod +x interleave_fastq
    ./interleave_fastq -h

This will give you:

    interleave_fastq [-h] filename.1.fq[.gz] filename.2.fq[.gz]

It works with either compressed and uncompressed files.

If the input is compressed, the output will also will be.
So try something like:

    ./interleave_fastq sample.1.fq.gz sample.2.fq.gz > sample.fq.gz

