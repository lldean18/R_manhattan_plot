#Coding club - Plotting a manhattan plot of Fst in R

Use your new ggplot skills to have a go at making a manhattan plot in R:

1. Start by making a plot for a single chromosome (hit you will need to use your knowledge of filtering to do this).

2. Then have a go at plotting Fst across the whole genome. Think about your x-axis and how you might get it looking nice. Have a try using colour to distinugish the different chromosomes.



This repository contains an FST data file for students to use to practice making Manhattan plots in R.
The data file contains the columns:
Chromosome name - names of chromosomes as they appear in the genome assembly
Chromosome number - corresponding chromosome numbers
Site - the centre point of 5Kb windows in which FST was calculated
FST - Wier and Cockhams weighted FST comparing two stickleback ecotypes
Chromosome length - the total length in bp of each chromosome
Chromosome midpoint - the midpoint in bp of each chromosome
Chromosome cumulative length - the total cumulative length in bp of all chromosomes in order from 1 to 22 for ease of plotting whole genome manhattan plots
Chromosome cumulative midpoint - the cumulative midpoints of each chromosome when ordered 1 to 22 for ease of plotting whole genome manhattan plots
