# AlignmentPlotter

This is a simple script for running a BLAST alignment on local files and outputting an easy to follow dot/line plot of the results. It is similar to [D-GENIES](https://dgenies.toulouse.inra.fr), but D-GENIES only works well for very large sequence sets like whole genomes. AlignmentPlotter can work for relatively short sequences and is mainly used to show the "composition" of a longer sequence in terms of other shorter sequences.

I made this mainly to show what different DNA sequences were inserted into the genome during "failed" genome editing events. The query sequence is a chunk of long-read whole-genome sequencing data and the subjects are various pieces of DNA that were introduced during the gene editing process. I think this is a cleaner approach than what I had been previously doing, which was drawing out the pieces by hand in powerpoint.

Here are example outputs I used in (link to paper once I publish it):
<img src="/Files/AlignmentPlotter1.png"  width="60%" height="30%">
