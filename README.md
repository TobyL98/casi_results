# casi_results
The results for the paper describing the 'sequence inferred fingerprint' python package to identify a species from ZooMS data. This data should be enough regenerate the results included in the paper. 

## Paper folders
The inputs that are required 

The theoretical peptide lists that were generated from NCBI COL1 sequences from NCBI are found within the 'theoretical_peptides' folder. The final peptide lists for each species  used for comparison with the experimental peaks is within 'theoretical_peptides/filtered'.

The results that are included within the paper for both the 'selected' dataset and the 'Pinhole' dataset are within the 'results' folder.

## Additional Results
We have also included some additional results that were mentioned within the paper but not included in full. These results both used the 'selected' dataset as input.

The first folder used theoretical peaks that were not filtered using LC-MS/MS data. This is called 'unfiltered_results'.

The second folder generated the theoretical peaks only accounting for hydroxylations instead of hydroxylations and deamidations. This is called 'no_deam_results'.

## Accessing the code
To use the python package that was used to create these results follow the link:
https://github.com/TobyL98/RP1_m-z_speciesidentify

