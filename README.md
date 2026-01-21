# Cell2Sentence – Inference Experiment Log 💼
This repository contains a record of experiments that observe the characteristics of output representations by **performing inference on F embeddings** using the already defined structure of the Cell2Sentence model, **without retraining the model**.
  
All experiments were conducted using Jupyter Notebooks, and each notebook proceeds in a way that questions raised in previous experiments are examined in subsequent ones.
<br/>
<br/>

## Experimental Setup 🧪

### 1. Initial Inference Experiment  
**`initial_exp/cell2sentence_f_inference_exp1.ipynb`**
  
- Verified that the Cell2Sentence inference pipeline runs correctly  
- Checked the input data format and the shape of the output F embedding  
- Examined the value range and basic distribution of the embedding  
  
→ Purpose: understanding the model structure and performing a sanity check
<br/>
<br/>

### 2. Observing Embedding Changes with Input Variations  
**`analysis_exp/cell2sentence_f_inference_exp2.ipynb`**  
**`analysis_exp/cell2sentence_f_inference_exp3.ipynb`**
  
- Observed changes in F embeddings while modifying input cell representations  
- Compared embedding differences under the same structure but different inputs  
- Identified change patterns through simple numerical comparisons and visualizations  
  
→ Understanding how embeddings respond to input variations
<br/>
<br/>

### 3. Embedding Stability and Distribution Analysis  
**`analysis_exp/cell2sentence_f_inference_exp4.ipynb`**  
**`analysis_exp/cell2sentence_f_inference_exp5.ipynb`**

- Checked embedding variance across repeated inference runs  
- Observed sensitivity to noise or small input changes  
- Visualized the overall embedding distribution  
  
→ Verifying stability as a representation
<br/>
<br/>

### 4. Analysis Summary and Usability Assessment  
**`analysis_exp/cell2sentence_f_inference_exp6.ipynb`**  
**`analysis_exp/cell2sentence_f_inference_exp7.ipynb`**
  
- Summarized results from previous experiments  
- Qualitatively evaluated whether F embeddings can be used for downstream analysis  
- Compiled characteristics observed throughout the experiments  
  
→ A concluding step to assess whether “this embedding can be used”
<br/>
<br/>

## Directory Structure 🗂️
```
Cell2Sentence_reference-main/
├─ initial_exp/
│  └─ cell2sentence_f_inference_exp1.ipynb
│
└─ analysis_exp/
   ├─ cell2sentence_f_inference_exp2.ipynb
   ├─ cell2sentence_f_inference_exp3.ipynb
   ├─ cell2sentence_f_inference_exp4.ipynb
   ├─ cell2sentence_f_inference_exp5.ipynb
   ├─ cell2sentence_f_inference_exp6.ipynb
   └─ cell2sentence_f_inference_exp7.ipynb
```
<br/>
<br/>

## Reference Paper 🖋️
- [Cell2Sentence: Teaching Large Language Models the Language of Biology](https://www.biorxiv.org/content/10.1101/2023.09.11.557287v3)
<br/>
<br/>
