# SPEDE-SAMPLER (GMYC)

This R Shiny App is the final part of the SPEDE-SAMPLER program, and allows the user to run GMYC analyes on multiple phylogenies that have been created by randomly resampling the sequences in an aligned Fasta file.

To run this app through R, type the following into the console:

`install.packages("shiny") # install the shiny package` 

`library(shiny) # load up the shiny library` 

`shiny::runGitHub("spede-sampler", "CJMvS", ref="main") # run the app`