# MMUbiPred
Multimodal deep learning for predicting protein ubiquitination sites

## Abstract
Ubiquitination is a crucial post-translational modification regulating various biological functions. In this study, we present MMUbiPred, a deep learning-based approach for predicting ubiquitination sites across general, human-specific, and plant-specific datasets. Protein sequence fragments around ubiquitination and non-ubiquitination sites were encoded using one-hot encoding, embeddings, and physicochemical properties, processed through deep learning architectures, and combined with a multi-layer perceptron to form the final model. MMUbiPred achieved 77.25% accuracy, 74.98% sensitivity, 80.67% specificity, 0.54 Matthew’s correlation coefficient, and an AUC of 0.87 on an independent test set, outperforming other leading predictors. A robust predictor and ubiquitination dataset has been developed, providing a valuable resource for benchmarking and discovering unknown ubiquitination sites and advancing knowledge in the field.

## Significance Statement
MMUbiPred represents a significant advancement in ubiquitination site prediction by utilizing multimodal deep learning techniques with a robust and comprehensive dataset. This framework surpasses existing predictors in accuracy and reliability across general, human-specific, and plant-specific datasets. By providing a powerful tool for identifying ubiquitination sites, MMUbiPred facilitates deeper insights into ubiquitination mechanisms, advancing our understanding of critical cellular processes and disease mechanisms.

<br>
<img max-width = 100% alt="image" src="https://github.com/PakhrinLab/MMUbiPred/blob/main/UBIQUITINATION_Draft_1_Colored.png">
The comprehensive framework for MMUbiPred
<br>
<br>

## System Requirements
Programs were executed using anaconda version: 2020.07, please use the same

The programs were developed in the following environment. python : 3.8.3.final.0, python-bits : 64, OS : Linux, OS-release : 5.8.0-38-generic, machine : x86_64, processor : x86_64, pandas : 1.0.5, numpy : 1.18.5, pip : 20.1.1, scipy : 1.4.1, scikit-learn : 0.23.1., keras : 2.4.3, tensorflow : 2.3.1.

## Comparison with DeepUBI
Please place the Large_Dataset_Independent_Test_Set_Assessment.ipynb, aaindex31.txt, Positive_10_percent_independent_test_set_DeepUBI.fasta, Negative_10_percent_independent_test_set_DeepUBI.fasta, and DeepUBI_AAindex_One_Hot_Emb_drop_out2423.h5 in the same directory where you will execute the python program. Execute the Large_Dataset_Independent_Test_Set_Assessment.ipynb python program to obtain the reported result for general ubiquitination sites.

## Comparison with Shrestha et al. Ubiquitination Predictor
Please execute MMUbiPred_Comparision_with_Palistha_Shresthas_ubiquitination_ProtGPT2_finetuning_method.ipynb file all the relevant data, model and are uploaded in the github. MMUbiPred has significantly outperformed ubiquitination predictor available at https://www.nature.com/articles/s41467-024-51071-9

## Comparison with hCKSAAP_UbSite 
Please place the Human_Dataset_Independent_Test_Set_Assessment.ipynb, aaindex31.txt, Ubiquitylation_81_window_Testing_positive.fasta, Ubiquitylation_81_window_Testing_negative.fasta, and DeepUBImodel_HubiPred_AAindex_One_Hot_Emb_drop_out_changed73887.h5 in the same directory where you will execute the python program. Execute the Human_Dataset_Independent_Test_Set_Assessment.ipynb python program to obtain the reported result for Human ubiquitination sites.

## Comparison with UbiComb
Please place the Plant_Dataset_Independent_Test_Set_Assessment.ipynb, aaindex31.txt, Positive_UbiCom_testing.fasta, Negative_UbiCom_testing.fasta, and UBICOMB_DeepUBI_AAindex_One_Hot_ProtT5_drop_out_Changed3257.h5 in the same directory where you will execute the python program. Execute the Plant_Dataset_Independent_Test_Set_Assessment.ipynb python program to obtain the reported result for plant ubiquitination sites.

## All Data, programs and models can be found in the following link
https://drive.google.com/drive/folders/1Bcx55mlv4FKqK2XVTww8XBaNqocnP71q?usp=sharing

## Help and Contact
If you need any help please contact Dr. Subash C. Pakhrin at pakhrins@uhd.edu
https://www.uhd.edu/faculty/pakhrins.aspx
