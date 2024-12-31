# Notes from Testing this Repository

## Table of Contents

- [2024-12-31](#2024-12-31)

## 2024-12-31

### Code base

- decided to fork the repo rather than using a parital clone.
- running in a Codespaces since there are many dependencies not on the approved list.
    - had to add extensions for python, jupyter, copilot, etc. Should probably create a dev
    configuration file to travel with repo. #TODO.

### Environment

- attempted to use the 1_Software_Environmnet.ipynb. They use mamba, which would have to be added to
    my codespace. For simplicity, just bash to create it with conda.  
    `conda env create -f environment_locked.yaml`

### CDS access

- using account associated with nicki.shobert@shanwil.com
- successfully created the credentials file using the 2_CDS_Access.ipynb. 
- It stores in the codespace home directory, so it's as safe as that is... at least it is not in my
    git history.

### Access HyP3 Data

- log in using nicki.shobert@shanwil.com account
- create a directory for data here: /workspaces/opensarlab_MintPy_Recipe_Book/asf_data/test1
- dang, previous order expired. need to create new hyp3 order
- 


