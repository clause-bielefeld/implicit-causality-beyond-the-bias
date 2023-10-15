# Beyond the Bias: Unveiling the Quality of Implicit Causality Prompt Continuations in Language Models

This is the code for our paper "Beyond the Bias: Unveiling the Quality of Implicit Causality Prompt Continuations in Language Models" (INLG 2023)

The paper can be found here: https://aclanthology.org/2023.inlg-main.15/ 

## Files
- **data**: contains prompts for producing the continuations, (model- and human produced) prompt continuations as well as results from (automatic and human) evaluations
- **scripts**: contains notebooks
- **scripts/produce-continuations.ipynb**: generate prompt continuations with GPT-2 and mGPT 
- **scripts/hyperparameter-testing.ipynb**: use automatic metrics to decide on the models' hyperparamters 
- **scripts/evaluate_continuations.ipynb**: evaluate the prompt continuations by automatic measures and investigate (correlation with) the results from the human evaluation study
