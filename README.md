# pacbio-polyATGC-trimmer-recursion
A shorter version after implementing a array recompile and storing the variables while running a subtle part of the recursion. Brian Haas told me to find it a way to make it shorter. I implemented a recursive recompile with in the code and remove all the if iterations. so the code is now only a block of code and not blocks of code. I stored the variables in an array and then put a recursive recompile on the array. 

```
longreadpolyATGCtrimmer("/Users/gauravsablok/Desktop/CodeCheck/fasta_sample_datasets/test_sample_short.fasta",
                              polyATGCstretch_type="G")
	ids	sequences	stretch_count	trimmed_sequences_new
0	>1	GCAGCGTACGTGGTTGGATCAATTAGTGGGGCACATTTGAATCCAG...	[27, 30]	GCAGCGTACGTGGTTGGATCAATTAGTGCACATTTGAATCCAGCTT...
1	>2	GCAGCGTACGTGGTTGGATCAATTAGTGGGGCACATTTGAATCCAG...	[27, 30]	GCAGCGTACGTGGTTGGATCAATTAGTGCACATTTGAATCCAGCTT...
2	>3	GCAGCGTACGTGGTTGGATCAATTAGTGGGGCACATTTGAATCCAG...	[27, 30]	GCAGCGTACGTGGTTGGATCAATTAGTGCACATTTGAATCCAGCTT...
3	>4	CGAAAATTACTTCGGTACAATGCTTGTATACATGGGCAAAGCACAC...	[33, 36]	CGAAAATTACTTCGGTACAATGCTTGTATACATCAAAGCACACGGT...
```
Gaurav Sablok \
Academic Staff Member \
Bioinformatics \
Institute for Biochemistry and Biology \
University of Potsdam \
Potsdam,Germany
