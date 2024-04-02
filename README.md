# Bodily maps of symptoms and emotions in Parkinson’s disease

This is a repository containing the original analysis maps presented in the article 'Bodily maps of symptoms and emotions in Parkinson’s disease' (Figures 1 and 2) published in Movement Disorders Journal in 2024 (doi: 10.1002/mds.29785). 

The maps are in NIfTI (Neuroimaging Informatics Technology Initiative) format, and they can be viewed with commonly used neuroimaging software, such as FSLeyes (https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FSLeyes) or Mango (https://mangoviewer.com).

## Maps:

**1S_T-Test_CohensD:** These are the pixelwise Cohen's D effect size maps. They have been created by 1) running one sample linear model test in one group and 2) calculating pixelwise Cohen's D value from the resulting T-maps, based on the degrees of freedom in the analyses. The maps of the control group have the prefix "CTR_", and the maps of the PD group have the prefix "PD_"

**2S_T-Test:** These are the pixelwise T-maps of the group comparisons. They have been created by running two-sample linear model test between the groups. Pixelwise positive values indicate greater values in the PD group, and negative values indicate smaller values in the PD group.

**PCA_Analysis:** These are the pixelwise loading maps of the PCA analysis. They have been calculated with *prcomp* in R 4.3.2. The files with the postfix "_PC1" contain the pixelwise loadings of the first principal component, and the files with the postfix "_PC2" contain the pixelwise loadings of the second principal component.


For further information about the methodology, see the article 'Bodily maps of symptoms and emotions in Parkinson’s disease'.


## Repository author:
Created by Kalle J. Niemi, Turku Brain and Mind Center, University of Turku on 2 April 2024

## Licensing:
CC BY-NC-ND 4.0 licensing applies to the files in this repository. For more information about the license, see [here](http://creativecommons.org/licenses/by-nc-nd/4.0).
