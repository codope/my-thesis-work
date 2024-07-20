# Undergraduate Thesis at NIT Trichy, 2012

**Access Methods for Social Inclusion**

[brief_summary.pdf](./brief_summary.pdf) contains an excerpt, including problem setup and conclusion, from the thesis I submitted for my Bachelor's in Computer Science at [NIT Trichy, India](https://www.nitt.edu). Complete thesis is contained in [ug_thesis_access_methods.pdf](./ug_thesis_access_methods.pdf). The source code is available in the appendix section of the thesis.

## Abstract

Poor sections of the society who lack an internet connection should be able to share the internet facility belonging to a richer community nearby for free. However, the real challenge is to make this privilege without denting the bandwidth allocated for the owner of the connection. We analyze existing congestion control mechanisms, and we see fit in a new experimental protocol called as LEDBAT (Low Extra Delay Background Transport), a delay based congestion control mechanism, which is extensively used in torrent applications to solve problems with similar goals. Our work implements the latest version of LEDBAT and develops a Linux kernel module for the same. We have implemented the latest version in a well-known network simulator NS2, by performing extensive experiments. In order to ensure only a genuine poor user participates, we have fingerprinted the LEDBAT traffic based on utilization and classified flows to detect non-LEDBAT users.

# Master's Project at Georgia Tech, 2020

**ICD Code Prediction From Medical Records**

The full project report is contained in [BD4H_ICD_Prediction_Paper_Final.pdf](./BD4H_ICD_Prediction_Paper_Final.pdf). The presentation for this work is available on [YouTube](https://www.youtube.com/watch?v=H4Ngmx9sW9Q). The source code for this work is in [this](https://github.gatech.edu/akumar689/bd4h) GitHub repository (you need @gatech login). Also, made available in [this](https://colab.research.google.com/drive/1bfm9I4EvL9TeeLj5lxe94CegrmO4VZvF?usp=sharing) Google Colab notebook.

## Abstract

Automatic ICD coding is an important text classification task in clinical domain that assigns relevant ICD-9 codes for patient visits that describe the diagnosis and procedure treatments given to the patient. Annotating these codes is labour intensive task and heavily rely on domain knowledge. In this work, we propose a hierarchy augmented network trained on joint-loss framework leveraging the hierarchy of labels to predict the full ICD-9 codes given a patient ICU discharge summary record. With initial experiments, we see that joint loss framework, helps in achieving up to 2.2% better micro-F1 score on full set prediction of ICD-9 codes. In another setup, we note 7% absolute improvement in micro-F1 score on using fine-tuned BERT embeddings on a feed-forward network baseline. Label-wise document attention boosts the performance of the system by 6% on micro-F1 score. 
