# Drug_PreScreen

As a cell biologist, I run some phenotypic drug screens in reporter cell lines to filter down test compounds from libraries of thousands, down to a few hundred. 
This enables to prioritise in-depth testing on smaller samples.

To handle the vast number or tested molecules in various conditions Pandas comes really handy!

Here I cleanup some dataset and apply some useful normalisation (z_scoring), in order to identify hit compounds. 
Hits are determined by thresholding the z scores.
These are then visualised in a Seaborn plot that overlays 2 conditions for each of the small molecules tested. 
