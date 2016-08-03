# RepeatHMM: to Detect trinucleotide repeats from long reads of DNA sequencing

RepeatHMM is a novel computational tool to accurately detect trinucleotide repeats and trinucleotide repeat disorders (TRD) from given long reads for a subject of interests. It takes long reads from a subject as input, and uses a novel unsymmetrical sequence alignment (UnsymSeqAlg) to map all reads to a specific gene of interest in a reference genome (hg38 here), and then, employs UnsymSeqAlg for optional error correction of repeat regions. After that, It uses a hidden Markov model (HMM) method to estimate the repeat count for each of long reads with higher coverage. Lastly, it will detect one or two peaks of expansion counts for the subject of interest. 

RepeatHMM is evaluated on simulation data with in silico produced repeat counts and their simulation long reads, and also a real dataset of the ATXN3 gene for SCA3. The results demonstrate that our tool is able to accurately estimate expansion counts from long reads.

RepeatHMM can also take a BAM file as input to find trinucleotide repeats for tens of known genes or a gene given by users, after all reads are well aligned to a reference genome. Our tool is very user friendly and easy to install and use. 

## Contact

If you have any questions/issues/bugs, please post them on [GitHub](https://github.com/WGLab/RepeatHMM/issues). They would also be helpful to other users. 

## More information

Copyright 2016 [USC Wang Lab](http://genomics.usc.edu/)
