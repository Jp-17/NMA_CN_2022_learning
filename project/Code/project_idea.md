# NMA_project

**Question:**
- How are state transitions correlated across brain areas? Which areas lead/follow?
- How are state transitions changed across different trial types(hit/miss/false_alarm/correct rejection)? Can we predict trial_types from hidden state sequences?

**Dataset:**
- Steinmetz dataset

**To do list:**
- explore how to use Steinmetz dataset, refer to dataset notebook
- explore how to use PossionHMM to find hidden states, refer to notebook
    - ssm packages
- find the hidden states across different areas
    - quantify how well the brain activity is captured by HMM
    - quantify the time delay (lead/follow relation) across different areas
- find the fidden states across different trial_types
    - quantify the difference of state sequence across trial_types
    - construct a decoder for predicting trial_types from hidden state sequences
    - compare the state sequence difference (decoder accuracy) from different brain areas
