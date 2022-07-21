# NMA_project

**Question:**
- How are state transitions correlated across brain areas? Which areas lead/follow?
- How are state transitions changed across different trial types(correct/miss/passive)? Can we predict trial_types from hidden state sequences?
- Which brain areas play a important role in defferent trials?

**Dataset:**
- Steinmetz dataset

**To do list:**
- explore how to use Steinmetz dataset, refer to dataset notebook
- explore how to use PossionHMM to find hidden states, refer to notebook
    - ssm packages
- find the hidden states across different areas
    - focus on certain areas, eg, motor areas, visual cortex
    - quantify the difference of state sequence across different areas
        - transition time
        - interval distribution
    - quantify the time delay (lead/follow relation) across different areas
- find the fidden states across different trial_types
    - quantify the difference of state sequence across trial_types
        - transition time
        - interval distribution
    - construct a decoder for predicting trial_types from hidden state sequences
- compare the state sequence difference in different trial types across different brain areas
    - to find which areas play a important role in defferent trials
