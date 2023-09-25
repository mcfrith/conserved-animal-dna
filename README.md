# Conserved animal DNA

Here is some data that was used in the study [DNA conserved in diverse
animals since the Precambrian controls genes for embryonic
development][paper]: see there for explanations.

The animal genomes (e.g. homSap: *Homo sapiens*) are detailed in the
2023 section of <https://github.com/mcfrith/last-genome-alignments>.

The study mentions 50-base extensions.  The [bed][] files here are the
initial ones before any such extension, and the fa (fasta) files are
the final ones after any such extension.

## Human genes and pseudogenes

The bed files in homSap have genome coordinates of protein-coding
regions, RNA genes, and pseudogenes.

## Chimaera data

The files in calMil have data for [chimaera][]:

* calMil.fa.out is the output of [RepeatMasker][].

* The bed files have coordinates of protein-coding regions, RNA genes,
  and pseudogenes.

* calMil-segments.fa has non-genic chimaera DNA that is conserved in
  human.

## last-train files

try1.train and try2.train are files made by [last-train][].

## Other data

The "genes.bed" files have coordinates of protein-coding regions and RNA
genes, for some of the genomes.

The "X-versus-Y.fa" files have regions of genome X that are conserved
in genome Y, excluding the "genes.bed" regions.

## Conserved deuterostome DNA

braFlo-calMil-sacKow-chunks.fa has non-genic chimaera DNA that is
conserved in invertebrates, and corresponding DNA from lancelet and
acorn worm.

[bed]: https://genome.ucsc.edu/FAQ/FAQformat.html#format1
[chimaera]: https://en.wikipedia.org/wiki/Callorhinchus
[last-train]: https://gitlab.com/mcfrith/last/-/blob/main/doc/last-train.rst
[paper]: https://www.biorxiv.org/content/10.1101/2023.06.18.545459v2
[RepeatMasker]: http://www.repeatmasker.org/
