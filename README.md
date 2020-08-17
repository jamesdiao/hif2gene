# hif2gene: Dense, high-resolution mapping of cells and tissues from pathology images for the interpretable prediction of molecular phenotypes in cancer

## Notice
> Scripts, data, and figures are now hosted on the PathAI Github. Please visit [https://github.com/Path-AI/hif2gene](https://github.com/Path-AI/hif2gene). 

## Overview

> `hif2gene` is the primary code repository for reproducing analyses in Diao, Chui, and Wang et al. 2020: "Dense, high-resolution mapping of cells and tissues from pathology images for the interpretable prediction of molecular phenotypes in cancer". The preprint is available on `bioRxiv` at [https://www.biorxiv.org/content/10.1101/2020.08.02.233197v2](https://www.biorxiv.org/content/10.1101/2020.08.02.233197v2).

## Authors

\*James A Diao<sup>1,2</sup>, \*Wan Fung Chui<sup>1,2</sup>, \*Jason K Wang<sup>1,2</sup>, Richard N Mitchell<sup>2,3</sup>, Sudha K Rao<sup>1</sup>, Murray B Resnick<sup>1,4</sup>, Abhik Lahiri<sup>1</sup>, Chirag Maheshwari<sup>1</sup>, Benjamin Glass<sup>1</sup>, Victoria Mountain<sup>1</sup>, Jennifer K Kerner<sup>1</sup>, Michael C Montalto<sup>1</sup>, Aditya Khosla<sup>1</sup>, Ilan N Wapinski<sup>1</sup>, \*Andy H Beck<sup>1</sup>, \*Amaro Taylor-Weiner<sup>1</sup>, \*Hunter Elliott<sup>1</sup>

- <sup>1</sup>PathAI, Inc., Boston, MA, 02215, USA
- <sup>2</sup>Harvard-MIT Program in Health Sciences and Technology, Harvard Medical School, Boston, MA, 02115, USA
- <sup>3</sup>Department of Pathology, Brigham and Women’s Hospital, Harvard Medical School, Boston, Massachusetts
- <sup>4</sup>Department of Pathology, Warren Alpert Medical School of Brown University, Providence, Rhode Island
- *These authors contributed equally

## Abstract 

While computational methods have made substantial progress in improving the accuracy and throughput of pathology workflows for diagnosis, prognosis, and the prediction of genomic features, a lack of interpretability remains a significant barrier to clinical integration. In this study, we present a novel approach for prediction of clinically-relevant molecular phenotypes from histopathology whole-slide images (WSIs) using human-interpretable image features (HIFs). Our method leverages >1.6 million annotations from board-certified pathologists across >5,700 WSIs to train deep learning models for high-resolution tissue classification and cell detection across entire WSIs in five cancer types. Combining cell- and tissue-type models enables computation of 607 HIFs that comprehensively capture specific and biologically-relevant characteristics of multiple tumors. We demonstrate that these correlate with well-known markers of the tumor microenvironment (TME) and can predict diverse molecular signatures, including immune checkpoint protein expression and homologous recombination deficiency (HRD). Our HIF-based approach therefore provides a novel, quantitative, and interpretable window into the composition and spatial architecture of the TME.

