# Coding club - Plotting a manhattan plot of Fst in R

FST is a widely used statistic in populations genomics. It describes the relative genomic divergence between populations. The dataset you will practice with is real - is shows regions of divergence between two three-spined stickleback ecotypes, one which migrates to sea and another which does not. A great way of plotting statistics like FST, which you expect to vary across the genome, is using a manhattan plot (so named because of it's similarity to the peaks and troughs of the New York skyline). This will allow you to locate regions of the genome that are strongly differentiated between ecotypes.

## Use your new ggplot skills to have a go at making a manhattan plot in R:

1. Start by making a plot for a single chromosome (hint you will need to use your knowledge of filtering to do this).

2. Then have a go at plotting Fst across the whole genome. Think about your x-axis and how you might get it looking nice. Have a try using colour to distinugish the different chromosomes.


## Description of data file:

Chromosome name - names of chromosomes as they appear in the genome assembly

Chromosome number - corresponding chromosome numbers

Site - the centre point of 5Kb windows in which FST was calculated

FST - Wier and Cockhams weighted FST comparing two stickleback ecotypes

Chromosome length - the total length in bp of each chromosome

Chromosome midpoint - the midpoint in bp of each chromosome

Chromosome cumulative length - the total cumulative length in bp of all chromosomes in order from 1 to 22 for ease of plotting whole genome manhattan plots

Chromosome cumulative midpoint - the cumulative midpoints of each chromosome when ordered 1 to 22 for ease of plotting whole genome manhattan plots
