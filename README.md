# AI-model-for-eHCC
## Background
Combination of convolutional neural networks and machine learning techniques were used to extract unique features that distinguish eHCC from HGDN from H&E images and RNA expression profiles. We then integrated these multimodal features to develop a classification model for diagnosing HGDN and eHCC, and further validated it on an independent test set . Finally, we evaluated the prognostic relevance of the multimodal features in another cohort of 365 patients with liver cancer.

We proposed two-stage multi-scale deep learning model (TMC-net) to extract superior local HE image features.

## Usage
The modeling and analysis of HE image were developed in Python (3.9). The pre-processing of RNA data, differential gene expression and functional analysis were developed in R version (4.1.3).

For detailed information on the specific modeling and statistical analysis methods, please refer to the supplementary methods.

The **transcriptomics** gene and functional analysis code can be obtained from /AI-model-for-eHCC/RNA.  
The **deep learning model TMC-net** modeling code can be obtained from /AI-model-for-eHCC/TMC-net.  
The **candidate biomarker screening** and **XGBoost** modeling code can be obtained from /AI-model-for-eHCC/RNA_model.  
The **multimodal model** modeling code can be obtained from /AI-model-for-eHCC/multimodal_model.  
The **survival analysis** modeling code can be obtained from /AI-model-for-eHCC/supplementary.  

## Citation
If you use code or data in this project, please cite:

- Jing SY, LI XL, et al. 2025. "Multimodal AI model for early detection of hepatocellular carcinoma". 
## Maintainers
[@jessiya](https://github.com/jessiya825),
