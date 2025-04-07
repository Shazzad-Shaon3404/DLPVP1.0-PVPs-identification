# <span style="font-size:16px;">**DLPVP: A Multi-view Feature-Based Deep Learning Model for Phage Virion Protein Identification**</span>

## <span style="font-size:16px;">**Overview:**</span>


<span style="font-size:14px;">DHUpredET is a computational tool designed for the identification of hage Virion Protein 
from FASTA protiens sequences. This repository contains the implementation of DLPVP as well as datasets collected from previous study.</span>

## <span style="font-size:16px;">**Features:**</span>

<span style="font-size:14px;">- Identification of PVPs:
1. This work rigorously explores four feature extraction
approaches for representing peptide sequence properties,
providing useful insights into the most informative features
for identifying phage virion peptides. By evaluating
several feature representations, the study improves our
knowledge of sequence patterns contributing to accurate
PVP identification.<\br>
2. An effective hybrid deep learning framework, DLPVP,
has been proposed that combines convolutional neural
networks (CNN) and bidirectional long short-term memory
(BiLSTM) to improve the efficiency of PVP detection.
Furthermore, the research conducts a thorough ablation
analysis to acquire a better understanding of the model’s
internal functions, evaluating the contribution of various
layers and components to overall performance. <\br>
3. Overall, this study shows an elaborate pipeline that
combines several feature extraction strategies, adaptation
testing on an alternate dataset, and a potent hybrid
deep-learning classification strategy to detect PVPs.</span>



## <span style="font-size:16px;">**File Formats:**</span>

<span style="font-size:14px;">
All datasets are provided in FASTA format, which can have either a .txt or .fasta extension. 
Please go to the (https://en.wikipedia.org/wiki/FASTA_format) for more information.


## <span style="font-size:16px;">**Dataset information:**</span>
## ⏩ Highlight Feature Categories

This study proposes a robust approach for developing a DLPVP model. The approach utilizes a comprehensive feature extraction strategy, leveraging features from four descriptors:

### **BERT**

### **nGRAMS**


### **AAC_NT**


### **SOC**
### **SOC+AAC_NT+nGRAMS+BERT= Multi-view**


## Workflow Diagram

![Workflow](https://drive.google.com/uc?id=16QdqaXOfEvVjoij08vpEWDOb-rnO7u3A)

**For more information please see the notebook**

## Proposed Architecture of the study
![MODEL](https://drive.google.com/uc?id=16QdqaXOfEvVjoij08vpEWDOb-rnO7u3A)




## Our DLPVP model achieved significant improvements over previous approaches....
![SOTA](https://drive.google.com/uc?id=1yeMSqZ3G5lOGIbzZbyQAzVBi0LnxgU82)





## <span style="font-size:16px;">**Requirements:**</span>

<span style="font-size:14px;">
To run DHUpredET, ensure the following packages are installed:
- matplotlib==3.6.2
- numpy==1.24.4
- scikit-learn==1.1.3

You can install these packages using pip:

```bash

pip install matplotlib==3.6.2

pip install numpy==1.24.4

pip install scikit-learn==1.1.3






