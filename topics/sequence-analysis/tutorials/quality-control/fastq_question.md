> ### {% icon question %} Questions
>
> 1. How are the DNA sequences stored?
> 2. What are the other entries of the file?
>
> > ### {% icon solution %} Solution
> > 1. The DNA sequences are stored in a FastQ file, in the second line of every 4-line group
> > 2. This file format is called [FastQ format](https://en.wikipedia.org/wiki/FASTQ_format). It stores sequence information and quality information. Each sequence is represented by a group of 4 lines with the 1st line being the sequence id, the second the sequence of nucleotides, the third a transition line and the last one a sequence of quality score for each nucleotide.
> {: .solution }
{: .question}
