PRIME - Personalized ReconstructIon of Metabolic models (DOI: http://dx.doi.org/10.7554/eLife.03641.002)

To run the optimization step the PRIME code uses the Tomlab software which is not a free software.

The PRIME procedure should be run as follows(Each of the scripts below is fully documentized):
1. findMaxBound - Finding the maximal bound (Step 1) in main text.
2. findRange - Finding the minimal and maximal values of the normalization range.
3. PRIME - Running the PRIME main procedure.

The fields 'genes_unique' and 'genes_unique_map' should be added to the human model and appear as '.mat' files in the code directory.  